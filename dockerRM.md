

### What is Docker? And Why? 

Docker is a container tecnology: A tool for creating and managing containers

Container:
- A standardized unit of software. A package of code and dependencies 
to run that code (e.g. NodeJS code + the NodeJS runtime).

- The same container always yields the exact same application and execition behavior!
No matter where or by whom it might be executed.

- Support for containers is built into modern operation systems!

- Docker simplifies the creation and management of such containers

### Why containers?

Why would we want independent, standardized "application pachages" ?

-   Different Development & Production Enviroments
We want to build and test in exacty the same enviroment as we later run our app in 

-   Different Development enviroments within a Team / Company 
Every team member should have the exacly same enviroment when working on the same project

-   Clashing Tools / Versions Between Different Projects
When switching between proct A should not clash with tools used in project B

### A Container ?
- Standardized unit for shipping goods
- Independent from other containers
- Can be moved with trucks, ships, cranes,...
- Self-containing

### Solution: Virtual Machines / Virtual Operating Systems
-   Wastes a lot of space on your hard divre and tends to be slow
-   Pro:
-   -   Separated environment
-   -   Environment-specifc configurations are possible
-   -   Enviroment configurations can be shared and reproduced reliably 
-   
-   Con
-   -   Redundant duplication, waste of space
-   -   Perfomance can be slow, boot times can be long
-   -   Reproducing on another computer server is possible but may still be tricky
-  

### Docker Helps You build & Manage Containers 

