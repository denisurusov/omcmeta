An OMC component has the following attributes:
 - Git URL
 - BitBucket address
 - Owner
 - Team
 - State (should be derived from events)
	 - Active
	 - Do be killed
	 - Waiting to see what happens
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
	 - *this one needs a lot of thinking.  Must be done dynamically, at the very least*
 - Roadmap
	 - Feature and technology
	 - *should be sourced from Aha* 

The dashboard accepts events from life cycle, especially from ci/CD part of it

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQzNjA1MTQzMywzMDU0OTcxOTAsLTEyMj
UzODE3MSw4MDM4MjkxNTldfQ==
-->