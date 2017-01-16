# flexgrid
An easy-to-use CSS grid system based on flexbox





# QUICK TEMPLATES EXAMPLES

### Simple row 

    <div class="row container">
      <div class="cell">CELL</div>
      <div class="cell">CELL</div>
      <div class="cell">CELL</div>
    </div>
    
### Simple row with wider cell
Other elements with `.cell` will expand to available width

    <div class="row container">
      <div class="cell">CELL</div>
      <div class="cell-6">CELL</div>
      <div class="cell">CELL</div>
    </div>

### Vertical fullscreen app template

    <div class="col grow">
      <div>HEADER</div>
      <div class="cell">CONTENT</div>
      <div>FOOTER</div>
    </div>

### Horizontal fullscreen app template
    
    <div class="row grow">
      <div class="cell-2">ASIDE 1</div>
      <div class="cell">CONTENT</div>
      <div class="cell-2">ASIDE 2</div>
    </div>   
    
### (Extras) Paddings classes

    <div class="col container">
      <div class="padd-head">CELL</div>
      <div class="padd">CELL</div>
      <div class="padd-foot">CELL</div>
    </div>
    
## Classes

`.col` creates a column wrapper  
`.row` creates a row wrapper  
`.cell` creates a cell that expands to available width  
`.cell-[1..12]` sets the cell width (8.333% * number)  
`.grow` enlarges element to fit available space  
`.container` set to `.col` or `.row` elements to make them page-centeres with a max-width of 1152px

## Extras

`img` are kept responsive using `max-width: 100%;`  
`.clear` a helper class to clear floats (if ever needed)  
`.padd[,-head,-foot]` padding classes (best used on cells)  

##Scrollbar classes:    
Those classes are useful if you want a layout's DIV to scroll it's content

    .noscroll { overflow:hidden; }
    .scroll-auto { overflow: auto; }
    .scroll-x {overflow-x: auto; overflow-y: hidden; }
    .scroll-y {overflow-x: hidden; overflow-y: auto; }

