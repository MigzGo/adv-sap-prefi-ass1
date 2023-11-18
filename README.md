## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
-Software development that permits the reusability of services is known as service-oriented architecture, or SOA. More applications of SOA include applications that require services from other active services, and these services will interact with one another to function as a team. A method known as "loose coupling" is used to remove dependencies between components in a system or network so that they can communicate with one another and handle business operations.

2. List and discuss the characteristics of SOA.
- •Standardized Service Contracts - takes guarantee that contracts in a service inventory are uniform and clearly state their capabilities and goals.

•Loose Coupling - Given the elimination of component dependencies, the client application shouldn't be severely impacted or crash as a result of a service functionality failure.

•Interoperability - As I understand this principle, it establishes guidelines for services, guarantees their usability for subscribers, and upholds interoperability for effective data exchange. It adheres to standards that let different clients or customers make use of the service.

•Abstraction - In here from what I understand, for the protection of the client, the customer, and the business, the workings of the service should remain hidden from the public. Allows for the introduction of agility, the breaking of dependencies, and the definition of technology within a business process.

•Autonomy - For runtime execution, services have extensive control over their underlying environment. Allows consumers the flexibility and control to make decisions without seeking approval or involvement.

•Discoverability - Services are added by leveraging communicative meta-information that can be found and translated successfully.

•Reusability - This is a method of reducing duplication and waste by utilizing current services whenever possible or developing new services that can serve many functions.

•Statelessness - Based on my understanding, the client application should be in charge of ensuring that data is not retained between states in this situation.

3. Define Microservices.
- Like SOA, microservices are used to develop separate applications in a way that improves robustness and scalability. It is made up of tiny, separate parts that, when put together, form larger applications that put services together and treat the whole thing as a whole.

4. List and discuss the benefits of using Microservices.
-•Improved productivity - When a program is separated into smaller, independent sections, it is easier to build and maintain.

•Increased scalability - Services can also be distributed over multiple servers, reducing the impact of more demanding components on performance.

•Right Tool for the Job - Microservices enable flexibility by allowing each service to use its own language and framework, which simplifies communication with the chosen application.

5. List and discuss the similarities and differences of SOA and Microservices.
-Similarities:

•Both emphasize the importance of checking for existing services before developing new ones, whereas microservices emphasize code reuse through copying and accepting data duplication.

•Communication - SOA relies on an ESB (Enterprise Service Bus) and can become a single point of failure, whereas microservices use independent communication protocols and simpler messaging methods such as APIs.

•Interoperability - SOA defines service standards, whereas microservices facilitate the sharing and usage of information across systems.

•Speed - Although SOA facilitates development and troubleshooting, it may be slower than microservices. Microservices enable the rapid deployment and testing of discrete application components without disrupting the overall program.
