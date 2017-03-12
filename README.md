# Monty Hall problem using a cluster

## Introduction
This is a clustered version of my [Monty-Hall](https://github.com/skabbi/Monty-Hall) reposotory.

## Usage
This is a simple CLI program, written in node.js, that using a cluster calculates the likelihood of winning a car by always choosing to switch doors.

```sh
$ node montyHall.js [iterations] [number of CPUs]
```
Default number of iterations is 1000.
Default number of CPUs is the total amount of CPUs/cores installed.

#### Example result

```
$ node montyHall-cluster.js 1000000 5
Iterations      : 5000000
Percent of car  : 66.66 %
Percent of goat : 33.34 %
Execution time  : 825.181ms
```