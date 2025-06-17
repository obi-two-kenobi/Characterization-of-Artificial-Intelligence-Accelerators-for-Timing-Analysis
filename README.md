# Characterization of Artificial Intelligence Accelerators for Timing Analysis 
Characterization of Artificial Intelligence Accelerators for Timing Analysis Master Thesis and Appendix.

## Directory Structure
The structure of the files and folders in this appendix is as follows: 
1. **main.pdf**: The actual master thesis as a pdf file, compiled from LaTeX. 
2. **Analysis.xlsx**: The Excel file that contains the full analysis of each kernel. Each kernel analysis is carried out in a separate sheet and is arranged as the following:
	- **Introductory example page**: Contains the analysis of the introductory example. Metrics of this kernel are collected in *Add kernel execution metrics.ncu-rep* and based on which the results were compared. 
	- **Vectorized element-wise**: Contains the analysis of the first Kernel of the AI model, with ID 0 in *AI model execution metrics.ncu-rep*.
	- **Matrix multiplication**: Contains the analysis of a matrix multiplication Kernel of the AI model, with ID 173 in *AI model execution metrics.ncu-rep*.
	- **Convolution**: Contains the analysis of a convolution Kernel of the AI model, with ID 17 in *AI model execution metrics.ncu-rep*.
	
3. **CUDA Occupancy Calculator.xls**: The occupancy calculator provided by Nvidia as a separate Excel sheet. Also available as part of Nvidia Nsight Compute.

4. **runAIModel.py**: Python script used to execute the used AI model, the script was used as a command inside Nvidia Nsight Compute.

5. **Nsight Compute Reports**:
	- **AI model execution metrics.ncu-rep**: AI model kernels report produced by Nvidia Nsight compute.
	- **Add kernel execution metrics.ncu-rep**: Introductory Example report produced by Nvidia Nsight compute. 

 
