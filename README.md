# Cloud Enable WPF LOB Apps

These are the sample apps I have been using in my Cloud Enable an Existing WPF LOB App talk at VSLive shows. There are six solutions total, each representing a step along the journey of taking an internal app and cloud enabling it. 

Expenses - 01 Existing App: This is the app at the beginning of the journey. Classic WPF talking to WCF talking to SQL Server. 

Expenses - 02 Data and Service in Azure: Next, we copy the data to Azure SQL and publish the WCF service to a Web App. Same client now talking to the service in the cloud which talks to the data in the cloud. No code changes required. Just run 2 wizards and make 2 config changes. 

Expenses - 03A After Securing Service: Next, we use Azure Active Directory to secure the WCF service. Run the app at this point and you are unauthorized. 

Expenses - 03B After Securing Service: Next, we add the ability for you to login so that you can call the WCF service. We now have a secure cloud enabled app. 

Expenses - 04 After Hybrid Connection: Here, we see how to leave the data in on-prems SQL Server and call it from the WCF service in the cloud.

Expenses - 05 After Service Bus: Finally, we see how to call an internal WCF service from the cloud hosted WCF service. 
