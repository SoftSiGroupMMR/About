# SI Exam Project

**Created by:**  
*Magnus Albeck Klitmose - cph-mk525@cphbusiness.dk*  
*Mathias Baunsgaard Kristensen - cph-mk523@cphbusiness.dk*  
*Rasmus Lynge Jacobsen - cph-rj173@cphbusiness.dk*  

* * * 

## The Buisness Case
If a person wants to travel to a specific city they can use our webiste to find all flights and hotels and get country information about the city that they want to travel to.
Everything will be sent to them by email. 

[The frontend can be seen and tested here](http://134.209.254.220/)  
[The endpoint for our system can be found here](http://134.209.254.220:30800/)  

* * * 

## The System 
The system consists of several microservices integrated by the use of RabbitMQ as a queueing system. All services is deployed with Kubernetes(minikube) and are scalable.  

* * * 
## Repositories
Here you can find all the repositpories of our services ect. for this project. Most of them can also be found [in the root of this project](https://github.com/SoftSiGroupMMR).  
| | |
|:-------|:-------|
|[Frontend](https://github.com/SoftSiGroupMMR/frontend) | Frontend SPA written in Angular. |
|[Restfull webservice](https://github.com/SoftSiGroupMMR/restfull) | Restfull service that recieves request and creates routing slip. |  
|[Flight service](https://github.com/SoftSiGroupMMR/aggregator) | Flight Service that fetches dummy flight-data from [easyjetAPI](https://github.com/SoftSiGroupMMR/easyjetAPI) and [norwegianAPI](https://github.com/SoftSiGroupMMR/norwegianAPI)  |  
|[HOTEL SERVICE MISSING](https://github.com/SoftSiGroupMMR/)| MISSING: Hotel service that fetches data from monolithic system [(Large System Development project)](https://github.com/LargeSystemsDevelopment2020/Moonlodge-Backend) |  
|[Country-Data service](https://github.com/SoftSiGroupMMR/countryData)| Country-data service that fetches data from [GeoDB](http://geodb-cities-api.wirefreethought.com/) restfull service and from [SOAP-API's](https://documenter.getpostman.com/view/8854915/Szf26WHn?version=latest#33a2b225-11a6-48d3-a695-fb0989cc4971).|  
|[Email service](https://github.com/SoftSiGroupMMR/countryData)| Email service that sends email to customer using javax mail and gmail. |  
[Routing Slip dependency](https://github.com/SoftSiGroupMMR/RoutingSlip)| The dependency that other java projects can use to administer the routing slip of the messages.  Dependency can be found [here](http://rasmuslynge.com:8081/#artifact/get.dk.si/routingslip). (can be opened in firefox)|
|[Logging service](https://github.com/SoftSiGroupMMR/LogDB)| Logging service that recieves logs from RabbitMQ and saves them in a MongoDB |  

