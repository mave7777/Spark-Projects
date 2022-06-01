# Spark-Projects
This is the repo for the Adobe Spark project follow along with Sameer Farooqui in Youtube.

The original project in youtube was in Spark 2.0, currently I have executed this using a Databricks community cloud account running Spark 3.2.

Note:
#Add this line of code before the columns are cast with timestamp data:
spark.conf.set("spark.sql.legacy.timeParserPolicy","LEGACY")

Also, link to the original file in case S3 link doesn't work:

https://data.sfgov.org/Public-Safety/Fire-Department-Calls-for-Service/nuek-vuh3
