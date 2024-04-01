# micro-frontend
## Jest Unit Test Setup
## ESLint Setup
## Linthtml Setup
Install lint hmtl
`npm i @linthtml/linthtml` ref: https://www.npmjs.com/package/@linthtml/linthtml  
Udpate the package.json
`"lint:html": "linthtml libs/**/*.html apps/**/*.html",`
Note: Sample config file is added to this repository 
## Stylelint Setup
Add required packages 
`yarn add stylelint stylelint-config-standard stylelint-scss stylelint-order --dev`  
Initialise the stylelint  
`npx stylelint --init`  
In your package.json add script to run the style lint in the required applications  
`"lint:styles": "stylelint apps/**/*.scss libs/**/*.scss",`  
Run Lint
`yarn run lint:styles`  
Note: Sample config file is added to this repository  
## Husky pre-commit hooks
