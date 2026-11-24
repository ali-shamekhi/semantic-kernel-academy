
# Semantic Kernel Academy - Curriculum

Version: 1.0.0
Date: 2026-11-24
Total Phases: 6
Total Modules: 24
Total Lessons: 66
Primary Framework: .NET 10
Primary Language: C#

---

# Curriculum Overview

| Phase | Name | Modules | Days |
|---|---|---:|---:|
| 0 | Foundation | 2 | 6 |
| 1 | Core Fundamentals | 4 | 12 |
| 2 | Plugins & Function Calling | 4 | 12 |
| 3 | Memory & RAG | 4 | 12 |
| 4 | Agents & Workflow Orchestration | 5 | 12 |
| 5 | Production & Enterprise Architecture | 5 | 12 |
| Total | | 24 | 66 |

---

# Phase 0 - Foundation

Days: 1-6
Modules: 2

## Phase Objectives

- Understand AI and LLM fundamentals.
- Understand the architecture of LLM-based applications.
- Understand the role of Semantic Kernel.
- Prepare the .NET 10 development environment.
- Understand the relationship between AI SDKs and AI Models.

## Expected Phase Output

The student can explain the architecture of an AI application and describe where Semantic Kernel fits into it.

## Module 0.1 - AI and LLM Foundations

### Day 01 - Introduction to Artificial Intelligence

Prerequisites: None

Topics:
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning (DL)
- Generative AI
- Traditional Software vs AI Applications
- Deterministic vs Probabilistic Systems

Expected Output:
Understanding the main categories of AI and their differences.

### Day 02 - Understanding Large Language Models

Prerequisites: Day 01

Topics:
- Large Language Models (LLMs)
- Tokens and Tokenization
- Context Window
- Input Tokens and Output Tokens
- Parameters and Model Size
- Inference
- Model Training vs Model Inference

Expected Output:
Understanding how an LLM processes input and generates output.

### Day 03 - LLM Capabilities and Limitations

Prerequisites: Day 02

Topics:
- Next Token Prediction
- Temperature
- Hallucination
- Structured Output
- Context Limitations
- Model Knowledge vs External Knowledge
- Reasoning Limitations

Expected Output:
Ability to identify suitable and unsuitable LLM use cases.

## Module 0.2 - AI Application Architecture

### Day 04 - Architecture of LLM Applications

Prerequisites: Day 03

Topics:
- AI Application Architecture
- Model Provider
- AI SDK
- API Integration
- Prompt and Response Lifecycle
- Stateless vs Stateful AI Applications
- Client-Server Interaction

Expected Output:
Ability to draw a basic LLM application architecture.

### Day 05 - Introduction to Semantic Kernel

Prerequisites: Day 04

Topics:
- What is Semantic Kernel?
- Why Semantic Kernel Exists
- SDK vs Framework
- Kernel
- Plugins
- AI Services
- Function Calling
- Memory and Context
- Semantic Kernel Ecosystem

Expected Output:
Understanding Semantic Kernel responsibilities and boundaries.

### Day 06 - Development Environment and Architecture Preparation

Prerequisites: Day 05

Topics:
- .NET 10 Development Environment
- NuGet Package Management
- Semantic Kernel Package Structure
- Provider Selection
- API Keys and Secrets
- Configuration Management
- Official Documentation and Release Notes
- Initial Solution Architecture

Expected Output:
A prepared development environment and an approved technical baseline.

Phase Assessment:
Conceptual assessment covering Days 01-06.

---

# Phase 1 - Core Fundamentals

Days: 7-18
Modules: 4

## Phase Objectives

- Understand Kernel architecture.
- Configure Semantic Kernel in C#.
- Understand AI Service abstractions.
- Work with prompts and responses.
- Integrate Semantic Kernel into ASP.NET Core.

## Expected Phase Output

A working ASP.NET Core Chat Application integrated with Semantic Kernel.

## Module 1.1 - Kernel Architecture

### Day 07 - Kernel Architecture and Responsibilities

Prerequisites: Phase 0 completed

Topics:
- Kernel Architecture
- Kernel Responsibilities
- Kernel Components
- Service Resolution
- Execution Context
- Kernel as an Integration Point

Expected Output:
Understanding the internal responsibilities of Kernel.

### Day 08 - Kernel Builder and Configuration

