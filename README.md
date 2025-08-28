# microservice.golang
For many years, web applications were built as monolithic systems where a single codebase handled everything: authentication, logging, email, and more. While this approach is still common, larger and more complex applications today often adopt microservices. A microservice architecture structures an application as a collection of small, independent services that are loosely coupled. This approach makes applications more maintainable, scalable, and resilient, allowing teams to deploy and update services independently while focusing on specific business capabilities.

Typical characteristics of microservices include being maintainable, testable, loosely coupled, independently deployable, business-focused, and often managed by small, autonomous teams.

In this course, we will build several microservices in Go (Golang), a language well suited for distributed applications. Our services will communicate through REST APIs, gRPC, RPC, and AMQP (RabbitMQ). The system will include:

A Front End service for rendering web pages.

An Authentication service using PostgreSQL.

A Logging service with MongoDB.

A Listener service to consume RabbitMQ messages.

A Broker service as an optional single entry point.

A Mail service that converts JSON payloads into formatted emails.

Beyond coding, we will learn to deploy our distributed system with Docker Swarm and Kubernetes. These platforms make it possible to scale services up or down as needed, and to update individual services with minimal or no downtime—an essential capability in modern production environments.
