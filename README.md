Using Basic Css-Grid 

## Css Grid
In this part of the code, The Grid-container is set display as a grid, with two columns using the **grid-template-columns** property set to auto twice..(Which means to repeat the the column twice each occupying maximum width of its container).
You can adjust the number of columns by modifying the **grid-template-columns** property in the css code

The grid items are styled with a background color of #7FFFD4, border of 1px solid blue, padding of 30px, and centered text using text-align: center. this will create a basic grid with 3 rows and 2 columns.

## Repeat
This code will create a grid container with six grid items. The grid container is set to display as a grid, with three columns using the grid-template-columns property set to **repeat(3, 1fr)** (which means to repeat the value 1fr three times).

The grid items are styled with a background color of #7FFFD4, border of 1px solid blue, padding of 30px, and centered text using text-align: center. This will create a basic grid with 2 rows and 3 columns.

## MinMax
In this example, the **minmax** function was used to define a minimum and maximum size for each column. In this case, the minimum size is set to 100px and the maximum size is set to auto(which means the row will take up as much available space as possible).

The grid-template-columns property was also use here to create two columns. it will create a basic grid with 3rows and 2columns

## Grid-gap
In this example, There is a grid container with two columns, a gap of 10 pixels between each column and 5px between each row. The grid-gap property can be used to set the gap between the rows and columns in the grid.
The first value on the grid-gap property specify the rows while the second value specify the column...

## Grid-area
For this part of the code, The **grid-area** property is used to position the element with the class "grid-item-1" in the "header" grid area, which spans from the start of the first row to the end of the third column. same goes for the the rest of the classes.

## Grid-span
This part works thesame as the grid-area. For the first element with the class "item-1", using the property and the value set to '**grid-row: span 2;**' it is set to span from the start of the first row to the end of the second row. same thing for the element with the class "item-3".

As for the element with the class 'item-5', the property used was 'grid-column' and the value 'span 2' which will set our element with the class "item-5" to start from the first column and to the end of second column i.e to span across 2 column.

## Alignment
In this example, there is a grid container with three columns, and I'm using justify-content: center to align the grid items to the center of the container. This means that the extra space in the container will be evenly distributed on either side of the grid items.

Then also using align-content: center to vertically center the grid items within the container.


 > Note: all grid-items have the same stylings
