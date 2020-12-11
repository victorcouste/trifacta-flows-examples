From a Time Series dataset with millisecond granularity, we want to set values at second level with the last value found at millisecond level.

1. Convert the unix time format in 2 readable datetime formats with seconds and milliseconds

2. By time at second level, create list of all values found at millisecond level

3. From the previous list, get the last value found

4. Group by time at second level with value found at previous step

Resources:

- [Flow zip file to import in Trifacta or Dataprep](https://github.com/victorcouste/trifacta-flows-examples/raw/main/Time%20Series%20-%20Set%20value%20at%20higher%20level%20with%20last%20value%20found%20at%20lower%20level/flow_Time%20Series%20-%20Set%20value%20at%20higher%20level%20with%20last%20value%20found%20at%20lower%20level.zip)

- [Recipe](https://github.com/victorcouste/trifacta-flows-examples/blob/main/Time%20Series%20-%20Set%20value%20at%20higher%20level%20with%20last%20value%20found%20at%20lower%20level/Set%20value%20at%20second%20level.wrangle)
