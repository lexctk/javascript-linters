# Javascript linter configuration

A reusable configuration for Javascript projects. Install one of the eslint configs, then prettier and if needed stylelint.

## Eslint

Install packages corresponding to your project, then copy the .eslintrc file to your project's root.

#### React

Install [airbnb's eslint config](https://www.npmjs.com/package/eslint-config-airbnb) and copy [eslintrc](react/.eslintrc)

```
npx install-peerdeps --dev eslint-config-airbnb
```

#### Node

Install [airbnb's base eslint config](https://www.npmjs.com/package/eslint-config-airbnb-base) and copy [eslintrc](node/.eslintrc)

```
npx install-peerdeps --dev eslint-config-airbnb-base
```

## Prettier

Install [prettier](https://github.com/prettier/prettier) and copy [prettierrc](.prettierrc) to your project's root.

```
npm install prettier eslint-config-prettier eslint-plugin-prettier --save-dev 
```

## Stylelint

Install [stylelint](https://github.com/stylelint/stylelint) with the [standard config](https://github.com/stylelint/stylelint-config-standard) and copy [stylelintrc](.stylelintrc) to your project's root

```
npm install stylelint stylelint-config-standard stylelint-scss --save-dev 

npm install stylelint-prettier stylelint-config-prettier --save-dev 
```

