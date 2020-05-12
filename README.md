# SparkPersonsDetailsJoin
Example join with Spark : Persons details. Using Spark 2.3


Example for run example:

spark-submit \
  --class "com.ventur.join.SparkJoins" \
  --master local[*] \
 /tmp/spark/SparkJoin.jar /tmp/examples/spark/join/UserDetails.csv /tmp/examples/spark/join/AddressDetails.csv /tmp/examples/spark/join/ouput/
