## API
The Application Programming Interface (API) is responsible for transmitting data from one device to another by taking in a request and responding with the data requested.

### Advantage and Purpose of APIs

The advantage of using an API to communicate between the client and the server rather than sending a direct query to the databases is that it protects the database from potential security risks. It also allows developers to keep a similar syntax when requesting data from any type of database. [^dreanfactory2023understanding]
The purpose of an API is to provide the client, whether a mobile application, website or other software, the information to build their product.

Several APIs are available on the Internet with different sets of data pertinent for various purposes. For example, if making an application that gives information on the weather, an API for the weather would be used to gather the necessary information. The developer or client would send a request to the API server that would return a response including some data. Using APIs also helps construct flexible applications by allowing developers to add functionalities easily to an existing project.[^aws24what] Anyone can easily integrate APIs into their projects by searching for them online. However, they are mostly implemented by programmers since it is not meant to be used by the end-user.[^wiki24api]

### Types of APIs
There are several types of APIs available for developers depending on the needs of a project. Each type of API has its own architecture and data formats.
#### Representational State Transfer (REST or RESTful):
The architecture of the REST API relies on six constraints, a uniform interface, a client-server decoupling, statelessness, storing cache, a layered system architecture and code on demand.
This gives developers consistent data that are uniform and predictable, making it easier for them to understand and put the information requested to use. The data can be delivered in several kinds of formats such as JSON, HTML, SLT, Python, PHP and plain text.
This type of API is ideal for web and mobile applications as it allows flexibility in programming languages. It is also able to handle large numbers of users simultaneously.[^ibm24what]

#### Simple Object Access Protocol (SOAP):
SOAP API, in comparison to REST API, is more rigid in its structure and only returns data in an XML format. It is most used when building on outdated systems which already use the protocol. There are also advantages in using SOAP for its tighter security beneficial to internal applications. It is also a better option if the integrity of the data is important as it implements the Atomicity, Consistency, Isolation, and Durability (ACID) properties. It is more reliable at the cost of less flexibility.[^aws24soap]

#### GraphQL (Query Language):
GraphQL is a query language signifying that the developer can use queries to request specific data. The string is sent to the server for interpretation and responds to the request with a JSON. It was developed by Facebook[^meta15graphql] and is the most modern standard for APIs after REST. It allows developers to avoid over-fetching data and only collecting what they request.[^graphql24basics] The developer can specify the structure of the response it needs for certain tasks. Additionally, GraphQL can retrieve the required data with a single request which reduces redundant communication between the client and the server.

### APIs and Art
Some museums have incorporated new technologies in the recent decade by [digitalizing](../main/glossary.md#Digitization) their collections to provide wider accessibility. By openly sharing a database of their art collections online, anyone with Internet access can view the collections through the museum's API. For example, the Metropolitan Museum of Art introduced the Metropolitan Museum of Art Met Collection API with an Open Access policy, allowing the distribution of their collection for the public domain. The data also includes relevant information on the history, artist and other details along with the works.[siegel18APIs] This reflects the integration of APIs in the art world and its impact on how we consume art. 

[^wiki24api]: Wikipedia. 2024. "API". Accessed January 29, 2024. https://en.wikipedia.org/wiki/API
[^aws24what]: 2024. "What is an API (Application Programming Interface)?" AWS. Accessed January 29, 2024. https://aws.amazon.com/what-is/api/.
[^dreanfactory2023understanding]: Nguyen, Spencer. 2023. "Understanding the Connection Between Databases and APIs." Accessed January 25, 2024. https://blog.dreamfactory.com/understanding-the-connection-between-databases-and-apis/#:~:text=APIs%20facilitate%20communication%20between%20applications,layer%20of%20protection%20to%20databases.
[^ibm24what]: 2024. "What Is a Rest Api?" IBM. Accessed February 26, 2024. https://www.ibm.com/topics/rest-apis. 
[^aws24soap]: 2024 "What is the Difference Between SOAP and REST?" AWS. Accessed February 26, 2024. https://aws.amazon.com/compare/the-difference-between-soap-rest/. 
[^graphql24basics]: 2024. "GraphQL is better than REST." How to GraphQL. Accessed February 26, 2024. https://www.howtographql.com/basics/1-graphql-is-the-better-rest/. 
[^meta15graphql]: Byron, Lee. 2015. "GraphQL: A data query language." Engineering at Meta. Accessed February 26, 2024. https://engineering.fb.com/2015/09/14/core-infra/graphql-a-data-query-language/
[siegel18APIs]: Siegel, Camille. 2018. "APIs and the art world: Working together for digital collaboration." Axway. https://blog.axway.com/product-insights/amplify-platform/application-integration/apis-art-world.