Prerequisites: Day 07

Topics:
- Kernel Builder
- Kernel Configuration
- Registering AI Services
- Configuration Lifecycle
- Service Provider Integration
- Configuration Best Practices

Expected Output:
Ability to create and configure a Kernel instance.

### Day 09 - Kernel, Dependency Injection and Lifetimes

Prerequisites: Day 08

Topics:
- Kernel and Dependency Injection
- Service Registration
- Singleton, Scoped and Transient Considerations
- Service Resolution
- Kernel Reuse
- ASP.NET Core DI Integration

Expected Output:
A correct Kernel registration strategy for a web application.

## Module 1.2 - AI Services and Model Integration

### Day 10 - Chat Completion Architecture

Prerequisites: Day 09

Topics:
- Chat Completion
- Chat Completion Service
- AI Service Abstractions
- Provider Responsibilities
- Request and Response Flow
- Model Configuration

Expected Output:
Understanding the Chat Completion execution flow.

### Day 11 - Integrating an AI Provider

Prerequisites: Day 10

Topics:
- AI Provider Integration
- Provider-specific Connector Packages
- Authentication
- Model Selection
- Endpoint Configuration
- API Request Lifecycle
- Provider Portability

Expected Output:
A working connection between Semantic Kernel and an AI Provider.

### Day 12 - Chat History and Conversation Context

Prerequisites: Day 11

Topics:
- Chat History
- Conversation Context
- Message Roles
- System, User and Assistant Messages
- Conversation State
- Token Consumption
- Context Management

Expected Output:
Ability to maintain a multi-message conversation.

## Module 1.3 - Prompt Engineering

### Day 13 - Prompt Engineering Fundamentals

Prerequisites: Day 12

Topics:
- Prompt Structure
- System Instructions
- User Instructions
- Context Injection
- Few-shot Prompting
- Prompt Quality

Expected Output:
Ability to design structured prompts.

### Day 14 - Prompt Templates and Variables

Prerequisites: Day 13

Topics:
- Prompt Templates
- Template Variables
- Variable Substitution
- Template Configuration
- Prompt Reusability
- Template Execution

Expected Output:
Ability to create reusable prompts.

### Day 15 - Prompt Execution and Result Handling

Prerequisites: Day 14

Topics:
- Prompt Invocation
- Prompt Execution
- Result Handling
- Execution Settings
- Error Handling
- Output Validation
- Token Usage

Expected Output:
A reusable prompt execution component.

## Module 1.4 - ASP.NET Core Integration

### Day 16 - Semantic Kernel in ASP.NET Core

Prerequisites: Day 15

Topics:
- Web Application Architecture
- Kernel Registration
- AI Service Registration
- Application Services
- Controllers and Minimal APIs
- Configuration Separation

Expected Output:
Semantic Kernel integrated into an ASP.NET Core application.

### Day 17 - Building a Chat API

Prerequisites: Day 16

Topics:
- Chat API Design
- Request and Response Models
- Conversation Identifiers
- Application Service Layer
- Async Execution
- CancellationToken
- Error Responses

Expected Output:
A functional Chat API.

### Day 18 - Building the First AI Application

Prerequisites: Day 17

Topics:
- Application Integration
- Chat Workflow
- Conversation Management
- Configuration Validation
- End-to-End Testing
- Phase Review

Expected Output:
A complete basic ASP.NET Core Chat Application.

Phase Assessment:
Build and demonstrate an ASP.NET Core Chat Application.

---

# Phase 2 - Plugins & Function Calling

Days: 19-30
Modules: 4

## Phase Objectives

- Understand Semantic Kernel Plugins.
- Expose application capabilities to AI.
- Understand Function Calling.
- Implement controlled Tool Invocation.
- Integrate AI with real application services.

## Expected Phase Output

A Function-calling Assistant capable of invoking approved application functions.

## Module 2.1 - Plugin Architecture

### Day 19 - Plugin Architecture and Concepts

Prerequisites: Phase 1 completed

Topics:
- Plugin Architecture
- Why Plugins Exist
- Native Functions
- Semantic Functions
- Function Metadata
- Plugin Registration

Expected Output:
Understanding the Plugin execution model.

### Day 20 - Creating Native Plugins

Prerequisites: Day 19

