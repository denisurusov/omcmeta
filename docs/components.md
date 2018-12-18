An OMC component has the following attributes:
#### Organization
- Owner
- Team
#### CI/CD
- Git URL
 - BitBucket address
#### State & Status
 - State (should be derived from events)
	 - Active - development is being done
	 - Planned - we are thinking/designing 
	 - Do be killed - old stuff that must die
	 - Waiting to see what happens - something that's in production and used, but not clear whether it will get enough adoption rate/usage
#### Component manifesto
 - Name
 - What purpose does it serve
 - 	 - Feature and technology
	 - *should be sourced from Aha* 
 - Type
	 - BAU
	 - R&D
	 - Strategy
 - Dependencies
	 - Pointers to git repos of components this component depends on
	 - API Connect end points pushed to or pulled from?
	 - ***this one needs a lot of thinking.  Must be done dynamically, at the very least***
 - Roadmap


The dashboard accepts events from life cycle, especially from ci/CD part of it

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQxNjA0NDY4MiwtNTA4MTY2MzEwLC0xMT
g0ODcxODMxLDE0MzYwNTE0MzMsMzA1NDk3MTkwLC0xMjI1Mzgx
NzEsODAzODI5MTU5XX0=
-->