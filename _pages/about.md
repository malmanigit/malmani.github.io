---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final year PhD student at Yale University. I am interested in sensorimotor control, neural population dynamics, optimal feedback control and deep reinforcement learning.

# Current Projects

## muSim | Python, PyTorch, MuJoCo, OpenSim, MATLAB

* Developed a modular computational framework to elucidate the neural control of movement through anatomically
accurate musculoskeletal modeling.

* Adapted advanced deep reinforcement learning (DRL) algorithms with biologically plausible neural regularizations to
capture neural population dynamics.

* Trained recurrent neural network (RNN)-based models of motor cortex (MC) for feedback control of macaque (39
muscles) and mouse (18 muscles) forelimb musculoskeletal models on diverse motor tasks.

* RNN-models formulated using muSim captured complex/elaborate signatures and properties of motor cortical neural
population dynamics that can not be captured using existing models.

* Devised simultaneous goal- and data- driven modeling approaches to enable generalizable single-unit-level decoding of
motor cortical activity.

* RNN-models captured elaborate biologically interpretable properties in kinematic, neural and sensory subspaces, such as
robustness to perturbations and generalization to out-of-distribution unseen conditions.

* Validated the utility of perturbation experiments to disentangle the role of inputs in shaping neural population dynamics.

* Under review in Nature Methods.

## Optimal Feedback Control (OFC) to capture key features of motor cortical neural population dynamics| PyTorch, JAX

* Adapted OFC algorithms (iLQR) to formulate recurrent-network-based MC models for locally optimal feedback control of
anatomically accurate musculoskeletal models.

* Showed that strong time-varying input sensory features, such as proprioception, are essential to capture
complex/elaborate features of MC neural population dynamics.

* Utilized OFC theory to signify the importance of strong non-linear synaptic connections of MC to sensory processing
regions in shaping its neural population dynamics.

* Mathematically elaborated the connection of OFC framework with DRL framework.

* Publication in progress.

## muSim with internal forward models to investigate motor learning, control, consolidation and generalization

* Augmented muSim with predictive modeling, i.e., internal forward models of musculoskeletal and task dynamics.

* Validated the significance of predictive modeling in enabling faster training on complex motor tasks.

* Achieved significantly better generalization to unseen conditions with predictive modeling.

* Currently, investigating the signatures/properties of neural dynamics specific to internal forward models.

* Publication in progress

## muSim and OFC to disentangle the role of feedback vs feedforward control in BCI settings

* Modeled a target tracking motor task in brain-computer interface (BCI) setting using muSim.

* Modeled the BCI task and formulated a recurrent-network-based MC model using OFC framework with internal forward
model (observer framework).

* Currently, working on disentangling the signatures of neural population dynamics specific to feedback vs feedforward
control in OFC framework.

* Publication expected before graduation.

Graph Neural Networks (GNNs) for Physics Simulation | PyTorch Geometric, MuJoCo

* Implemented task- and musculoskeletal-dynamics- specific internal forward models using GNNs.

* Trained the developed sensorimotor loop using sensory feedback prediction from GNN-based internal forward models.

* Devised a new sparse graph attention mechanism robust to partial state feedback for modeling physics simulations
incorporating musculoskeletal models.

# Publications and Conferences

Muhammad Noman Almani, John Lazzari, Jeff Walker, Shreya Saxena. “Embodied sensorimotor control:
computational modeling of the neural control of movement”, Annual Review of Biomedical Engineering, 2026
(Accepted)

Muhammad Noman Almani, Shreya Saxena. “Optimal feedback mechanisms capture key features of motor
cortical activity”, Computational and Systems Neuroscience (COSYNE), 2026 (Submitted)

Muhammad Noman Almani, John Lazzari, Shreya Saxena. “muSim: A goal-driven framework for elucidating
the neural control of movement through musculoskeletal modeling”, Under review in Nature Methods

Muhammad Noman Almani, Shreya Saxena. “Towards Generalizable Neural Decoding: Simultaneous Goal-
and Data- Driven Modeling of Motor Cortex”, Computational and Systems Neuroscience (COSYNE), 2024

Muhammad Noman Almani, Shreya Saxena. “Modeling the contribution of sensory feedback and internal
models on motor cortex activity dynamics and task execution”, Neural Control of Movement (NCM), 2024

Muhammad Noman Almani, Shreya Saxena. “Taming machine learning models of neural dynamics with
anatomical and behavioral constraints”, Asilomar, 2023

Muhammad Noman Almani, Shreya Saxena. “Simultaneous goal- and data- driven modeling of motor cortex
using musculo-RNN”, Neural Control of Movement (NCM), 2023

Muhammad Noman Almani, Shreya Saxena. “Recurrent neural networks controlling musculoskeletal models
predict motor cortex activity during novel limb movements”, IEEE Engineering in Medicine and Biology
Conference (IEEE EMBC), 2022

Muhammad Noman Almani, Shreya Saxena. “Deep Reinforcement Learning mimics neural strategies for limb
movements”, Computational and Systems Neuroscience (COSYNE), 2022

Muhammad Noman Almani, Shreya Saxena. “Deep Reinforcement Learning mimics neural strategies for limb
movements”, Society for Neuroscience (SfN), 2022

Muhammad Noman Almani, Ghulam Amjad Hussain, Ashraf A. Zaher. “An Improved Technique for Energy
Efficient Starting and Operating Control of Single-Phase Induction Motors”, IEEE Access, 2021
