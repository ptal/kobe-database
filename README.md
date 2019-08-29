# Benchmarking database

Benchmarking results obtained by the [kobe](https://github.com/ptal/kobe) tools suite for various problems.

A benchmark is performed on a data set with a specific solver configuration.
Each benchmark has two output files, for example:

```
database-ccipl/rcpsp/j30.sm/absolute-2d33cd7/Octagon-Max_min_LB.csv
database-ccipl/rcpsp/j30.sm/absolute-2d33cd7/Octagon-Max_min_LB.json
```

The CSV file contains the results of the benchmark, and the JSON file contains the configuration of the solver used to compute these results.
The JSON file can be fed to `kobe` in order to replicate this exact benchmark.

## Databases

A database is a set of benchmarks performed on a same machine.
The file `meta.json` contains information on the machine that was used to perform the benchmarks.

1. `database-ccipl`: Contains all the benchmarks performed on the server ["Centre de calcul intensif des Pays de la Loire" (CCIPL)](https://ccipl.univ-nantes.fr/).
2. `research`: Contains one database per published research paper.

## Add your benchmarks

We accept new benchmarking results performed by `kobe`, so feel free to send us a pull request.