Topics:
- Native Plugin Design
- C# Methods as Functions
- Function Metadata
- Method Parameters
- Return Values
- Function Discoverability

Expected Output:
A custom Native Plugin.

### Day 21 - Plugin Registration and Execution

Prerequisites: Day 20

Topics:
- Plugin Registration
- Kernel Integration
- Function Discovery
- Function Invocation
- Plugin Organization
- Execution Flow

Expected Output:
Ability to register and execute a custom Plugin.

## Module 2.2 - Semantic Functions

### Day 22 - Semantic Functions and Prompt-based Plugins

Prerequisites: Day 21

Topics:
- Semantic Functions
- Prompt-based Functions
- Function Definition
- Prompt Configuration
- Function Metadata
- Native vs Semantic Functions

Expected Output:
Understanding the difference between Native and Semantic Functions.

### Day 23 - Function Parameters and Outputs

Prerequisites: Day 22

Topics:
- Input Parameters
- Output Parameters
- Parameter Metadata
- Return Types
- Serialization
- Output Contracts

Expected Output:
Designing functions with predictable input and output contracts.

### Day 24 - Composing Functions

Prerequisites: Day 23

Topics:
- Function Composition
- Function Chaining
- Execution Dependencies
- Data Passing
- Composition Patterns
- Error Propagation

Expected Output:
A multi-function workflow.

## Module 2.3 - Function Calling

### Day 25 - Function Calling Fundamentals

Prerequisites: Day 24

Topics:
- Function Calling
- Tool Calling
- Model Tool Selection
- Function Metadata
- Model vs Application Responsibilities
- Function Invocation Lifecycle

Expected Output:
Understanding how an LLM selects an application function.

### Day 26 - Automatic Function Invocation

Prerequisites: Day 25

Topics:
- Automatic Function Invocation
- Function Choice Behavior
- Invocation Settings
- Execution Flow
- Multiple Tool Calls
- Automatic Invocation Risks

Expected Output:
A controlled automatic function-calling implementation.

### Day 27 - Manual Function Invocation and Approval

Prerequisites: Day 26

Topics:
- Manual Function Invocation
- Tool Call Inspection
- Invocation Control
- User Approval
- Human-in-the-loop
- Side-effect Protection

Expected Output:
A function-calling workflow with explicit execution approval.

## Module 2.4 - Application Integration and Security

### Day 28 - Integrating Business Services as Plugins

Prerequisites: Day 27

Topics:
- Application Service Integration
- Domain Service Boundaries
- Plugin Adapters
- Service Dependencies
- DTO Design
- Business Rule Protection

Expected Output:
Integration of existing application services through Plugins.

### Day 29 - Plugin Security and Validation

Prerequisites: Day 28

Topics:
- Input Validation
- Authorization
- Tool Permission Boundaries
- Sensitive Operations
- Prompt Injection Risks
- Function Execution Restrictions
- Audit Logging

Expected Output:
A secured Plugin execution design.

### Day 30 - Building a Function-calling Assistant

Prerequisites: Day 29

Topics:
- End-to-End Function Calling
- Plugin Composition
- Tool Selection
- Execution Approval
- Error Handling
- Integration Testing
- Phase Assessment

Expected Output:
A working Function-calling Assistant.

Phase Assessment:
Demonstrate an assistant that can invoke approved business functions safely.

---

# Phase 3 - Memory & RAG

Days: 31-42
Modules: 4

## Phase Objectives

- Understand Embeddings.
- Understand Vector Search.
- Design memory architecture.
- Implement document ingestion.
- Build Retrieval-Augmented Generation.

## Expected Phase Output

A Document-based RAG Application capable of answering questions using an external knowledge source.

## Module 3.1 - Embeddings and Vector Search

### Day 31 - Embeddings Fundamentals

Prerequisites: Phase 2 completed

Topics:
- Embeddings
- Vector Representation
- Semantic Similarity
- Embedding Models
- Vector Dimensions
- Semantic Search vs Keyword Search

Expected Output:
Understanding how text is converted into vectors.

### Day 32 - Similarity and Vector Search

Prerequisites: Day 31

Topics:
- Similarity Search
- Cosine Similarity
- Dot Product
- Euclidean Distance
- Top-K Search
- Metadata Filtering

Expected Output:
Understanding vector similarity and retrieval.

### Day 33 - Vector Database Architecture

