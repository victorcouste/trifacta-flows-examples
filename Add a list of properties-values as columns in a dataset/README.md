
If you need to add a list of properties / values in columns to an existing dataset, it can be done in 2 steps :

1. Pivot all properties in your Properties files so you have 1 row with values and properties name in column name

2. From your dataset, do a cross-join to add the properties columns to all rows

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Add%20a%20list%20of%20properties-values%20as%20columns%20in%20a%20dataset/flow_Add%20a%20list%20of%20propertiesvalues%20as%20columns%20in%20a%20dataset.zip)

- [Properties Pivot recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Add%20a%20list%20of%20properties-values%20as%20columns%20in%20a%20dataset/Pivot%20properties.wrangle)

- [Cross-join recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Add%20a%20list%20of%20properties-values%20as%20columns%20in%20a%20dataset/Add%20properties%20in%20columns.wrangle)



