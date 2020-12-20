This project is structured using submodules:
- themes/vex-hugo is a submodule targetting our fork of the theme
- social-books.github.io targets the website development version code.
Do get those by executing
```
git submodule update
```

Development
```
hugo server --watch
```

Upload to development env:
```
hugo
```
Then upload files under social-books.github.io by commiting chnages to development or uploading files to production

