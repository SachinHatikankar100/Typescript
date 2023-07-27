# Typescript

`npx create-react-app todo-react --template typescript`
for starting react with typescript poject

`npm install eslint --save-dev` for linting features 

Type `npx eslint --init` for configuring the eslint with below options. Creates `eslintrc.json` file with all configurations
 How would you like to use ESLint? · style
--What type of modules does your project use? · commonjs
--Which framework does your project use? · react
--Does your project use TypeScript? · No / Yes
--Where does your code run? · browser
--How would you like to define a style for your project? · guide
--Which style guide do you want to follow? · standard-with-typescript
--What format do you want your config file to be in? · JSON


`npm install  eslint-plugin-import eslint-import-resolver-typescript --save-dev` required to correctly resolve the ES6 style imports and files with typescript 
and TSX extensions.
This requires eslint plugin import

`npm i --save-dev prettier eslint-config-prettier eslint-plugin-prettier`
eslint-config-prettier -turns off all rules in that are unnecessary or might conflict with prettier
eslint-plugin-prettier runs prettier as eslint rule to get rid of the incompatibility between prettier and eslint
