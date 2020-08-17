### Mohamad Faiz Ikhwani Hakimi Bin Md Fazli - 1712163
### Muhamad Danial Bin Mohamad Radzi - 1714492
### Wan Abdul Rashid Bin Wan Rahim - 1714181
### Hirzan Afiq Bin Kharuddin - 1713051




# Introduction

The first algorithm that we chose is Shortest Job First (SJF). It is the job or process scheduling algorithm that follows the non-preemptive scheduling discipline. This scheduler selects the process from waiting queue with the lease completion time and allocate the CPU to that job. SJF is more desirable because it reduces average waiting time.

The other algorithm that we chose is Priority Scheduling which means every process is associated with a priority ranging from 0-10 where 0 represents the lowest priority and 10 represents the highest priority. In non-preemptive priority scheduling, the scheduler will queue the new process at the head of the ready queue.

# Consideration

We take into consideration with the preemptive and non-preemptive case. In CPU scheduling, the algorithm can be preemptive but there is definitely no preemptive algorithm in class scheduling. This is because we cannot stop a class from running to allow another process to run.

So after some research, we find out that the algorithm that are suitable for this assignment are First Come First Serve, Shortest Job First and Priority Scheduling


# Analysis

## First Come First Serve (FCFS)

For FCFS, the average waiting time is 2.667 and the average turn around time is 4.667. 
Both average waiting time and turn around time for FCFS are the highest compare to SJF and Priority Scheduling.

## Shortest Job First (SJF)

For SJF, the average waiting time is 1.333 and the average turn around time is 3.333.
Both average waiting time and turn around time for FCFS are the lowest compare to FCFS and Priority Scheduling.


## Priority Scheduling 

For Priority Scheduling, the average waiting time is 2.333 and the average turn around time is 4.333. The order of the process gets executed is 3401, 2201, 1103.
Both average waiting time and turn around time for priority scheduling is higher than SJF but lower than FCFS.

