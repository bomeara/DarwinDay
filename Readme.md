This is the site for Darwin Day TN. It is deployed at https://bomeara.github.io/DarwinDay/.

It is deployed using hugo.

See [here](https://gohugo.io/getting-started/installing) for how to install it. Easiest is to install homebrew and then `brew install hugo`. You will also need github to get this site and modify it.

You may need to install npm for other dependencies. On a Mac:

```
brew install npm
npm install postcss-cli
npm install autoprefixer
```


# To make new content

https://github.com/victoriadotdev/hugo-theme-introduction for how to use this theme.

To make a new section on the home page, say for DarwinDay2028, do not edit content/home/index.md (that's just for the blurb at the top). Instead, from within the DarwinDay folder:

```
hugo new home/darwinday2028.md
```

Then you can edit content/home/darwinday2028.md in a text editor.

# To deploy content

Within the DarwinDay directory, just type `hugo`. It will render the site and put it in docs directory. Then `git add docs`, `git commit -m"description of what you did" -a`, `git push` to put on github.