Prerequisites: Day 32

Topics:
- Vector Database
- Collections
- Vector Records
- Indexing
- Metadata
- Vector Storage
- Database Selection Criteria

Expected Output:
Ability to design a basic vector storage architecture.

## Module 3.2 - Semantic Kernel Memory

### Day 34 - Semantic Kernel Memory Architecture

Prerequisites: Day 33

Topics:
- Memory Concepts
- Semantic Memory
- Short-term and Long-term Memory
- Memory Abstractions
- Vector Store Integration
- Memory Lifecycle

Expected Output:
Understanding memory-related architecture in Semantic Kernel.

### Day 35 - Vector Store Integration

Prerequisites: Day 34

Topics:
- Vector Store Abstractions
- Vector Store Connectors
- Record Definitions
- Embedding Generation
- Insert and Update
- Search and Retrieval

Expected Output:
A working vector store integration.

### Day 36 - Conversation and Persistent Memory

Prerequisites: Day 35

Topics:
- Conversation Memory
- Persistent Memory
- User Context
- Memory Retrieval
- Data Isolation
- Memory Expiration
- Memory Management

Expected Output:
A basic persistent memory strategy.

## Module 3.3 - RAG Architecture

### Day 37 - Introduction to RAG

Prerequisites: Day 36

Topics:
- Retrieval-Augmented Generation
- Why RAG Exists
- Knowledge Grounding
- Retrieval Pipeline
- Generation Pipeline
- RAG vs Fine-tuning

Expected Output:
Understanding the complete RAG architecture.

### Day 38 - Document Ingestion Pipeline

Prerequisites: Day 37

Topics:
- Document Loading
- Text Extraction
- Document Normalization
- Metadata Extraction
- Ingestion Pipeline
- Data Validation

Expected Output:
A document ingestion pipeline.

### Day 39 - Chunking and Embedding Pipeline

Prerequisites: Day 38

Topics:
- Text Chunking
- Chunk Size
- Chunk Overlap
- Semantic Chunking
- Embedding Generation
- Batch Processing
- Indexing Strategy

Expected Output:
An indexed document collection.

## Module 3.4 - RAG Implementation

### Day 40 - Retrieval Strategies

Prerequisites: Day 39

Topics:
- Vector Retrieval
- Keyword Retrieval
- Hybrid Search
- Metadata Filtering
- Top-K Selection
- Reranking Concepts
- Retrieval Evaluation

Expected Output:
A configurable retrieval strategy.

### Day 41 - Grounded Answer Generation

Prerequisites: Day 40

Topics:
- Context Construction
- Retrieved Content Injection
- Grounded Responses
- Source Attribution
- Citation Handling
- Hallucination Reduction
- No-answer Scenarios

Expected Output:
An answer-generation pipeline grounded in retrieved documents.

### Day 42 - Building a Document-based RAG Application

Prerequisites: Day 41

Topics:
- RAG End-to-End Architecture
- ASP.NET Core Integration
- Document Ingestion
- Vector Retrieval
- Answer Generation
- Testing and Evaluation
- Phase Assessment

Expected Output:
A complete Document-based RAG Application.

Phase Assessment:
Demonstrate a system that answers questions based on indexed documents and provides evidence for its answers.

---

# Phase 4 - Agents & Workflow Orchestration

Days: 43-54
Modules: 5

## Phase Objectives

- Understand Agent architecture.
- Understand the difference between Chat Completion and Agents.
- Understand Agent collaboration.
- Design multi-step workflows.
- Understand orchestration patterns.
- Distinguish Semantic Kernel Agent APIs from Microsoft Agent Framework.

## Expected Phase Output

A Multi-Agent System with defined responsibilities and controlled workflow execution.

## Module 4.1 - Agent Fundamentals

### Day 43 - Introduction to AI Agents

Prerequisites: Phase 3 completed

Topics:
- AI Agents
- Agent Architecture
- Agent vs Chatbot
- Agent Responsibilities
- Tools and Capabilities
- Autonomy and Control

Expected Output:
Understanding Agent-based application architecture.

### Day 44 - Semantic Kernel Agent Architecture

Prerequisites: Day 43

Topics:
- Semantic Kernel Agent Concepts
- Agent Abstractions
- Agent Instructions
- Agent Configuration
- Agent Execution
- Agent Services

