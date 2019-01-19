# DCMSProject3
Web Service Implementation of the Distributed Class Management System (DCMS)

In this assignment, you are going to implement the Distributed Class Management System (DCMS) from Assignment #2 as a Web service. Specifically, design the service from Assignment #2 (using the same functions and exceptions) by doing the following:
1) Extract the Java client-server implementation by removing the CORBA specific code from your Assignment #2.
2) Properly annotate your Java implementation to adapt it as a Web service.
3) Build the end point files using the wsgen command before publishing the service.
4) Import the wsdl files using the wsimport command.
Your server design should maximize the concurrency in the application. In other words, use proper synchronization that allows multiple managers to createTRecord, createSRecord, getRecordCounts, editRecord, transferRecord for the same or different records at the same time.

[Java IDL (CORBA Implementation)](https://github.com/kdss91/DCMSProject2)

[Java RMI Implementation](https://github.com/kdss91/DSProject)
