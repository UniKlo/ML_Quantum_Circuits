# ML_Quantum_Circuits

## Objective

I have a QC based on 5 qubits. Each qubit has 2 states. Thus QC has 32 states in total. After each run, the QC will generate one state out of 32 states. After running the QC for 1024 times, we can have a histogram for how many times each state has been used.

My objective is to use machine learning to predict the histogram.

## Data

Each QC has up to 41 gates. Gates are activated one after another one in ascending sequence.<br/>

Each gate has the following attributes: gate name, gate type, control, target, angle_1, angle_2, and angle_3. The value in control and target mean the index of the qubit has this gate. '-1' means NULL.<br/>

I have 100K randomly generated QCs and their states histograms.

