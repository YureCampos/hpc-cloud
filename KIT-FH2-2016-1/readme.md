   --- SWF file converted from SQL database ---  
   
       Version: 2.2
	   
       Computer: ForHLR II
	  
       Conversion: Mehmet Soysal <Mehmet.Soysal@kit.edu> Aug 2019

  Installation: ForHLR II
  
   Acknowledge: Mehmet Soysal, Karlsruhe Institue of Technology / Steinbuch Centre for Computing
   
   Information: https://www.scc.kit.edu/dienste/forhlr2.php
  
       MaxJobs: 114355
       MaxRecords: 114355

 UnixStartTime: 1464739965

 TimeZoneString: Europe/Berlin
 
 StartTime: Wed Jun 01 02:12:45 CEST 2016
 
 EndTime:   Thu Jan 04 14:31:24 CET 2018
 
       MaxNodes: 1173
	   MaxProcs: 24048

 MaxQueues: 2
 
    Queues: Queue nb 1 is default queue. Queue nb 2 is visu queue. 
	
     Queue: 1 - Normal compute nodes - 1152 Nodes (each  20 core / 64gb RAM) , two islands with (816/336 nodes), 
		 jobs cannot spread islands. Always whole nodes where allocated.
		 
     Queue: 2 - Visualation Queue - 21 Nodes (each 48 core / 1Tb RAM / 4 GPU)  

 
 Note: 

	DISCLAMER:

	This log does not contain the full workload of the machine.
	For special campaings parts of the cluster where seprated, 
	the workload of these campaings are not part of this workload.
	Also some jobs are removed due to privacy concerns.
	Interactive jobs are not included in these workloads at all.
	
	As mentioned above the normal compute nodes have two island.
	Usually, a job will not spread over both islands, however for
	scaling tests and experiments, a few jobs where started across 
	both island. If there are jobs in the workload that are larger 
	then the big island - both island where used.