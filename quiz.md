## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- The SOA is a method of software development that uses software components called services to
create business applications.
2. List and discuss the characteristics of SOA.
.It supports loose coupling everywhere in the project
.SOA supports interoperability
.It increases the quality of service
.It supports vendor diversity
.It promotes discovery and federation
.It is location-transparent
.It is still maturing and achievable idea
3.Define Microservices
- an architectural and organizational approach of software development
where software os composed of small independent services.
4. List and discuss the benefits of using Microservices.
.Improved productivity
-It is simpler to develop and maintain an application when it is divided up into smaller, independent pieces. Different programming languages, technologies, and software environments can be used by each service, depending on its requirements.
.Better resiliency
-Implementing microservice-based architecture adds ease to the process of  identifying and resolving the root cause of performance issues.
.Increased scalability
- every service can be written in a different language or technology, DevOps teams can select the best tech stack for every module without worrying about incompatibilities. 
 .Continuous delivery/continuous integration
-Continuous integration and continuous delivery are key concepts of both the DevOps philosophy and the agile approach. 
.Optimize business functionality
- It is simpler to adapt the requirements of each component to enhance business functionality when the focus is on a single service rather than the overall program.
5. List and discuss the similarities and differences of SOA and Microservices.
Architecture -SOA Designed to share resources across services then the Microservices is Designed to host services which can function independently.
Component sharing -SOA is frequently involves component sharing. then the Microservices Typically does not involve component sharing.
Granularity -SOA  Larger, more modular services then the Microservices is Fine-grained services.
Data storage -SOA Involves sharing data storage between services then the Microservices Each service can have an independent data storage.
6. Define Web Services.
- The web Services is a method of communication between two electonic devices over a network
7. List and discuss the benefits of using Web Services.
- IT Department Benefits of Using Web Services:
Improved efficiency by reducing time to integrate applications
The ability to develop new applications much faster than before
Cost savings through consolidation 
Integrate existing software modules into your own applications, making use of 3rd party expertise
Evolution - having the flexibility to move with the times rather than being restricted by an applications version release
 
8. List and discuss the characteristics of Web Services.
 .XML-based XML is used at the record transportation and information representation layers in web services. Networking, operating system, and platform binding are not required when using XML.
 .Coarse-grained Few items have a large amount of connected data in the coarse-grained operation. Compared to fine-grained service, it offers more capabilities.
 .Loosely Coupled Loosely connected connections between systems are supported via web services. Through a web API, it exchanges messages with each other in XML format.

9. List and discuss the distinct roles in Web Services Architecture.
Service Provider-From an architectural perspective, it is the platform that hosts the services.
Service Requestor-Service requestor is the application that is looking for and invoking or initiating an interaction with a service. 
Service Registry-Service requestors find service and obtain binding information for services during development.
10. List and discuss the Web Services Components.
-SOAP (Simple Object Acess Protocol)is XML based, so it is platform independent and language independent.
-UDDI is an XML based standard for describing, publishing and finding webservices.
-WSDL is a XML based language for describing webservices and how to access them.