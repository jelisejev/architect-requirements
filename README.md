# Software Architect Position in C.T.Co

A manifest clarifying what is expected from a Software Architect in C.T.Co.

## Job Description

A Software Architect must be able to:
1. Analyse and understand business requirements of a project
1. Investigate different ways to address the business requirements of a project, identify their strengths and limitations.
1. Propose an architecture and techical stack suitable to implement the project, considering possible client's constraints
1. Propose a roadmap to implement the project
1. Investigate new and unfamiliar technologies and create quick proof of concepts
1. Present and explain the architecture to the relevant stakeholders, both technical and business-oriented
1. Assess the resources requirement to implement the project and set up a team
1. Contribute to development and, if necessary, develop a project on his own
1. Efficiently work with both existing and new clients

A Software architect is not required (although being able to is a bonus) to:
1. Have in-depth understanding of the business of the client: we expect the client to work with us and explain the most relevant and important aspects
2. Have deep understanding or experience with each and every technology out there: we have developers who can contribute their experience to clarity details
3. Contribute to the whole landscape of an organization: this is something we expect from Solution Architects.

## Required technical expertise

### **Architecture Design and Programming Paradigms**
1. Algorithms and Data Structures
1. Programming Paradigms (OOP, AOP, functional, imperative, declarative)
1. Design principles (e.g. Separation of concerns, Single responsibility principle, Principle of least knowledge, Evolutionary design)
1. Architecture documentation
    1. Diagraming notations (UML, Crow's Foot, etc.)
    1. Templates (e.g. arc42, architecture decision records)
    1. Visualization approaches (e.g. C4)
### **Application Development**

1. Backend, web frontend and, optionally, mobile development
    1. Popular languages and frameworks
    2. Performance (e.g. popular causes of bottlenecks and profiling methods)
    3. Security aspects (e.g. usual attack vectors and counter-measures)
    4. Debugging tools and techniques

1. Platform-specific questions
    1. Backend
        1. Layering/Componentization
        1. Multi-threading and concurrency
    1. Mobile
     	1. Cross-platform development (e.g. Xamarin, React Native, Ionic)
     	
1. Low-level Aspects of Architecture
   1. Peculiarities of operating systems
   1. Memory Management
   1. Inter-process communication
   1. Network Protocols (at least TCP/IP to HTTP(S))
   
### **Enterprise Architecture**
1. Architecture styles and types (client/server, layered architecture, service-oriented architecture, domain-driven design, event-driven architecture)
1. Application Integration Patterns
    1. Remote invocation (API&#39;s)
        1. Protocols (e.g. Rest, RPC, GraphQL)
        1. API design (e.g. api first, versioning)
    1. Messaging
        1. Queues and Topics
        1. Events
1. Non-Functional Aspects (Availability, Scalability, Reliability)
    1. High availability (e.g. eliminating single points of failure, redundancy)
    1. Scaling and load balancing
    1. Performance (e.g. requirements and metrics)
    1. Application resilience
    1. Business continuity
1. Security
    1. Authentication 
    2. Authorization (e.g. role-based, row-based security, column-based security)
    1. Popular protocols (e.g. Saml, oAuth,  OpenID Connect)
    1. Single sign-on
    1. Data encryption and key management

### **Data Access**

1. SQL
    1. RDBMS (e.g. Oracle, MS SQL, PostgreSQL, MySQL; practical experience with at least one of these)
    1. SQL (DML, DDL, Stored Procedures and specifics of mainstream DBs)
1. NoSQL 
    1. Types (e.g. document, graph, time-series, column, key-value)
    2. Popular DBMS
1. Comparing SQL and NoSQL databases (advantages and trade offs, areas of applicability)
1. Consistency models (e.g. ACID, BASE)
1. Data versioning approaches (e.g. patching, migrations)
1. Advanced questions:
    1. Big data processing (architectures, technologies, four Vs)
    1. Full text search/fuzzy search (DBMS-native and third-party technologies)
    1. GIS data processing and available technologies (DBMS-native and third-party)
    1. Partitioning and replication
    1. ETL ((concepts of data landing, staging, concepts of virtual DWH))
    1. Encryption

### **Software Development Process**
1. Project setup
    1. Epic/story breakdown
    1. Initial estimating
    1. Team setup: skills, roles, initial capacity
    1. Development methodologies (e.g. scrum, kanban)
1. CI/CD
    1. Test automation
    1. Code style
    1. Metrics (e.g. coverage, complexity, code analysis)
    1. Multi-stage environments
    1. Release management
    1. Zero downtime deployment
1. QA (validation, verification disciplines)
    1. Automatic  and manual testing
    1. Integration tests
    1. E2E tests
    1. Performance tests
    1. Visual regression tests
    1. Security testing (penetration, vulnerabilities)
    1. UAT
1. Engineering practices (e.g. unit testing, pull requests, code review, pair programming, VSC best practices)
1. Operations
    1. Monitoring
    1. Logging
    1. Alerting
    1. Distributed system monitoring and traceability
    1. Operation scenarios (i.e. what to do in case of a particular failure)

### **Operations, Tools and Frameworks**
1. Hosting types (on-premise, cloud or hybrid)
1. Virtualization:
    1. Virtualization types
    1. Software-defined networks
    1. Virtual Machines
    1. Containers
1. Cloud
    1. Automated Infrastructure setup
    1. Distributed system architecture patterns (retry, circuit breaker, idempotency)
    1. Abstraction levels
        1. IaaS
        1. PaaS
        1. SaaS
        1. CaaS
        1. Serverless (FaaS and BaaS)
1. Identity service providers (e.g. social logins, Azure Active Directory, Cognito, Cas, Okta etc.)
1. Monitoring solutions (e.g. Application insights, Elastic Stack, Prometheus)

### **Legal and Compliance**
1. International/government rules and legal issues that can affect applications&#39; architecture
2. Data protection (legal aspects of)
3. Types of software licenses and their impact on applications&#39; technology stack
