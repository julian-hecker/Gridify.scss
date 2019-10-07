# Gridify.scss
Redefine what it means to be a grid.
- Powered by CSS Grid, the most powerful in CSS layout.



<!-- 
Next steps for this project:

Make actual rows capability
- @include gridify(columns, gap, rows);
- How to deal with row height? auto, by content?
- To make the templateAreas function, save the starting and ending positions of each grid-area.

Polish up the testing codepen

Documentations

 -->



## Benefits
- Absolutely annihilate and exterminate tons of code from your markup.
    - With Gridify.scss, there is no need for bloating classes like `.row` or `.col-sm-8`.
- Run your own show with customizable grids.
    - Why is it always 12 columns? Gridify lets you specify the number of columns you want in your grid.
- Make responsive design a breeze.
    - Simply call the scss mixin from inside a media query and redefine what it means to be a grid.


## Usage
1. Add the `gridify.scss` file to your project.
2. In SCSS, `@include gridify($columns, $gap-size);` where ever you'd like a grid.
3. (Optional) Assign template areas, either using the default syntax, 
    or the included `templateAreas` mixin.
4. Compile along with the rest of your SCSS.
5. Profit from making layouts easier!

## What's included in Gridify.scss?
- mixin for gridify with adjustable columns and gap sizes
- mixin for making a `grid-template-areas` declaration

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
- Explicit support for multi-row grids
- Draggable grid areas (Would require javaScript)
