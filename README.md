# Assembly Dimensions 

Calculates measurements on Assembly time. 

Description: 
----------------

Takes the command, evaluates with params, writes results to next column of the same row

Current restrictions 
--------------------------

Searches through A1 to A1000 only

Syntax: 
----------

	#! command param [param [param...]]

Commands: 
----------------

1. `distance from element-label-1 to element-label-2`

	returns: distance
  
	example: 

		#! distance from front to back

2. `doc-name the-regex-string`

	returns: the regex groups as is 

	example: 
	
		#! doc-name ^([0-9]+)x([0-9]+)-.*
