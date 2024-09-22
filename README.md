# README

[![Netlify Status](https://api.netlify.com/api/v1/badges/cc1ba3fe-2f38-45f6-8020-94aeb94770d2/deploy-status)](https://app.netlify.com/sites/sunthornphu-poem/deploys)

# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

## My Resources

<small>Poem is from [Thai Enquirer](https://github.com/5t3ph/11ty-sass-skeleton](https://www.thaienquirer.com/50051/an-introduction-to-the-poetry-of-sunthorn-phu/?fbclid=IwAR2wju0BXfVEYS9-p4rKkhAan9RI0LuJpgBGU-TeoA4EEU7DglHgZWNYh98))</small>

<small>Image is from [dreamloveyou](https://www.shutterstock.com/image-photo/nakhonpathom-thailand-march-52016-wax-figuressunthorn-388913131)</small>
