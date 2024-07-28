# Written for my COMP 7500 Advanced Operating Systems class at Auburn University

## Description
The application uses multithreading to handle a common queue for job submission.
The command parser module handles most of the scheduling threads work including calling functions that build and run the benchmarks and menus.
The dispatching module handles running the processes and removing the job from the queue as well as sending job performance to the performance metrics for calculation.

The queue is sorted based on which policy is selected (sjf) (fcfs) (priority)

## Performance metrics used to evaluate the application
1.	Total jobs 
2.	Average turn around
3.	Average wait time
4.	Throughput 
The workload conditions are:
policy, job count, arrival rate, min cpu time, max cpu time
