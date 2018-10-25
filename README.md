### Merge requests pre requirements
Actually I was thinking about some rules that we may consider before submitting any merge requests. And there is a very good [repo](https://github.com/elsewhencode/project-guidelines) which is similar to what I want to create here, but we have some different rules, and I want to create this repo just as a sample so you may use some parts of it.
As we are using [React](https://github.com/facebook/react), [Material-ui](https://github.com/mui-org/material-ui), [JSS styles] (https://github.com/cssinjs/jss) these rules are related to these projects. We are also using [eslint](https://github.com/eslint/eslint) and [flow](https://github.com/facebook/flow).

### JavaScript
1. Avoiding console.log
2. Using `// @flow` on top of every file
3. Avoiding eslint errors
4. Each component file's name should start with an uppercase letter and the other files should start with a lowercase letter.
5. Each component file should have a component with the same name as the file inside it.
6. No hard-coded text in files, (should use resources files)
7. Avoiding formatting numbers or dates or any mathematical calculations using moment or any other library (should use the related util)

### JSS or CSS in JS
1. Avoiding inline styles in html parts.
2. Avoiding hard-coded numbers for width, height, padding, etc. (using theme object introduced by material-ui)
3. Avoiding hard-coded colors in styles (using theme object introduced by material-ui)
4. Avoiding float: left|right (use flexbox or grid instead)

### Git
1. Commit messages should be simple and start with module name and a description of what you did on that module e.g. (Customers: adding notifications on create and update)
2. Avoid using general commit messages like bug fix, improvement, refactoring etc.
