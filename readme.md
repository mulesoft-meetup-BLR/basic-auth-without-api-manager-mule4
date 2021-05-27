# Basic Auth without using API Manager in MULE 4

This example illustrates the Basic Authorisation using Spring

### Example Use Case
In this Example, we will create basic security filter (http) and authorisation filter (spring) for validating the request using username and password. The second flow is created to relate the use of API manager for the same use case.

### Set Up and Run the Example
1. Open the New project in Anypoint Studio from
2. Create the processes and try to call a separate REST request using it.
	- Using Spring Authorisation filter
	- Using API Manager
3. You will be able to get response in both the cases.

###Take away
We can use these Spring connectors and have basic auth requirement fullfilled without use of API Manager.