### Overview
- OMC -  as a software **product** - consists of a number of **components**
- Components undergo a life cycle
- Life cycle is driven by actors
- Actors produce artifacts using tools

```mermaid
graph LR
    Product--consists of-->Components;
    Components--undergo -->LifeCycle;
    LifeCycle--is driven by-->Actors;
	Actors--produce-->Artifacts;
graph TD
	A-->B;	    
```
### Actors, tools and artifacts
|Actor|Tool|Artifact|URI
|--|--|--|--|
|Product owner| Aha.io |Feature|Feature number
|BA|Any editor supporting .md|User story|git URL
|Tester|Any editor supporting Cukes|Scenario

##### TODO

 1. Relationships between Aha Features and BA user stories
 2. Relationship between BA user stories and Testers Cuke Scenarios and Features
 3. Relationship between Tester Cukes and Development JIRA

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQzMTIwOTYyNiwtMTg4NTAzNDY5MiwxND
U0NzA4NzMxLC02NzkxNDYyNzAsMTgzMDM5MDQ1NSwtNDY2MzUx
ODQ5XX0=
-->