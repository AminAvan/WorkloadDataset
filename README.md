# Workload dataset

This workload dataset currently consists of one-hundred overloaded workloads with different tasks.
Contact: Amin Avan, amin.avan@ontariotechu.net

## Description
Each workload has parameters including:

* `NumberOfTask`: shows How many tasks are in the workload. 
* WorkloadUtilization: shows how much is the utilization of the workload.
* Execution Time: shows the execution time of each task.
* Deadline: shows the deadline of each task.
* Time Period: shows the period of each task.

We assume that the "period" equals the "deadline".

## Format of dataset (example)
```
[10,1.25]
4,20,20
4,40,40
6,60,60
8,80,80
10,100,100
30,200,200
50,400,400
70,600,600
90,800,800
150,1000,1000
```
According to the example,
* There are ten tasks in the workload.
* The workload utilization is 1.25, which demonstrates that the workload is in an overloading situation.
* The first task has the following characteristics:
	* Execution time: 4
	* Deadline: 20
	* Period: 20
