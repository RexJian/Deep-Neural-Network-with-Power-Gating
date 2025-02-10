# Deep-Neural-Network-Power-Gating
This is a one-neuron network circuit, as shown in Figure 1. During the synthesis phase, I tried to use a memory IP to replace the flip-flop array to ensure that PrimeTime has no setup/hold violations. In this project, the multiplier block consumes a significant amount of power, so I decided to implement power gating for the block.

Before performing APR, I need to ensure that VCCV in Figure 2 maintains at least 97% of VCCR to prevent excessive IR drop, which could affect the circuit’s functionality. Additionally, I selected the power gating cell based on rise time and fall time. If the rise or fall time is too high, it may cause circuit errors.

After considering these factors, the power gating results are shown in Figure 3.
