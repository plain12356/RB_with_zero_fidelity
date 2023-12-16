# RB_with_zero_fidelity
This is the accompanying code for the paper
'Making the zeroth-order process fidelity independent of state preparation and measurement errors'
Yu-Hao Chen, Renata Wong, Hi-Sheng Goan

Note: The code for 3 qubits has long running times. It requires HPC resources to generate the composed
circuits and calculate fidelities. 




In the file "For_zero_fidelity", we show how SPAM errors affect zero-fidelity as zero-fidelity is not robust to SPAM errors. Here, we also show how zero-fidelity varies depending on different channels. The details are described in the paper.

Files "Two-qubit RB code" and "Three-qubit RB code" show how we make zero-fidelity independent of SPAM errors by combining it with randomized benchmarking.
