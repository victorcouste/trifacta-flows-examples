
If you need to add a list of properties with values in columns to an existing dataset, it can be done in 2 steps :

1/ Pivot all properties in your Properties files so you have 1 row with values and properties name in column name

2/ From your dataset, do a cross-join to add the properties columns to all rows