Expected Output:
Understanding Agent architecture in Semantic Kernel.

## Module 4.2 - Agent Execution and Collaboration

### Day 45 - Agent Conversations and Threads

Prerequisites: Day 44

Topics:
- Agent Conversations
- Threads
- Conversation State
- Message Flow
- Agent Responses
- Context Management

Expected Output:
Understanding persistent Agent conversation state.

### Day 46 - Agent Tools and Function Integration

Prerequisites: Day 45

Topics:
- Agent Tools
- Plugin Integration
- Function Calling
- Tool Permissions
- Agent Execution
- Tool Result Processing

Expected Output:
An Agent that can use approved application tools.

## Module 4.3 - Multi-Agent Systems

### Day 47 - Multi-Agent Architecture

Prerequisites: Day 46

Topics:
- Multi-Agent Systems
- Agent Specialization
- Agent Responsibilities
- Agent Communication
- Coordination
- Shared Context

Expected Output:
A basic Multi-Agent architecture.

### Day 48 - Agent Collaboration Patterns

Prerequisites: Day 47

Topics:
- Sequential Collaboration
- Handoff
- Group Chat
- Coordinator Patterns
- Delegation
- Collaboration Risks

Expected Output:
Ability to select an appropriate Agent collaboration pattern.

## Module 4.4 - Workflow Orchestration

### Day 49 - Workflow Fundamentals

Prerequisites: Day 48

Topics:
- Workflow Architecture
- Steps and Activities
- State Transitions
- Workflow Execution
- Deterministic vs Agent-driven Workflows
- Failure Handling

Expected Output:
A basic workflow design.

### Day 50 - Orchestration Patterns

Prerequisites: Day 49

Topics:
- Sequential Orchestration
- Concurrent Execution
- Conditional Routing
- Fan-out and Fan-in
- Checkpoints
- Workflow Coordination

Expected Output:
Understanding workflow orchestration patterns.

## Module 4.5 - Agent Framework and Integration

### Day 51 - Semantic Kernel Process Framework

Prerequisites: Day 50

Topics:
- Process Framework
- Events
- Steps
- Process State
- Process Execution
- Workflow Coordination
- Framework Limitations and Version Status

Expected Output:
Understanding the Process Framework and its suitable use cases.

### Day 52 - Semantic Kernel vs Microsoft Agent Framework

Prerequisites: Day 51

Topics:
- Semantic Kernel Architecture
- Microsoft Agent Framework Architecture
- API and Namespace Differences
- Agent Execution Models
- Workflow Capabilities
- Migration Concepts
- Technology Selection

Expected Output:
Ability to distinguish the two technologies and make an architectural selection.

### Day 53 - Building a Multi-Agent Application

Prerequisites: Day 52

Topics:
- Agent Design
- Agent Responsibilities
- Communication
- Orchestration
- Tool Integration
- State Management
- End-to-End Execution

Expected Output:
A working Multi-Agent Application.

### Day 54 - Multi-Agent Assessment

Prerequisites: Day 53

Topics:
- Architecture Review
- Collaboration Testing
- Failure Scenarios
- Execution Control
- Workflow Validation
- Security Review
- Phase Assessment

Expected Output:
A documented and tested Multi-Agent System.

Phase Assessment:
Demonstrate a Multi-Agent workflow with explicit responsibilities and controlled execution.

---

# Phase 5 - Production & Enterprise Architecture

Days: 55-66
Modules: 5

## Phase Objectives

- Design production-grade AI applications.
- Understand security boundaries.
- Implement observability.
- Improve reliability and performance.
- Design testing and evaluation strategies.
- Prepare an enterprise deployment architecture.

## Expected Phase Output

A documented Production-ready AI Application architecture with implementation, testing, operational and deployment considerations.

## Module 5.1 - AI Application Architecture

### Day 55 - Enterprise AI Application Architecture

Prerequisites: Phase 4 completed

Topics:
- Enterprise AI Architecture
- Layered Architecture
- Clean Architecture
- Domain Boundaries
- AI Integration Layer
- Application Service Layer
- Infrastructure Boundaries

Expected Output:
A maintainable enterprise AI architecture.

### Day 56 - Semantic Kernel Integration Patterns

Prerequisites: Day 55

