bootstrap-n-column
=====================

LESS mixins for n-column Bootstrap 3 grids

Generate n-column grid layouts on top of Bootstrap's existing 12 column configuration. Easy upkeep as no modification of Bootstrap is required.

Includes support for offset, push & pull.

Just call `.col-set(n)` in LESS, then apply a `.col-n` style to your row.

e.g

### LESS
`.col-set(14);`

### HTML
```html
<div class="container">
	    <div class="row col-14">
	    	<div class="col-md-14">Whole row</div>
	        <div class="col-md-1">1</div>
	        <div class="col-md-1">2</div>
	        <div class="col-md-1">3</div>
	        <div class="col-md-1">4</div>
	        <div class="col-md-1">5</div>
	        <div class="col-md-1">6</div>
	        <div class="col-md-1">7</div>
	        <div class="col-md-1">8</div>
	        <div class="col-md-1">9</div>
	        <div class="col-md-1">10</div>
	        <div class="col-md-1">11</div>
	        <div class="col-md-1">12</div>
	        <div class="col-md-1">13</div>
	        <div class="col-md-1">14</div>            
	    </div>
</div>
```

Put this together as I couldn't find anything existing that didn't require Javascript or modifying Bootstrap itself. Here's hoping it will save someone else some time.

