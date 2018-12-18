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
eyJoaXN0b3J5IjpbMjEyOTkxMDM5MCwzMDUyMDgwMTYsLTUwOD
E2NjMxMCwtMTE4NDg3MTgzMSwxNDM2MDUxNDMzLDMwNTQ5NzE5
MCwtMTIyNTM4MTcxLDgwMzgyOTE1OV19
-->