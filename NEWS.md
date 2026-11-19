# SparkR 3.1.2.9002

- Use the upstream Spark version for distribution downloads and JVM compatibility checks. Fall back to the Apache archive over HTTPS.

## SparkR 3.1.2.9001

- Uses scalar class checks, writes Arrow IPC bytes through the supported API, and repairs three help pages.
- Compatibility changes from CRAN 3.1.2 affect `R/DataFrame.R`, `R/SQLContext.R`, `R/WindowSpec.R`, `R/catalog.R`, `R/column.R`, `R/functions.R`, `R/group.R`, `R/mllib_classification.R`, `R/schema.R`, `R/serialize.R`, `R/utils.R`, `man/repartition.Rd`, `man/repartitionByRange.Rd`, `man/spark.kmeans.Rd`.
