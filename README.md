# Names Exercise
In this exercise you'll create a simple table to display various human names with a calculated score. The requirements are as follows:

- Create a text input for entering names.
- Names can be submitted through a keypress or button click.
- Create an html table with columns for row number, name, & score. 
  -- This table should show any names added through the input in _alphabetical_ order. 
  -- The third column, score, should display a value calculated on the name.
     --- The score is defined as: the sum of each alphabetic value of the name multiplied by it's position in the provided list (found in `names.json`) once sorted in ascending order. 
     --- For example, the name COLIN is 938th in the list after being sorted. It has an alphabetic value of 3 + 15 + 12 + 9 + 14 = 53, thus the score would be 938 * 53 = 49714.
- Create a footer at the bottom of the table with a value that is the sum of the entire score column.
- Add the ability to remove any row in the list
- Lastly, create a button that bulk adds the provided list of names to the table. What is the total score for this list?

A boilerplate skeleton has been provided for you that includes AngularJS, lodash, and Bootstrap styles to get started, but feel free to use whatever libraries you feel comfortable with.

If you have any extra time feel free to add any extra features or improvements you would like.
