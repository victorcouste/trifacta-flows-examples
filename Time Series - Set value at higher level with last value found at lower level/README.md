From a Time Series dataset with millisecond granularity, we want to set values at second level with the last value found at millisecond level.

1. Convert the unix time format in 2 readable datetime formats with seconds and milliseconds

2. By time at second level, create list of all values found at millisecond level

3. From the previous list, get the last value found

4. Group by time at second level with value found at previous step

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Custom%20Calendars/flow_Custom%20Calendars.zip)

- [Calendars recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Custom%20Calendars/my_calendars.wrangle)
