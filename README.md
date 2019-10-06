# Gridify.SCSS
Easily create CSS Grids with reusable, modular code.


## Benefits
- Heavily reduce HTML markup
    - no need for `.row` or `.col-*` classes.
- Integrate smoothly with modular SCSS code
    - simply `@include gridify($columns, $gap-size);` in whichever container you want to be a grid.
- Change number of columns
    - Change optional arguments. Default values: `$columns: 12, $gap-size: 1rem`
- Easily make responsive layouts
    - just include the gridify mixin at different media queries.


## Usage
1. Add the `gridify.scss` file to your project.
2. In SCSS, `@include gridify($columns, $gap-size);` where ever you'd like a grid.
3. (Optional) Assign template areas, either using the default syntax, 
    or the included `templateAreas` mixin.
4. Profit from making layouts easier!


## Demo / Testing
An [example codepen is available](Not yet actually, please wait for a bit!) trying out all the features.


## Requirements
- Some Knowledge of CSS Grid. [Check a great resource here](https://css-tricks.com/snippets/css/complete-guide-grid/).
- Does not support Internet Explorer until Edge 16+ ([caniuse](https://caniuse.com/#search=grid-template-areas)).


## Contributions
Please feel free to contribute to the project with suggestions, issues, bug reports, as well as pull requests!


## Special Thanks
- [Alex Tsirozidis](https://itnext.io/@alexfirebrand), who [wrote an article on ITNext](https://itnext.io/stop-using-bootstrap-create-a-practical-css-grid-template-for-your-component-based-ui-da784d974cc7) which inspired this project.
