# Dynamic Spreadsheet

## To run this project:

1) Extract the files
2) Symply open the file 'spreadsheet.html' on the browser of your preference


## Technologies used:

	1) HTML
	2) CSS
		2.1) Bootstrap
	3) Javascript
		3.1) Vue.js
		3.2) jQuery

## What do it do:

This spreadsheet should allow you to edit cells, add new columns with types, add more rows.
When the user opens the page, there's no spreadsheet showing. First, the user must create a column. When creating that column, the user should specify the column type and a column title. That column title should be shown on the header row of the spreadsheet.

Field types we should allow:

	-Date
	-Select (dropdown)
	-Text
	-Number

When the first column is created, we should initially populate the spreadsheet with 10 empty rows. To add additional rows, a user should be able to click a button “Add 10 rows” below the spreadsheet and 10 empty rows will be created.

There's one column to the left side that says the row number (indexing starts at 1). This column is not editable.
There should be one row at the top that contains the column titles. This row is editable.