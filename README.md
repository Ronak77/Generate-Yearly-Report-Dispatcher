# Generate Yearly Report Dispatcher
An Robotic Process Automation(RPA) project used to generate yearly report for vendors using UIPath tool. Dispatcher Process will dispatch transaction items to Orchestrator Queue for processing by Performer Process.


## Description
This project is used to generate yearly report for a vendor by collecting monthly reports and uploading the final report and thereby updating the status by unique Id. Here Orchestrator Queue is used to process each and every transaction items by using multiple Robots. Two processes are used- Dispatcher and Perfomer. Dispatcher is used to dispatch transaction items to Orchestrator Queue and Performer is used to process the items generated in the previous step.

## Note
- Orchestrator Asset is used to store Credentials
- Orchestarator Queue is used to store transaction items
- Robotic Enterprise Framework is used(REFramework)
