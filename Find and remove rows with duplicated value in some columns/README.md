
We want to delete rows where first name and last name are duplicated:

1. First, with a flat aggregation (count) we identify rows where first name and last name are the same

2. And with a row count generated for each couple (first name, last name) ordered by file row number, we identify which 
of the rows to keep.

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Find%20and%20remove%20rows%20with%20duplicated%20value%20in%20some%20columns/flow_Find%20and%20remove%20rows%20with%20duplicated%20value%20in%20some%20columns.zip)

- [Recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Replace%20missing%20by%20the%20most%20frequent%20value/replace%20missing.wrangle)
