The worker framework has the following commands:

  * `wsub`: submit a worker job
  * `wresume`: resubmit a worker job, however, only unfinished work items will be executed
  * `wconvert`: convert a Bash file to a work item file, each line is considred a work item
  * `wsummarize`: provide summary information on a (running) worker job, showing the number of completed or failed work items
  * `wload`: analyze the worker log file to diagnose load balancing issues
  * `wcat`: aggregate text output produced by work items
  * `wreduce`: aggregate any type of output generated by work items using a user-defined reductor