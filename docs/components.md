An OMC component has the following attributes:
#### Organization
- Owner
- Team
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
	 - Green - no data errors, release *frequently*
	 - Amber - some data errors, few releases, development "not very active"
	 - Red - a lot of data errors, no d
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
eyJoaXN0b3J5IjpbLTEwNjE3MjYwNDQsMjEyOTkxMDM5MCwzMD
UyMDgwMTYsLTUwODE2NjMxMCwtMTE4NDg3MTgzMSwxNDM2MDUx
NDMzLDMwNTQ5NzE5MCwtMTIyNTM4MTcxLDgwMzgyOTE1OV19
-->