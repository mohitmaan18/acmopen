Project Name : CPU Scheduler
How to Run this project ??
1. Install c++ compiler:
2. Check for Additional DEpendencies:The project uses standard C++ libraries like <bits/stdc++.h> which is used to include all standard libraries in competitive programming enviroments.
3. the project references a custom header file 'parser.h' .Ensure this file is in same directory.
4. Compile and run.
Internal Working of This Project :-
1.Header Files and Libraries :- Includes Standard libraries and a custom 'parser.h' for input parsing.
2.Global Constants and Variable :-constants like 'TRACE' and a list of scheduling algorithms.
Functions for sorting and comparison based on service time , arrival time ,response ratio and priority level.
3.Utility Functions :- Functions to clear the timeline ,get process attributies and calculate response ratio.
4. Scheduling Algorithms : Implementation of various algorithms such as -
   .First come First Serve
   .Round Robin
   .Shortest Process Next
   .Shortest Remaining Time
   .Highest Response Ratio Next
   .Feedback Queue
   .Aging
5.Execution and output :-
.'execute_algorithm' to run selected scheduling algorithm.
.'printTimeline' and 'printStats' to display timeline ans stats of process.
6. Main Function :-parses input , clears the timeline ,execute and prints the result based on operation mode .

Learnings:-
This Project is comprehensive understanding of CPU Scheduling .Enhancing both theoritical and practical knowledge in system programming and performance analysis.
