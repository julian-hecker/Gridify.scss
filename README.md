# Gridify.SCSS
Easily create CSS Grids with reusable, modular code.

## Benefits
- Heavily reduce HTML markup
    - no need for `.row` or `.col-*` classes.
- Integrate smoothly with modular SCSS code
    - simply `@include gridify($columns, $gap-size);` in whichever container you want to be a grid.
- Change number of columns
    - Change optional arguments. Default values: $columns: 12, $gap-size: 1rem
- Easily make responsive layouts
    - just include the gridify mixin at different media queries.

## Requirements
- Knowledge of CSS Grid. [Check out some resources here](https://gridbyexample.com/resources/)

## Usage
1. Add the `gridify.scss` file to your project.
2. In SCSS, `@include gridify($columns, $gap-size);` where ever you'd like a grid.









## Features






## Demo / Testing
An [example codepen is available](Not yet actually, please wait for a bit!) trying out all the features.

## Special Thanks
- [Alex Tsirozidis](https://itnext.io/@alexfirebrand), who [wrote an article on ITNext](https://itnext.io/stop-using-bootstrap-create-a-practical-css-grid-template-for-your-component-based-ui-da784d974cc7) which inspired this project.