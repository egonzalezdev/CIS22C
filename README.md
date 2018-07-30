# Lab 4

<!DOCTYPE html>

One of the main applications of priority queues is in operating systems for  
<br>scheduling jobs on a CPU. In this project you are to build a program that  
<br>schedules simulated CPU jobs. Your program should run in a loop, each  
<br>iterationof which corresponds to a time slice for the CPU. Each job is assigned a  
<br>priority, which is an integer between −20 (highest priority) and 19 (lowest  
<br>priority), inclusive. From among all jobs waiting to be processed in a time 
<br>slice, the CPU must work on a job with highest priority. In this simulation,  
<br>each job will also come with a length value, which is an integer between 1 and  
<br>100, inclusive, indicating the number of time slices that are needed to process  
<br>this job. For simplicity, you may assume jobs cannot be interrupted—once it is  
<br>scheduled on the CPU, a job runs for a number of time slices equal to its  
<br>length. Your simulator must output the name of the job running on the CPU in  
<br>each time slice and must process a sequence of commands, one per time slice,  
<br>each of which is of the form “add job name with length n and priority p” or  
<br>“no new job this slice”.
