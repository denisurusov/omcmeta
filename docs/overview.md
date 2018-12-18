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

meta data fits into life cycle
Matt
BAs are a part of life cycle 
Testers
Coders
Release

dashboard monitors life cycle



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNzg4OTAxNTAsLTE4ODUwMzQ2OTIsMT
Q1NDcwODczMSwtNjc5MTQ2MjcwLDE4MzAzOTA0NTUsLTQ2NjM1
MTg0OV19
-->