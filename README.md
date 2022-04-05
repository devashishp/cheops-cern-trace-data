# cheops-cern-trace-data

Data related to the CHEOPS'22 submission: ["Analysis and workload characterization of the CERN EOS storage system"](https://dl.acm.org/doi/abs/10.1145/3503646.3524293)

## Description of files:

| Filename(s)                                  | Description of file                                                                         |
| :---                                         | :---                                                                                        |
| Monthly_writes.csv                           | Total bytes written by month                                                                |
| access.csv                                   | FileID, number of accesses, and maximum observed file size for each file                    |
| aggstats.csv                                 | Aggregated statistics by application tagged in the trace, column name is self-descriptive   |
| appstats.csv                                 | Unrefined aggregated stats                                                                  |
| read_writes.csv                              | Writes, Reads, and actions on each day                                                      |
| file_sizes.csv                               | Maximum size of each file (188 million files)                                               |
| file_depths.csv                              | total volume occupied by files at various filesystem depths                                 |
| group.csv, group_reads.csv, group_writes.csv | Actions, Reads, and Writes by groupID                                                       |
| readmany.csv                                 | Number of reads observed by each file, including total data read and average read size      |
| users.csv, user_reads.csv, user_writes.csv   | Actions, reads, writes by each user                                                         |
| writeonce.csv                                | Number of writes observed by each file, including total data written and average write size |
