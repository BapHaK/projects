# projects
My firsts projects
Data cleaning project
I found the first idea of project on Upwork.
One guy stored the problem as:
"Given the following table: On column "breadcrumb_0_merged" we have data of the following format: some text : url, 2nd text : 2nd url We want to remove 
all groups only inside the cell, if we have duplicates of "url". So there can only be 1 "group" of text : url wtih the same value of "url" inside the cell.
Note: this only applies at a cell level, NOT at a column level. We can have the same url on multiple columns.
This could be made as a function so we apply it in pandas."

I wrote the code which went through the each cell of one column of the data frame, looking for duplicates and removing it

