# Making the zero-fidelity robust to SPAM errors
This is the accompanying code for the paper
'Making the zeroth-order process fidelity independent of state preparation and measurement errors'
Yu-Hao Chen, Renata Wong, Hi-Sheng Goan


In the file "Zeroth_order_process_fidelity", we show how SPAM errors affect zero-fidelity as zero-fidelity is not robust to SPAM errors. Here, we also show how zero-fidelity varies depending on different channels. The details are described in the paper.

Files "Two-qubit RB code" and "Three-qubit RB code" show how we make zero-fidelity independent of SPAM errors by combining it with randomized benchmarking. (Note: The code for 3 qubits has long running times. It requires HPC resources to generate the composed
circuits and calculate fidelities.)


In the file "Zero_fidelity_channel_noise_scaling", we use channel noise scaling to make the zero-fidelity robust SPAM errors. We simulated our results up to five-qubit (see the paper "Making the zeroth-order process fidelity independent of state preparation and measurement errors") by this code. (Note: The code for 5 qubits has long running times. It requires HPC resources to generate the composed
circuits and calculate fidelities.)
