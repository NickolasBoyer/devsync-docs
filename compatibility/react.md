# React
Functionallity varies between projects, some do not generate correct sourcemaps for all the CSS. React projects often generate incorrect line numbers for CSS in JS.

## Next
By default, using `@zeit/next-css` or `@zeit/styled-jsx`, sourcemaps are not correctly generated.

## Gatsby
Fully working using CSS files (like `404.css`).

## Styled Components
Does not support sourcemaps yet, there is currently an [open pull request](https://github.com/styled-components/babel-plugin-styled-components/pull/180/) to add sourcemaps to styled components.