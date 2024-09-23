# PhD

### GitHub repository for the simulation code and time series data referenced in my PhD thesis 

The **'Simulations'** folder contains the Julia code I used to simulate spinodal decomposition and dissolution (see comment on line ...). 
The code uses parallel processing where possible and calculates the powerspectrum of the microstructure at regular intervals. 
I ran the code on Stanage, the University of Sheffield's high performance computer. I used shell scripts to pass parameter values and implement repeat simulations on different nodes. 

The **'Data'** folder contains the time series of power spectrum snapshots I used to generate the synthetic structure factor snapshots from. 
Each text file contains 2001 powerspectrum snapshots (saved row-wise). The number of columns corresponds to the number of k-values, which depends on the spatial discretisation, dx, used in the simulations. 

Details regarding parameter values and the model on which the simulations are based can be found in my thesis and the references within (a link will be provided in due course). 

Please feel free to contact me if you have any questions.

Useful links:
- Stanage HPC documentation: https://docs.hpc.shef.ac.uk/en/latest/stanage/index.html#gsc.tab=0
- Sheffield RSE: https://rse.shef.ac.uk/
- Julia CUDA: https://cuda.juliagpu.org/stable/
- Julia performance tips: https://docs.julialang.org/en/v1/manual/performance-tips/
