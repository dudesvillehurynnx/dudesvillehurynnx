# Hi, I'm Gilbert (Jojo)

**Technology Architect | .NET & Distributed Systems | Application Modernization | Microservices | Engineering Leadership**

I design, modernize, and build enterprise software systems with a strong focus on maintainability, scalability, engineering discipline, and long-term architectural evolution.

## About Me

I'm an Enterprise Technology Architect with 20+ years of software engineering experience spanning hands-on development, technical leadership, application modernization, and enterprise architecture.

My primary specialization is the Microsoft technology ecosystem, particularly C#, .NET, SQL, distributed systems, and enterprise application development.

Over the course of my career, I have worked across large-scale enterprise environments involving cloud and on-premises platforms, legacy modernization, distributed architectures, microservices, system integration, and multi-environment delivery ecosystems.

I enjoy designing systems from the ground up, establishing architectural foundations, defining engineering standards, and creating reusable frameworks and developer tooling that improve consistency, maintainability, and development productivity.

## Architecture & Engineering Focus

- Enterprise Application Architecture
- Distributed Systems
- Microservices Architecture
- Application Modernization
- Legacy System Transformation
- Domain-Driven Design
- CQRS
- SOLID Principles
- Dependency Injection
- API and Integration Architecture
- Architecture Governance
- Engineering Standards
- Developer Experience and Tooling
- Reusable Framework and Library Design
- Technical Leadership and Mentoring

## Core Technologies

### Languages & Platforms

- C#
- .NET
- SQL
- Windows Forms
- WPF
- ASP.NET / .NET Application Development

### Architecture

- Domain-Driven Design
- CQRS
- Microservices
- Distributed Systems
- Layered and Modular Architecture
- Event-Driven Architecture
- Dependency Injection
- Design Patterns
- SOLID

### Data & Integration

- Relational Databases
- SQL
- REST APIs
- Enterprise Integration
- Service-to-Service Communication
- Data Access Architecture

### Engineering

- Unit Testing
- Automated Testing
- Code Quality
- Static Analysis
- Roslyn Analyzers
- Coding Standards
- Continuous Integration
- Application Lifecycle Management
- Multi-Environment Deployment

## Engineering Philosophy

I believe good software architecture should make systems easier to understand, extend, test, operate, and evolve.

My engineering approach emphasizes:

- Clear separation of responsibilities
- Explicit architectural boundaries
- Maintainable and predictable code
- Strong domain modeling
- Testable business logic
- Reusable components and abstractions
- Consistent engineering standards
- Thoughtful use of design patterns
- Architecture that supports change rather than resists it

I prefer architecture that solves real problems without introducing unnecessary complexity.

## Selected Work

Most of my active development work is maintained in private repositories.

The projects below represent selected platforms, applications, frameworks, and engineering initiatives I have designed and developed. Source code remains private, while technical overviews and selected case studies may be published through this profile over time.

### DHV.Global.Toolkit

A comprehensive and modular .NET platform foundation designed to standardize reusable infrastructure and cross-cutting concerns across microservices, enterprise APIs, and Windows desktop applications.

The platform is composed of independently consumable toolkits with explicitly controlled dependencies, allowing applications to use only the capabilities they require while maintaining consistent architectural and engineering conventions.

Key capability areas include:

- Foundation and shared infrastructure
- Authentication and authorization
- Data protection and application security
- Structured logging and distributed tracing
- Metrics and health monitoring
- Request and response processing
- Resilience and fault-tolerance policies
- Caching and HTTP communication
- Data access and transactional coordination
- Search, matching, scoring, and discovery
- Globalization and localization
- Auditing and synchronization
- Background and out-of-band processing
- Release and feature lifecycle management
- Windows Forms infrastructure
- Custom reusable UI controls and visualization components
- Engineering standards and developer tooling

The architecture emphasizes modularity, testability, extensibility, security, performance, separation of concerns, and strict acyclic dependency management.

**Technologies:** C#, .NET 10, ASP.NET Core, Windows Forms, Entity Framework Core, SQL Server, Redis, OpenTelemetry, Serilog, Polly

**Repository:** Private

---

### BurnFlow

A software delivery planning and timeline estimation application designed to model the complete lifecycle of a software project from planning through production and hypercare.

BurnFlow calculates delivery schedules using project estimates, configurable phase allocation, working calendars, resource availability, holidays, leave, overtime, and delivery constraints.

Major delivery phases include:

- Planning
- Analysis
- Design
- Build
- Testing
- System Integration Testing
- User Acceptance Testing
- Deployment
- Hypercare

The application also supports milestone planning such as Pre-CAB, CAB, and Production dates while distinguishing working days from calendar days.

Its scheduling model is designed to produce predictable delivery projections while accounting for real-world resource and calendar constraints.

**Technologies:** C#, .NET, Windows Forms

**Repository:** Private

---

### OptiForge

An enterprise-grade material nesting and layout optimization application engineered to maximize material yield while reducing waste in sheet-based manufacturing scenarios.

OptiForge performs intelligent multi-sheet placement and evaluates alternative layouts to determine efficient material utilization.

Core capabilities include:

