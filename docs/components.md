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
 - **Type**
	 - BAU
	 - R&D
	 - Strategy
	 - Enabler
 - **Dependencies**
	 - Pointers to git repos of components this component depends on
	 - API Connect end points pushed to or pulled from?
	 - ***this one needs a lot of thinking.  Must be done dynamically, at the very least***
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjE0NjU0Mzg2MiwyMTI5OTEwMzkwLDMwNT
IwODAxNiwtNTA4MTY2MzEwLC0xMTg0ODcxODMxLDE0MzYwNTE0
MzMsMzA1NDk3MTkwLC0xMjI1MzgxNzEsODAzODI5MTU5XX0=
-->