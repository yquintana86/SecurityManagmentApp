Security Management Platform

A modern enterprise-grade security management platform designed for operational management, monitoring, and analytical reporting within a security services company.

This solution includes two client applications:

Angular 21+ for a modern dynamic web interface
Blazor for an additional .NET-based client experience

The backend is powered by ASP.NET Core Web API, following Clean Architecture, DDD, and CQRS principles to ensure scalability, maintainability, and clear separation of concerns.

🚀 Tech Stack
Frontend Clients
Angular Client
Angular 21+
Tailwind CSS
daisyUI
Modular component-based architecture
Responsive and modern UI
Blazor Client
Blazor
Bootstrap
Component-driven UI
Tight integration with .NET ecosystem
⚙ Backend
ASP.NET Core Web API
API Controllers
JWT Authentication & Authorization
CORS configuration
FluentValidation
MediatR
CQRS
Domain-Driven Design (DDD)
Clean Architecture
🗄 Data Layer
Transactional Database (OLTP)

Designed for operational business workflows:

Entity Framework Core
LINQ
SQL Server
Analytical Database (OLAP)

Designed for reporting and business intelligence:

Dapper
Optimized read queries
Aggregated analytical models
Data Integration
Dual SQL Server databases
ELT pipelines
Data synchronization between OLTP and OLAP environments

This enables high-performance transactional operations while supporting advanced reporting and analytics.

🧱 Architecture Principles

This project follows enterprise architectural patterns:

Clean Architecture
CQRS
DDD
Separation of read/write concerns
Independent domain layer
Scalable infrastructure layer

The goal is to simulate a real-world enterprise software solution.

🧪 Testing
NSubstitute for mocking
FluentAssertions for expressive unit tests
Unit testing focused on application and domain layers