- Multi-sheet material nesting
- Intelligent piece placement
- Piece rotation
- Kerf and cutter-width consideration
- Material yield optimization
- Waste analysis
- Remnant and reusable offcut identification
- Layout utilization analytics
- Placed and unplaced piece reporting
- Optimization strategies and configurable parameters
- Visual nested-sheet rendering
- Detailed optimization statistics
- PDF and Word report generation

The optimization engine evaluates layouts according to material utilization, waste, sheet consumption, and placement quality while supporting deterministic reporting of optimization results.

**Technologies:** C#, .NET 10, Windows Forms

**Repository:** Private

---

### The Roman Genesis Global (TRG)

A purpose-driven technology initiative focused on designing and building digital solutions for churches, ministries, and faith-based communities.

The Roman Genesis Global combines modern software engineering with a mission-oriented approach to create web, mobile, and desktop systems that support church operations, ministry management, communication, community engagement, and long-term digital transformation.

The platform is designed around modular and independently maintainable services, allowing different areas of church and ministry operations to evolve without tightly coupling the entire ecosystem.

Its architecture is currently organized around two major microservice layers:

#### TRG.SLIP

**Service Layer Integrated Payload**

The core platform microservice layer responsible for domain-specific business logic, data processing, persistence, and integration.

SLIP contains independently focused services for areas such as:

- Accounts and users
- Authorization and access control
- Applications and forms
- Bookings and schedules
- Calendars and events
- Communications and notifications
- Communities and ministries
- Donations and financial activities
- Facilities and resources
- Files and documents
- Organizations and jurisdictions
- Registries and certificates
- Sacraments
- Services and requests
- Stores and orders
- Tenants
- Volunteers
- Reporting and operational data

Each service follows single-responsibility principles and owns a clearly defined application domain.

#### TRG.NOAH

**Neutral Overlay Aggregated Host**

An experience-oriented microservice layer positioned between SLIP and client-facing applications.

NOAH aggregates information from one or more SLIP services and exposes unified, client-friendly experiences without requiring web, mobile, or desktop applications to orchestrate multiple backend services directly.

Experience domains include:

- Activities
- Announcements
- Catalogues
- Certifications
- Checkouts
- Client management
- Contributions
- Dashboards
- Directories
- Discovery
- Engagement
- Formation
- Galleries
- Helpdesk
- Inquiries
- Institutions
- Offerings
- Profiles
- Publications
- Reservations
- Settings
- Worship

This separation allows the core domain services and the client experience layer to evolve independently while maintaining clear responsibilities across the platform.

#### Architecture & Engineering

Both SLIP and NOAH follow a consistent architectural foundation based on:

- Clean Architecture
- Domain-Driven Design
- CQRS
- SOLID principles
- Domain-focused microservices
- Dependency Injection
- Request validation pipelines
- API security
- Resilience policies
- Structured logging
- Request correlation
- Request deduplication
- Multi-environment deployment
- Independent service scalability and maintainability

Services are organized into four primary architectural layers:

- Host / Presentation
- Application
- Domain
- Infrastructure

The overall platform is designed to support secure, scalable, maintainable, and purpose-built digital solutions while keeping technology aligned with the operational and ministry needs of churches.

**Technologies:** C# 14, .NET 10, ASP.NET Core, MediatR, Dapper, Flurl.Http, AutoMapper, FluentValidation, Polly, Serilog

**Architecture:** Clean Architecture, DDD, CQRS, Microservices

**Repository:** Private

## Developer Tooling & Framework Design

A significant part of my personal engineering work focuses on building reusable tools rather than only end-user applications.

This includes:

- Custom UI component frameworks
- Application infrastructure
- Charting frameworks
- Validation components
- Developer utilities
- Roslyn analyzers
- Engineering conventions
- Testing infrastructure
- Reusable architectural patterns

I enjoy solving recurring engineering problems once and turning those solutions into reusable building blocks.

## Coding & Quality Practices

Some of the engineering practices I consistently apply include:

- Explicit and consistent coding conventions
- XML documentation for public APIs
- Automated unit testing
- High testability through dependency injection
- SOLID design
- Clear architectural boundaries
- Static code analysis
- Roslyn-based rule enforcement
- Deterministic tests
- Strong API design
- Consistent naming and structure
- Continuous refactoring and modernization

## Professional Experience

My professional experience spans more than two decades of software engineering across enterprise systems and large-scale transformation initiatives.

My work has evolved from hands-on software development into technical leadership and architecture, while remaining closely connected to implementation and engineering practices.

I continue to stay hands-on with software development because I believe architecture is strongest when architectural decisions remain grounded in how systems are actually built, tested, deployed, maintained, and evolved.

## Current Interests

I'm particularly interested in:

- Modern .NET architecture
- Distributed application design
- Domain-Driven Design
- CQRS
- Microservices
- Application modernization
- Framework engineering
- Developer tooling
- Windows desktop engineering
- Software quality and maintainability
- Architecture governance
- Engineering productivity

## About My GitHub

Most repositories associated with my active projects are intentionally kept private.

This GitHub profile serves as a technical portfolio where I document selected projects, architectural concepts, engineering practices, reusable frameworks, and software development work without exposing proprietary or private source code.

Public technical showcases and project case studies may be added over time.

## Connect

- [LinkedIn](https://www.linkedin.com/in/dudesville/)

---

> **Good architecture doesn't just solve today's problem. It creates room for tomorrow's opportunities.**