Topics:
- Kernel Integration Patterns
- Provider Abstraction
- Plugin Boundaries
- Application Services
- Configuration Strategy
- Modular Design
- Dependency Management

Expected Output:
A modular integration architecture.

## Module 5.2 - Security and Governance

### Day 57 - AI Application Security

Prerequisites: Day 56

Topics:
- AI Security
- Prompt Injection
- Data Leakage
- Sensitive Information
- Tool Security
- Input Validation
- Output Validation

Expected Output:
A documented AI security threat model.

### Day 58 - Authorization and Governance

Prerequisites: Day 57

Topics:
- User Authorization
- Tool Authorization
- Permission Boundaries
- Tenant Isolation
- Data Governance
- Human Approval
- Auditability

Expected Output:
A secure authorization and governance strategy.

## Module 5.3 - Observability and Reliability

### Day 59 - Observability and Telemetry

Prerequisites: Day 58

Topics:
- Observability
- Structured Logging
- Metrics
- Distributed Tracing
- OpenTelemetry
- AI Request Tracking
- Correlation IDs
- Sensitive Data Redaction

Expected Output:
An observability design for AI applications.

### Day 60 - Reliability and Resilience

Prerequisites: Day 59

Topics:
- Timeout
- Retry
- Circuit Breaker
- Rate Limiting
- Cancellation
- Fallback
- Provider Failover
- Transient Failure Handling

Expected Output:
A resilient AI integration strategy.

## Module 5.4 - Testing and Performance

### Day 61 - Testing AI Applications

Prerequisites: Day 60

Topics:
- Unit Testing
- Integration Testing
- Mocking AI Services
- Deterministic Testing
- Test Data
- Plugin Testing
- Workflow Testing

Expected Output:
A testing strategy for AI applications.

### Day 62 - AI Evaluation and Quality

Prerequisites: Day 61

Topics:
- AI Evaluation
- Answer Quality
- Groundedness
- Relevance
- Retrieval Quality
- Regression Evaluation
- Evaluation Datasets

Expected Output:
A measurable AI quality evaluation strategy.

### Day 63 - Performance and Cost Optimization

Prerequisites: Day 62

Topics:
- Token Optimization
- Context Optimization
- Caching
- Batching
- Streaming
- Model Selection
- Latency
- Cost Monitoring

Expected Output:
A performance and cost optimization plan.

## Module 5.5 - Deployment and Capstone

### Day 64 - Deployment and Operations

Prerequisites: Day 63

Topics:
- Production Deployment
- Environment Configuration
- Secrets Management
- Health Checks
- Background Processing
- Database and Vector Store Operations
- Version Management
- Rollback Strategy

Expected Output:
A production deployment plan.

### Day 65 - Enterprise Capstone Architecture

Prerequisites: Day 64

Topics:
- End-to-End Architecture
- Architecture Decision Records
- Component Boundaries
- Security Design
- Data Flow
- Observability
- Deployment Architecture
- Operational Readiness

Expected Output:
A complete enterprise AI architecture document.

### Day 66 - Final Assessment and Capstone Review

Prerequisites: Day 65

Topics:
- Architecture Presentation
- Implementation Review
- Testing Review
- Security Review
- Performance Review
- Production Readiness
- Final Assessment

Expected Output:
A reviewed and documented production-grade AI application.

Phase Assessment:
Final architecture and implementation review.

---

# Global Prerequisite Rules

1. Phase 0 has no technical prerequisite.
2. Each subsequent lesson requires the preceding lesson to be completed or explicitly approved as satisfied.
3. A phase assessment must be evaluated before the next phase begins.
4. Missing exercises must be recorded in LEARNING-PROGRESS.md.
5. No lesson is automatically marked Completed.
6. A failed assessment requires remediation before progression.
7. API changes and Package versions must be verified before generating implementation examples.

# Lesson Documentation Convention

Each daily document follows the structure defined in README.md.

Suggested filenames:

day-01-introduction-to-artificial-intelligence.md
day-02-understanding-large-language-models.md
...
day-66-final-assessment-and-capstone-review.md

# Course Completion Criteria

The course is completed when:

- All 66 lessons have been completed.
- All mandatory exercises have been evaluated.
- All six phase assessments have passed.
- The final capstone has been reviewed.
- Production architecture documentation has been delivered.

End of Curriculum.
