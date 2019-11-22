# ML_Quantum_Circuits

## Objective

I have a QC based on 5 qubits. Each qubit has 2 states. Thus QC has 32 states in total. After each run, the QC will generate one state out of 32 states. After running the QC for 1024 times, we can have a histogram for how many times each state has been used.

My objective is to use machine learning to predict the histogram.

## Data

Each QC has up to 40 gates. <br/>
Each gate has following attributes: gate name, gate type, control, tartget, angle_1, angle_2 and angle_3.<br/>
We have 100K randomly generated QCs and their states histograms.

