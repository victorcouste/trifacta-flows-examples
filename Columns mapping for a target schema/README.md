This flow shows how to automatically map input columns with a specific output schema, with different columns name and a specific order.
The **Columns_mapping.csv** dataset contains 2 columns with the mapping between the input columns and the output columns.
The **input_customers.csv** is the new input dataset with initial input columns.

In **Columns_mapping** recipe, a new column will be created to keep column order with pivot will have to be done.
In **Customers Output** recipe, data will have to be unpivot and join with Columns_mapping to map columns, and finally pivot to get back to the output schema.


Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Custom%20Calendars/flow_Custom%20Calendars.zip)

- [Calendars recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Custom%20Calendars/my_calendars.wrangle)
