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
 - Dependencies (*this one needs a lot of thinking*)
	 - Pointers to git repos of components this component depends on
	 - API Connect end points pushed to or pulled from?
	 - 
 - Roadmap - feature and tech

The dashboard accepts events from life cycle, especially from ci/CD part of it

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg2OTY2NDQ3OCwzMDU0OTcxOTAsLTEyMj
UzODE3MSw4MDM4MjkxNTldfQ==
-->