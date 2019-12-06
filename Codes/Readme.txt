First compile measure_thresh with gcc without any optimzation flag
Run the ./a.out 
Inorder to run spectre attack without mitigation comment #define INTEL_MITIGATION
Then compile spectre.c and then run the ./a.out