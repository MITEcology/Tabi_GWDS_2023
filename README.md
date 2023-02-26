This is the data and code in R associated with the manuscript: "Protection from harvesting promotes energetically efficient structures in marine communities"
by Andrea Tabi, Luis J Gilarranz, Spencer A Wood, Jennifer A Dunne, and Serguei Saavedra.
The folder is comprised of code and data folders to reproduce the figures and results.
The script “Simulation_Fig1.R” generates the data from simulations and creates Figure 1 and Figure S2. To generate Figure 3, first the script “RLS_comm_structure.R” has to be run, which outputs the result data file (data.RData) using reef fish data (all_data.csv) and covariates (Covariates.RData) . Then Figure 3 can be generated by “Fig3.R”. 
The script “Causal_inference.R” generates the results in Table 1, which sources the “pcalg.R” script. 
The “KS_tests.R” generates the test results in Table S2. 
