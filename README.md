# SID
System Inventory &amp; Deployment

The idea of this project is to create a server/client application that writes windows client information back to a database for auditing purposes and also to deploy software to the clients (a SCCM type affair). Now the idea might not be feasible in practice or a very reliable way of doing so but I just wanted to see if it could be done by using the likes of Web Api and SignalR.

There will be 4 or more parts to the project, so far I am thinking a database to store all the data, a client to gather the information on the computer and return that data to the database and a central server that will push deployments to the clients. All of this will then be managed via a web frontend written in angularjs/angularjs2.
