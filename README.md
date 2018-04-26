# This is the static landing page repository for Pocket Chef.

The purpose of this page is to create a user waitlist for beta users of Pocket Chef.

## Get Started

First navigate to a directory you want to have the repository in
```
cd desktop/folder-i-want-it-in
```

Clone or download the repo
```
git clone https://github.com/trypocketchef/trypocketchef.git
```

Make sure you have gulp installed for minifying our css. DO NOT EDIT IN `min.css` files. I'm onto you... Use your package manager of your choice, we will be using NPM for this example.
```
npm install --global gulp
```

And you are ready to go!

## Editting design

There is only 1 main file we will be using for any edits. `index.html`. You can also edit the `.css` files but that requires some additional steps.

To save the changes made in the css files you must first minify it with gulp. Run this after saving changes to `xxxx.css`
```
gulp
```

Yeah... that's it. The gulp build process in `gulpfile.js` will build the css as `min.css` and you are good to go!
