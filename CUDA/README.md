## Prerequisites

	For execution, CUDA

	For plotting,  perl, libstatistics-descriptive-perl, gnuplot

	Recommended GPU memory > 3GB

## Tests

	Global case,
 
		Under global/global_auto/

		./gpujob.sh
		./auto.sh

		Output file -> out.eps 		
		Figure 3: Simulation runtime with global movement

	Limited case,

		Under limited/limited_auto/

		./gpujob.sh
	        ./auto.sh

		Output file -> limited.eps 
		Figure 4: Simulation runtime with limited neighborhood.


## Results obtained using

	NVIDIA Tesla K20Xm with CUDA 7.5
