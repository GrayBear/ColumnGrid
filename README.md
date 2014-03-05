ColumnGrid
==========

Responsive CSS only column grid.

Git Site with demo http://graybear.github.io/ColumnGrid/

##How to use

Apply the csss to the <head> tag in your document

    <link rel="stylesheet" href="column-grid.css">

Add the columns markup to your required part of your site. 

    <div class="columns">
      <div class="cell">
        <p>first</p>
      </div>
      <div class="cell">
        <p>second</p>
      </div>
      <div class="cell">
        <p>third</p>
      </div>
    </div>

This will create

On Large Screens

    -------------------------------------
    | first    | second     | third     |
    -------------------------------------
    
On Medium Screens

    --------------------------
    | first     | second     |
    --------------------------
    | second    |
    -------------
        
On Small Screens

    -------------
    | first     |
    -------------
    | second    |
    -------------
    | third     |
    -------------
    
##Customising 

The main customisable tags for the column grid are held in the .colums class (This is repeated for each of the @media queries).

Each of the column css tags currently requires vendor specific versions e.g. -webkit.


###Number of columns columns-count

This denotes the number of columns in the grid.

####Examples

One column

    .columns-count:1 
    
result

    -------------
    |           |
    -------------
    |           |
    -------------
    |           |
    -------------

One column

    .columns-count:2 
    
result

    -------------------------
    |           |           |
    -------------------------
    |           |           |
    -------------------------
    |           |           |
    -------------------------
    |           |
    -------------
  




