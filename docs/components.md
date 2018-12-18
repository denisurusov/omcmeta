An OMC component has the following attributes:
 - Git URL
 - BitBucket address
 - Owner
 - Team
 - State (should be derived from events)
	 - Active - development is being done
	 - Planned - we are thinking/designing 
	 - Do be killed - old stuff that must die
	 - Waiting to see what happens - something that's in production and used, but not clear whether it will get enough adoption rate/usage
 - Component manifesto
	 - Name
	 - What purpose does it serve
 - Type
	 - BAU
	 - R&D
	 - Strategy
 - Dependencies
	 - Pointers to git repos of components this component depends on
	 - API Connect end points pushed to or pulled from?
	 - ***this one needs a lot of thinking.  Must be done dynamically, at the very least***
 - Roadmap
	 - Feature and technology
	 - *should be sourced from Aha* 

The dashboard accepts events from life cycle, especially from ci/CD part of it

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUwODE2NjMxMCwtMTE4NDg3MTgzMSwxND
M2MDUxNDMzLDMwNTQ5NzE5MCwtMTIyNTM4MTcxLDgwMzgyOTE1
OV19
-->