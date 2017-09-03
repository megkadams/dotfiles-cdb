# brooklyn united dotfiles

Here is a collection of project-oriented dotfiles, the purpose of which is to maintain code consistency across development at [Brooklyn United](http://brooklynunited.com). The following dotfiles are included:

## JavaScript
1.  `.babelrc` - Settings for Babel to compile by. ***required***
2. `.eslintrc` - JavaScript linting, extends [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb), and uses [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react), [eslint-plugin-babel](https://github.com/babel/eslint-plugin-babel), and [babel-eslint](https://github.com/babel/babel-eslint). ***required***
3. `.eslintignore` - Ignore certain parts of the project.
4. `.flowconfig` - Currently optional, but strongly recommended. Will be required at some point. [flow](http://flowtype.org) is a static typing system for JavaScript. There are many benefits for static typing, especially when maintaining a codebase over a long period of time is a concern. ***strongly recommended***

## System
1. `.editorconfig` - Enforces specific tabbing, spacing, and character encoding across files. ***required***
2. `.gitignore` - Files to ignore for git repos.
3. `.npmignore`  - Files to ignore for npm packages.
