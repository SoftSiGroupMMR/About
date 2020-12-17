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
Here you can find all the repositpories for our services ect. for this project. 
| | |
|:-------|:-------------------------------------------------|
|[Frontend](https://github.com/SoftSiGroupMMR/frontend) | Frontend SPA written in Angular. |
|[Restfull webservice](https://github.com/SoftSiGroupMMR/restfull) | Restfull service that recieves request and creates routing slip. |  
|[Flight service](https://github.com/SoftSiGroupMMR/aggregator) | Flight Service that fetches dummy flight-data from [easyjetAPI](https://github.com/SoftSiGroupMMR/easyjetAPI) and [norwegianAPI](https://github.com/SoftSiGroupMMR/norwegianAPI)  |  
|[HOTEL SERVICE MISSING](https://github.com/SoftSiGroupMMR/)| MISSING: Hotel service that fetches data from monolithic system [(Large System Development project)](https://github.com/LargeSystemsDevelopment2020/Moonlodge-Backend) |  
|[Country-Data service](https://github.com/SoftSiGroupMMR/countryData)| Country-data service that fetches city data from [GeoDB](http://geodb-cities-api.wirefreethought.com/) restfull service and country data from |  
|[Email service](https://github.com/SoftSiGroupMMR/countryData)| test |  
|[Logging service](https://github.com/SoftSiGroupMMR/LogDB)| test |  

