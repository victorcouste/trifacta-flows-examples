Working with Excel files, you often get data in crosstab format, but you need to transpose it with 1 value per row for analytics tool.

Easy to do that in Trifacta with multiple steps:
1. Remove default structure found by Trifacta to get flexibility on column rename
2. Keep all default rows and columns split
3. Rename columns based on values from the 2 first rows
4. Unpivot all your columns containing values
5. Split the column containing initial categories merged

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Transpose%20Excel%20crosstab%20with%20multiple%20categories%20in%20rows%20and%20columns/flow_Transpose%20Excel%20crosstab%20with%20multiple%20categories%20in%20rows%20and%20columns.zip)

- [Data Transposed recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Transpose%20Excel%20crosstab%20with%20multiple%20categories%20in%20rows%20and%20columns/Data%20transposed.wrangle)
