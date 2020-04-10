
<b>WHAT IS MICROSERVICES?</b> &nbsp
Microservices are architectural design that structures different services. Earlier monolithic were used which works as a single unit. But it was not successful on the complex and larger applications, we will understand monolithic in detail later. Microservices are loosely coupled and distributed i.e. one change or error will not disturb the entire application. Developers are rapidly able to build new features to meet business need.

WHY MICROSERVICES?
Microservices are popular these days as many multinational companies like Twitter, Facebook, and Netflix has adopted this architecture. 
To understand the architecture of microservices we need to understand the structure and problems with our monolithic architecture.

WHAT IS MONOLITHIC ARCHITECTURE?
A monolithic application is said to be a self-contained means they are all composed in one piece. This architecture is like a container where all the components are assembled and tightly coupled where all components are fully dependent on each other unlike microservices.
Let’s understand with a scenario.
 
There is an application for client which includes customer services, product services and cost services, as they are all directly connected so if we want to make some changes in code or something else then we’ll have to make changes in all services as well. 

DISADVANTAGES OF MONOLITHIC ARCHITECTURE:
•	Large applications: It is difficult to maintain application because of large application as they are depend on each other. 
•	Complex applications: It is difficult to read applications because of its complex behavior. 
•	Unreliable: if one service performs down then it will affect all the other services as they are all connected to each other.
•	Inflexible: Becomes difficult to adopt new technology.
•	Unscalable: Each application will access the whole data which make more memory consumption as they are not independent.
•	Slow: instead of updates we need to modify whole application to redeploy which takes more time.

PROS OF MICROSERVICES: The main pro of Microservices is that the developer team can maintain and deploy application independently. Microservices also reduces your time and speed up your pipeline process. It is easy to understand as it is not complex like monolithic so a new developer becomes familiar easily. The developers can make new changes without breaking any architecture. Provides you flexibility. It can also be developed by small developing team.   

CONS OF MICROSERVICES:  Distributed deployment, process flows and partitioning the application into microservice can create complicated testing. The developers have to deal with the additional complexity of distributed systems. Increasing number in services can lead to information barriers.
