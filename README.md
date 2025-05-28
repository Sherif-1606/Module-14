Start the program.
Define the function CalculateWaitingTime(at, bt, N).
Initialize a list wt of size N with all values set to 0.
Set wt[0] = 0 for the first process.
Print the table header: "P.No.", "Arrival Time", "Burst Time", "Waiting Time".
Print the values for the first process.
For each process from index 1 to N-1:
Calculate wt[i] = (at[i - 1] + bt[i - 1] + wt[i - 1]) - at[i].
Print the process number, arrival time, burst time, and waiting time.
Initialize total_waiting_time = 0.
Add up all waiting times.
Calculate average waiting time as average = total_waiting_time / N.
Print the average waiting time.
Get burst times as input from the user for 5 processes.
Call CalculateWaitingTime() with at, bt, and N.
End the program.
