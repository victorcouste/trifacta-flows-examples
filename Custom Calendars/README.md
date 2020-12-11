
This single recipe flow is to generate a custom calendar dataset.

The flow contains 4 parameters that will be uses to generate calendar rows:
- The start date of the calendar : **initial_year, initial_month, initial_day**
- The number of rows or dates of the calendar : **nb_increments**

We need a fake input dataset that can be for example, a "select 1 as dummy" SQL query on any database.

Based on the start date and number of dates you want in your calendar, 
the recipe will generate 1 row per unit time (**month, week, day, hour or minute**). 


- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Custom%20Calendars/flow_Custom%20Calendars.zip)

- [Calendars recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Custom%20Calendars/my_calendars.wrangle)
