# CLASS 07 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 

## WHATS A TABLE ?
-A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

- Grids allow us to understand
  complex data by referencing
  information on two axes.

- Each block in the grid is referred
  to as a table cell. In HTML a
  table is written out row by row.

  ## Basic Table Structure

 ### <table>
- The <table> element is used
 to create a table. The contents
 of the table are written out row
 by row.
 tr
 
- You indicate the start of each
  row using the opening tr tag. 
 (The tr stands for table row.)
 It is followed by one or more
 a td elements (one for each cell
 in that row).
 At the end of the row you use a
 closing tr tag.
  atd
 Each cell of a table is
 represented using a td
 element. (The td stands for 
 table data.)
 At the end of each cell you use a
 closing td tag.

### Spanning Columns

- Sometimes you may need the
  entries in a table to stretch
 across more than one column.
 The colspan attribute can be
 used on a th or td element
 and indicates how many columns
 that cell should run across.
 In the example on the right
 you can see a timetable with
 five columns; the first column
 contains the heading for that
 row (the day), the remaining four
 represent one hour time slots.
 If you look at the table cell that
 contains the words 'Geography'
 you will see that the value of the
 colspan attribute is 2, which
 indicates that the cell should run
 across two columns. In the third
row, 'Gym' runs across three
columns.
You can see that the second
and third rows have fewer
 a td elements than there are
columns. This is because, when
a cell extends across more than
one column, the td or th
cells that would have been in the
place of the wider cells are not
included in the code.

### Long Tables

There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).
<thead>
The headings of the table should
sit inside the <thead> element.
<tbody>
The body should sit inside the
<tbody> element.
<tfoot>
The footer belongs inside the

<tfoot> element.

By default, browsers rarely treat
the content of these elements
any differently than other
elements however designers
often use CSS styles to change 
their appearance.

### THIS (IT IS A KEYWORD) 

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates. 

### RECAP: STORING DATA 

In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 


- [Previous](https://seidomo.github.io/201-reading-notes/class06) 
