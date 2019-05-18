# tabulator
use a library (tabulator)

First practice with using a libary. Starting off with an empty project.
Next step will be using this library to enhance one of my existing Github projects.

Step 1.
First attempt.
  -create a div in HTML where the Tabulator will be displayed in.
  -create data (an array of objects).
  -instantiate a Tabulator object, which defines the presentation and functionality of the table.

Step 2.
Fill the tabulator object with data from an external source (a JSON file)

1. Preparation: make a JSON file containing the tabledata contained in the HTML.
  - use JSON.stringify(tabledata) and output it to the console
  - copy and paste this output to a .json file.
  - remove the tabledata from the HTML file.

2. When the user clicks a button, retrieve the data from this .json file with the built-in setDataFromLocalFile() method of the tabulator object.