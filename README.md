# SparkR

Provides an R interface to Apache Spark.

Compatibility updates by Renova.

Uses scalar class checks, writes Arrow IPC bytes through the supported API, and repairs three help pages.

SparkR uses Apache Spark 3.1.2 with Java 8 or 11. `install.spark()` can fetch this version from the Apache archive.

## Installation

```r
install.packages("SparkR", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Version `3.1.2.9002` is based on [CRAN 3.1.2](https://cran.r-project.org/package=SparkR).

## Credit

Shivaram Venkataraman [aut], Xiangrui Meng [aut], Felix Cheung [aut, cre], The Apache Software Foundation [aut, cph].

Licensed under `Apache License (== 2.0)`.
