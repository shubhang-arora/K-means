**Authors** <br>
1. SHUBHANG ARORA [1410110399] <br>
2. ISHAN SINGH    [1410110613] <br>
3. SIDHARTH SINGH [1410110413] <br>

**NAME:** <br>
K-Means Clusstering

**DESCRIPTION** <br>
k-means clustering aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells.

**How To Run** <br>
Download the [jar File](http://repo1.maven.org/maven2/ca/pjer/ekmeans/), and run the demo by double-clicking the jar file or by running it in a terminal with

```bash
$ java -jar ekmeans.jar
```

The demo supports importing data from a CSV file. Each line terminated by a new line, must have at least two values (dimensions) separated by a comma. The first two values will be used, they must be parsable Java double.

Example:

```csv
1.52792,42.50525,MCDONALD'S (MCDRIVE),AD500 ANDORRA LA VELLA
3.9522,50.45396,MCDONALD'S,7000 MONS
4.00676,50.83615,MCDONALD'S (MCDRIVE),9400 NINOVE
```

You can view and download this example file.

The demo also supports exporting data to a CSV file. Lines in the exported CSV file will be in the same order as in the imported CSV file. Each line will be identical to the imported CSV file except for the first column, it will be the cluster index (so 0 means the first cluster).

Example:

```csv
2,1.52792,42.50525,MCDONALD'S (MCDRIVE),AD500 ANDORRA LA VELLA
0,3.9522,50.45396,MCDONALD'S,7000 MONS
0,4.00676,50.83615,MCDONALD'S (MCDRIVE),9400 NINOVE
```

**BUGS:** <br>
 If      you     find     a     bug,     please     report     it     at
       **https://github.com/shubhang-arora/K-means**


