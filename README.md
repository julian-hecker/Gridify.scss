# Gridify.scss
Redefine what it means to be a grid.
- Powered by CSS Grid, the most powerful in CSS layout.


## Benefits
- Absolutely annihilate and exterminate tons of code from your markup.
    - With Gridify.scss, there is no need for bloating classes like `.row` or `.col-sm-8`.
- Run your own show with customizable grids.
    - Why is it always 12 columns? Gridify lets you specify the number of columns you want in your grid.
- Make responsive design a breeze.
    - Simply call the scss mixin from inside a media query and redefine what it means to be a grid.


## Usage
There are two main ways the project could be used.

### Recommended Usage
1. add the mixins file from `scss/_gridify-mixins.scss` into your project.
2. Include the `gridify()` mixin to define a grid container with the desired number of columns, gap sizes, and rows.
3. Place grid items inside grid using CSS `grid-template-areas` or `grid-column` / `grid-row` 
4. Compile along with the rest of your scss.
5. Profit from easy layouts!

### Other Usage (Not Recommended)
1. Copy the compiled `gridify-dist.css` file into your project
2. Use the pre-defined classes to define a grid container's properties.
3. Place grid items inside using CSS properties
4. Profit from easy layouts!


## What's included in Gridify.scss?
- Mixin to declare a grid container with adjustable columns, gap size, and rows.
- Mixins for testing CSS Grid Support and fallback code

## Demo / Testing
An [example codepen is available](https://codepen.io/what-the-heck-julian/pen/eYYYMZX) for trying out all the features.


## Requirements
- Some Knowledge of CSS Grid. [Check a great resource here](https://css-tricks.com/snippets/css/complete-guide-grid/).
- Does not support Internet Explorer until Edge 16+ ([caniuse](https://caniuse.com/#search=grid-template-areas)).


## Contributions
Please feel free to contribute to the project with suggestions, issues, bug reports, as well as pull requests!


## Special Thanks
- [Alex Tsirozidis](https://itnext.io/@alexfirebrand), who [wrote an article on ITNext](https://itnext.io/stop-using-bootstrap-create-a-practical-css-grid-template-for-your-component-based-ui-da784d974cc7) which inspired this project.


## Future Plans
- Draggable grid areas (Would require lots of JavaScript)
- Responsive grid classes.
