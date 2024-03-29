# ❔ About ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/daneeskripter/random-img-api/CodeQL)
With this package you can create API that will randomly generates images.
# 🏁 Installation
```sh
npm i randomimgapi

# Dev Version
npm i randomimgapi@dev
```
# 📜 Example
```js
const { API } = require('randomimgapi')

API({
    imgFolder: 'img', // folder where you will store images
    port: 4000, // the port on which the api will run
    apiURL: '' , // leave it blank if you want use it on main page (https://yourdomain.com/)
    apiDomain: 'localhost:4000', // your domain on which will api work (if you want to use localhost do it with port)
    rateLimit: 10 // number of allowed requests per minute
})
```
# ✅ Hosting
- Looking for free hosting for your API? Use [DisHost](https://dishost.xyz)!

# ➕ Links
- [Package link](https://www.npmjs.com/package/randomimgapi)

# Supported Versions

- ✅ = These versions are recommended for use.
- ❌ = These versions are not recommended for use.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x  | :x: |
| 1.1.x  | :white_check_mark: |
