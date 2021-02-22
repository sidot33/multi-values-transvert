# multi-values-transvert
turn multi-values in tables to small parts


First, the data that in tsv form could be transformed to CSV.
Use database tool to import multi-value data.

open JDBCdemo, modify connection information and connect to database.
choose the table you want to split, and target table to contains single data.

It use parallal programming and JDBc transaction. The speed is about 1 billion rows/hour 



