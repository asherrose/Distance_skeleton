# Distance_skeleton
Compute the distance transform (using 8-distance) of the input imageTthen, from the resulting distance transform to extract the skeletons of objects using 4-neighbor-local-maxima method.

I. Input: a binary image 
	  // Use argv[0]

II. Outputs: 

      You should have three output files: // Use argv[1], argv[2], and argv[3].

	- Use argv[1] to do:
  
		1) Create a distance transform image from the result of Pass-2 
			with *newRowVal and newColVal* image header for future processing.

	- Use argv[2] to do:
 
 		2) Create a skeleton image from the result of 4-neighbors-local-maxima computation 
			with *newRowVal and newColVal* image header for future processing.

	- Use argv[3] to do: 
 
		3) Pretty print the result of the Pass-1 of distance transform 
			with proper caption
	
		4) Pretty print the result of the Pass-2 of distance transform 
			with proper caption

		5) Pretty print the result of the skeleton 
			with proper caption
