# Some fomulas/notations

## Burst time
> Burst time is the total time taken by the process for its execution on the CPU.

## Arrival time
> Arrival time is the time when a process enters into the ready state and is ready for its execution.

## Exit time
> Exit time is the time when a process completes its execution and exit from the system.

## Response time
> Response time = Time at which the process gets the CPU for the first time - Arrival time

## Waiting time
> Waiting time is the total time spent by the process in the ready state waiting for CPU.
> Or: Waiting time = Turnaround time - Burst time

## Turnaround time
> Turnaround time is the total amount of time spent by the process from coming in the ready state for the first time to its completion.
> Turnaround time = Burst time + Waiting time 
> Or
> Turnaround time = Exit time - Arrival time

## Throughput
> Throughput is a way to find the efficiency of a CPU. It can be defined as the number of processes executed by the CPU in a given amount of time. For example, let's say, the process P1 takes 3 seconds for execution, P2 takes 5 seconds, and P3 takes 10 seconds. So, throughput, in this case, the throughput will be (3+5+10)/3 = 18/3 = 6 seconds.

## Effective memory access time(EMAT)
TLB is used to reduce effective memory access time as it is a high speed associative cache. 
> EMAT = h*(c+m) + (1-h)*(c+2m) 
where, h = hit ratio of TLB 
m = Memory access time 
c = TLB access time 