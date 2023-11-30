## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
-it aims to promote reusability and business agility.
2. List and discuss the characteristics of SOA.
2.1. Standardized service contract- it allows service to the consumers access and help to the service as well 
2.2. Loose coupling - An Enterprise can now treat each layer independently from the other. 
2.3. Abstraction - Abstraction allows the Enterprise to define technology in the context of a business process 
2.4 Reusability - Reusability creates a flywheel effect for innovation 
2.5 Autonomy - Users can then consume this service in a secure defined way in any compatible front end with no other needed dependencies 
2.6 Statelessness - You can cache data but that is a capability that the service can utilize as an option but will not depend on it 
2.7 Discoverability - To support reuse, a service must be able to be found by a consumer 
2.8 Composability - Enable your organization to combine packaged business capabilities to define business processes
3. Define Microservices - it is design for creating a distributed application using containers
4. List and discuss the benefits of using Microservices.
4.1. improved productivity - through detailing it makes easier to build and maintain 
4.2. Better resiliency - it adds ease to the process of identifying and resolving the root cause of performance issues 
4.3. Increased scalability - it allows DevOps teams to choose the most appropriate tech stack for each module without concerns about incompatibility. 
4.4. Continuous integration - it allows cross-functional teams to develop, test, problem-solve, deploy, and update services independently, which leads to faster deployment and troubleshooting turnaround times. 
4.5 Optimize business functionality - it’s easier to customize the needs of each component to improve business functionality.
5. List and discuss the similarities and differences of SOA and Microservices.
5.1 Communication - each service must share the same communcation mechanism called enterprise service bus. and each service is developed independently.
5.2 Interoperability - SOA has no upper limits and the microservice architecture style supports protocol aware heterogeneous interoperability.
5.3 Service granularity - SOA services are large and typically have a wider range of focus. the more granular nature of microservices means that individual service excel in performing a single specific task.
5.4 Speed - microservices are smaller and largely independent of one another, they are deployed much more quickly and easily than those in SOA.
6. Define Web Services - is a communication between two electronic devices over a networ.
7. List and discuss the benefits of using Web Services.
7.1 Exposing the existing function on the network - webs services allows exposing the functionality of existing code over the network. 
7.2 Interoperability - it allows various application to talk to each other and share data and service to each other.
7.3 Standarized Protocol - with all four layers, it used well defined protocols in the web services protocol stacks.
7.4 Low Cost Communication - it is much costly compare to proprietary solutions like EDI/B2B
8. List and discuss the characteristics of Web Services.
8.1 XML-Based - it elimates any networking,OS or platform binding
8.2 Loosely Coupled - a tightly coupled system implies that the client and server logic are closely tied to one another.
8.3 Coarse Grained - an individual method is to find an operation to provide any useful capability at a corporate level.
8.4 Ability to be Synchronous or Asynchronous - Synchronicity refers to the binding of the client to the execution of the service.
8.5 Support remote procedure calls - it allows clients to invoke procedures, functions and method on remote object using xml based protocol.
8.6 Support Document Exchange - it can be as simple as representing an entire book or request for quotation.
9. List and discuss the distinct roles in Web Services Architecture.
9.1 service provider - it provides the interface for the web service and the implementation of the application
9.2 service requester- it looks for and invokes or initiates an interaction with a service.
9.3 service registry - this is a logically centralized directory of services and The registry provides a central place where developers can publish new services or find existing ones.
10. List and discuss the Web Services Components.
10.1 Extensible Markup Language (XML) -  is used to describe data. The XML standard is a flexible way to create information formats and electronically share structured
10.2 Simple Object Access Protocol (SOAP)-  defines SOAP messages that are sent to web services and client applications.
10.3 Web Services Description Language (WSDL). it is an XML-based interface description language that is used for describing the functionality offered by a web service.
10.4 Universal Description, Discovery and Integration (UDDI) - it is an Extensible Language Markup (XML)-based standard to describe, publish and find information about web services.
10.5 Representational State Transfer (REST) - it is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each others.