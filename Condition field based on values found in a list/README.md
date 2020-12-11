The use case of this flow is to filter rows based on a list of dynamic words found in 2 string columns.
If one of the word is found in one of the 2 columns and if another condition is met then we keep the row.

The dynamic list of words to look for can be found in the dataset **categories.txt**
And the list of words to look into will be extracted from 2 columns, name and site, from the **ites_Names.xlsx** dataset

The **"Categories list"** recipe will create the list of words to look for.
The **"Find values and created field"** recipe will extract words, compare with the categories list and do the filter.

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Custom%20Calendars/flow_Custom%20Calendars.zip)

- [Calendars recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Custom%20Calendars/my_calendars.wrangle)
