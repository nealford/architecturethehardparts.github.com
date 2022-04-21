---
layout: default
---

# Software Architecture: The Hard Parts Workshops
The material across these workshops is the same; the level of detail and hands-on exercises differentiates them.

The material represents both the source and derivative of the book [{{ site.url }}](Software Architecture: The Hard Parts): the authors conducted workshops and training classes for several years, refining the material and the narrative, distilling the difficult problems facing modern architects. Because each software architecture is unique, generic advice doesn't help (which is why not many advanced software architecture books exist). However, every architect can benefit from learning how to perform trade-off analysis, which is what this material does, using common problems in microservices architectures.

## Three Days
Class which mixes exposition with visuals with team-based exercises.

### Outline

1. **What Happens When There Are No Best Practices?**
   - The Importance of Data in Architecture
   - Architecture Fitness Functions
   - Sysops Squad: architecture components
   - Sysops Squad: data model
2. **Discerning Coupling in Software Architecture**
   - Architecture Quantum
   - Static Coupling
   - Dynamic Coupling
3. **Architecture Modularity**
   - Modularity Drivers
   - Sysops Squad Saga: Creating a business case
4. **Architectural Decomposition**
   - Is the Codebase Decomposable?
   - Analysis metrics
   - Component-Based Decomposition 
   - Tactical Forking
5. **Component-Based Decomposition Patterns**
   - Identify and Size Components Pattern
   - Gather Common Domain Components Pattern
   - Flatten Components Pattern
   - Determine Component Dependencies Pattern 
   - Create Component Domains Pattern
   - Create Domain Services Pattern
6. **Pulling Apart Operational Data**
   - Data Decomposition Drivers 
   - Data Integrators
   - Data Decomposition 
   - Step 1: Analyze Database and Create Data Domains
   - Step 2: Assign Tables to Data Domains
   - Step 3: Separate Database Connections to Data Domains
   - Step 4: Move Schemas to Separate Database Servers
   - Step 5: Switch Over to Independent Database Servers
   - Selecting a Database Type
7. **Service Granularity**
   - Granularity Disintegrators
   - Granularity Integrators
8. **Reuse Patterns**
   - Code Replication
   - Shared Library
   - Shared Service
   - Sidecars and Service Mesh
9. **Data Ownership and Distributed Transactions**
	- Assigning Data Ownership
	- Common Ownership Scenario
	- Service Consolidation Technique
	- Distributed Transactions
	- Eventual Consistency Patterns
10. **Distributed Data Access**
	- Interservice Communication Pattern
	- Column Schema Replication Pattern
	- Replicated Caching Pattern
	- Data Domain Pattern
11. **Managing Distributed Workflows**
	- Orchestration Communication Style
	- Choreography Communication Style
	- Trade-Offs Between Orchestration and Choreography
12. **Transactional Sagas**
	- Primal forces in dynamic quantum coupling
	- Eight transaction saga patterns
13. **Contracts**
	- Strict Versus Loose Contracts
	- Stamp Coupling
14. **Managing Analytical Data**
	- Previous Approaches
	- The Data Warehouse
	- The Data Lake
	- The Data Mesh
	- Definition of Data Mesh
	- Data Product Quantum
	- Data Mesh, Coupling, and Architecture Quantum
	- When to Use Data Mesh
15. **Build Your Own Trade-Off Analysis**
	- Qualitative Versus Quantative Analysis
	- MECE Lists
	- The "Out-of-Context" Trap
	- Model Relevant Domain Cases
	- Prefer Bottom Line over Overwhelming Evidence
	- Avoiding Snake Oil and Evangelism

## Two Days


## One Day
