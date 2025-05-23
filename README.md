# BCS-SecretaryTasks
This Repository contains 2 folders mainly aiming to solve BCS Secretary Task(IITK 2025)

1)First one include 1 Research Paper + Explanation + Jupyter noteboook pivoted around a ps which in short is:

A critical crisis unfolds on 12 May 2045, aboard the Synaptech Neuro-Lab stationed in orbit at Aegis-9. Dr. Z, a renowned cyber-neurologist at the forefront of brain-computer interface research, has fallen victim to a rogue neural parasite known as Corticon, which is hijacking his cortical microcircuits.
Corticon is a digital virus capable of disrupting the brain’s natural balance between excitatory and inhibitory neurons. If it is not stopped in time, Dr. Z will lose control over his motor systems, cognitive abilities, and decision-making, leading to complete neural shutdown. You are trained to simulate and understand biological neural circuits to isolate and combat neural threats. Your mission is to model a simplified cortical microcircuit, analyze how Corticon has disturbed its natural dynamics, and simulate potential rescue interventions in real-time.

Research paper By Heiko J. Luhmann mainly aims on:

1)Neocortical Structure and Cell Types
2)Connectivity and Microcircuits
3)Dynamics of Synaptic and Network Activity
4)Beyond the Canonical Model
5)Implications for Brain Function and Disease

On the other side jupyter notebook include code for:

1)Implementation of Izhikevich neuron model using pythons and its libraries
2)Izhikevich neuron model with the varying input Current and the variation of membrane potential as the time passes by.
3)STDP curve showing how synaptic weight changes based on the timing difference between pre- and postsynaptic spikes.
4)Simulating and Plotting a Spiking Neural Network of Izhikevich neurons with spike-timing-dependent plasticity (STDP) including rastor plots and membrane potentials.
5)Simulating how a Spiking Neural Network reacts to a Corticon-like disturbance which includes weakened inhibition, unbalanced excitation, and noisy external inputs using a Izhikevich neurons with STDP plasticity.


| Brian2 Component | Purpose                                                                                                              |
| ---------------- | -------------------------------------------------------------------------------------------------------------------- |
| `start_scope()`  | Resets the Brian2 simulation environment to avoid overlap of previous variables/simulations.
| `NeuronGroup()`  | Defines a group of neurons and how they behave using differential equations (Izhikevich model here).                 |
| `Synapses()`     | Creates synaptic connections between neurons, including plasticity rules like STDP.                                  |
| `SpikeMonitor()` | Monitors and records when each neuron spikes (i.e., reaches threshold).                                              |
| `StateMonitor()` | Tracks internal state variables (like membrane potential `v`) of specified neurons over time.                        |
| `run(duration)`  | Runs the simulation for the specified time (`1 second` in my case).                                                |
| `clip()`         | A Brian2 function to restrict a variable (like synaptic weights) within a defined range.                             |
| `ms`             | Time unit (millisecond) from Brian2. Used to make time values biologically meaningful.                               |
| `rand()`         | Returns random values between 0 and 1 — Brian2 version, vectorized for use in equations.                             |

VAIBHAV KALYAN(241125)


2) Design Task( Made Using Canva)
Containing Poster on the topic-"Anchoring Bias"
Anchoring bias is a sneaky little cognitive glitch where your brain clings to the first piece of information it gets—the “anchor”—and then uses it as a reference point for all future judgments, even when it’s completely irrelevant.
