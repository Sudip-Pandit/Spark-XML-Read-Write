# Spark-XML-Read-Write
This repository gives the clear picture regarding spark-xml read and write.
# Write xml data

  val df = spark.write.format("com.databricks.spark.xml").option("rowtag", "data").mode("overwrite").save("file:///C:data/xml_write_spark")
