An OMC component has the following attributes:
#### Organization
- Owner
- Team
- Dev Lead
- Lead BA
- Lead Tester
#### CI/CD
- Git URL
 - BitBucket address
#### State & Status
 - State *(should be derived from events*)
	 - Active - development is being done
	 - Planned - we are thinking/designing 
	 - Do be killed - old stuff that must die
	 - Waiting to see what happens - something that's in production and used, but not clear whether it will get enough adoption rate/usage
 - Status
	 - Green - no data errors, release *frequently* -> requires no action
	 - Amber - some data errors, few releases, development "not very active" -> requires corrective action
	 - Red - a lot of data errors, no active development work -> requires "keep or kill" decision
#### Component manifesto
 - Name
 - What purpose does it serve
 - 	Roadmap for Feature and technology
	 - *should be sourced from Aha* 
 - **Type** - Git URL
 - BitBucket address
 - Owner
 - Team
 - State
	 - Active
	 - Do be killed
	 - Waiting to see what happens
 - Purpose
	 - BAU
	 - R&D
	 - Strategy
	 - Enabler
 - **Dependencies**
	 - Pointers to git repos of components this component depends on
	 - API Connect end points pushed to or pulled from?
	 - ***this one needs a lot of thinking.  Must be done dynamically, at the very least***Dependencies 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM3MTU4OTk2NCwyMTQ2NTQzODYyLDIxMj
k5MTAzOTAsMzA1MjA4MDE2LC01MDgxNjYzMTAsLTExODQ4NzE4
MzEsMTQzNjA1MTQzMywzMDU0OTcxOTAsLTEyMjUzODE3MSw4MD
M4MjkxNTldfQ==
-->