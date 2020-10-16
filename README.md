# Single Node Hadoop Experimentation
This project is part of a course on distributed computing using Hadoop. The examples contained here were run using AWS as a backend. Commands and processes were laid out by the professor, but the implementation and coding was left to us. Although this does not contain all the directions (as that content is course related and I do not feel comfortable sharing them here), it does contain as much as was able to be shared.

## Single Node
This was set up as a single node to stay within the free tier, but could certainly be expanded to multi-node. The machine was very small (single vCPU and 1GB of RAM) and as such only had so much power for calculation. This was purely experimental and for learning, so the sizing and scaling was not a big factor.

## Frameworks
Included in these examples are experiments with multiple frameworks built on the base set of Hadoop functionality, namely the HDFS file system. This includes experiments with Hive, Pig, Spark and StreamI/O.

## Main Dataset
The primary data for these analyses are based on an open source cars dataset (containing metadata for many car models), NYSE (New York Stock Exchange) for time-series, and a couple small corpora for other examples.