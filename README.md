# Virtual Store

**Virtual Store** is a microservices-based backend system designed to simulate an online store. It leverages multiple APIs for managing different aspects of an e-commerce platform, including cart services, product management, discounts, and identity authentication. Built using a microservices architecture, this project showcases the power and flexibility of dividing functionalities across independently deployable services.

## Features

- **Microservices Architecture**: Each service, such as cart management, product handling, and user authentication, is independently developed and deployed, ensuring scalability and modularity.
- **RESTful APIs**: Each microservice exposes a RESTful API, allowing interaction with the store’s backend services.
- **Discount Management**: Handles the application of discounts at checkout using a dedicated discount API.
- **Identity Management**: Securely manages user authentication and authorization through a dedicated identity server.
- **Seamless Integration**: The microservices work together cohesively to provide the backbone for a robust online store experience.
  
## Prerequisites

- **.NET Core SDK**: Ensure that you have .NET Core installed to build and run the solution.
- **Docker** (optional but recommended): For containerizing the services and managing their deployment.
