<h1 align="center">Welcome to Trillo 👋</h1>
<p align="center" markdown="1">

  <img alt="Netlify" src="https://img.shields.io/netlify/888bad59-c4f9-45d0-a2f9-b37920d99819?style=flat-square">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Slashflex/Trillo?style=flat-square">
</p>


> Landing page created using SASS(scss synthax) to learn how it works. 7-1 pattern and BEM methodology are also used. 

## Install

```sh
npm install 
# This will install node-sass locally based on package.json
```

## Usage (If you want to make modifications to SCSS files)

```sh
npm run compile:sass 
# This will run a script from package.json which compiles scss files into css
```

```sh
npm run prefix:css
# This will add prefix for browser supports to a new file eg.(css/style.prefix.css)
```

```sh
npm run compress:css
# This will compress css/style.prefix.css into css/style.css
```

```sh
npm start
# This will watch for css changes and open and auto reload the page on change 
# (live-server must be installed globally: sudo npm i -g live-server)
```

```sh
npm run build:css
# This will run all of 3 above scripts to run into a single one 
# (if css files gets deleted, this will regenerate them based on sass folder's files)
```

## Author

👤 **Slashflex (David)**

* Twitter: [@saoud_david](https://twitter.com/saoud_david)
* Github: [@Slashflex](https://github.com/Slashflex)

## Result can be seen here
[Fake travel agency](https://fake-travel-agency.netlify.com/)
## Show your support

Give a ⭐️ if you liked this project !

***
