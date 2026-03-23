---
layout: page 
title: Research 
---

My research explores how the collective behavior of electrons in quantum materials gives rise to exotic phenomena — from frustrated magnetism and spin liquids to superconductivity at material interfaces. I combine low-temperature transport, microwave spectroscopy, and nanofabrication to probe these states, and have also developed machine learning tools for automating quantum device experiments. Below is an overview of the main threads of my work.

# Quantum Spin Liquids and Frustrated Magnetism

![QSL resonator](/assets/images/spinliquid-res.png)

When magnetic moments sit on a geometrically frustrated lattice, the competition between exchange interactions can prevent long-range order and instead stabilize exotic quantum states of matter such as quantum spin liquids. My current work at Stanford focuses on TbInO<sub>3</sub>, a hexagonal antiferromagnet where Tb<sup>3+</sup> moments on a triangular-honeycomb lattice remain disordered down to millikelvin temperatures. To probe the magnetic excitations in epitaxial thin films of this material, I developed a microwave spin resonance technique using NbTiN superconducting coplanar waveguide resonators deposited directly on the films. This approach, inspired by circuit quantum electrodynamics, enables sensitive detection of spin excitations while being compatible with millikelvin cryogenics. Our measurements reveal two distinct magnetic resonance modes arising from the two inequivalent Tb sites created by improper ferroelectricity, and the extracted in-plane susceptibility confirms extreme frustration of magnetic order down to 20 mK — over two orders of magnitude below the Curie-Weiss temperature.

[S.S. Kalantre, J. Nordlander, M.A. Anderson, J.A. Mundy, and D. Goldhaber-Gordon, Microwave spin resonance in epitaxial thin films of spin liquid candidate TbInO<sub>3</sub>, arXiv:2603.14545 (2026)](https://arxiv.org/abs/2603.14545)

# Microwave Probes of Correlated Electronic Systemss

![Resonator Probes](/assets/images/res-probes.png)

Beyond TbInO<sub>3</sub>, I am building a broader experimental toolkit that uses superconducting microwave circuits to probe correlated electron materials. One thrust involves a flip-chip geometry where a superconducting resonator chip is placed face-down on a sample of interest, enabling rapid screening of different thin-film materials for magnetic or superconducting signatures without the need for lithography on each sample. A second thrust adapts techniques from circuit quantum electrodynamics to measure the superfluid stiffness of van der Waals superconductors at GHz frequencies — a quantity that is directly related to the superconducting carrier density and provides insight into the pairing mechanism. These approaches complement traditional DC transport, offering spectroscopic access to energy scales and dynamics that are invisible to resistance measurements alone. 

# Josephson Junctions in Topological and Van der Waals Materials
![Graphene Shapiro](/assets/images/gra-shapiro.png)

Josephson junctions built from exotic weak-link materials serve as sensitive probes of novel superconducting and topological phenomena. I have studied graphene-based Josephson junctions where hexagonal boron nitride encapsulation provides high-mobility weak links. Under RF drive, these junctions exhibit an unexpected bistability between ±1 Shapiro steps with switching times on the order of seconds — a phenomenon we explained through the nonlinear dynamics of the driven pendulum problem, revealing a critical scaling near the onset of bistability. In parallel, I contributed to measurements of SnTe topological crystalline insulator nanowire junctions, where we observed signatures of time-reversal symmetry breaking: an asymmetric DC critical current, a prominent second-harmonic AC Josephson response, and a magnetic diffraction pattern with a critical current minimum at zero field. These features point to an unconventional superconducting order parameter influenced by multiband effects and ferroelectric domain walls in the SnTe.

[S.S. Kalantre et al., Anomalous Phase Dynamics of Driven Graphene Josephson Junctions, Phys. Rev. Research 2, 023093 (2020)](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.023093)

[C.J. Trimble, M.T. Wei, N.F.Q. Yuan, S.S. Kalantre et al., Josephson Detection of Time Reversal Symmetry Broken Superconductivity in SnTe Nanowires, npj Quantum Materials 6, 61 (2021)](https://www.nature.com/articles/s41535-021-00359-w)


# Machine Learning for Quantum Device Automation
![Auto-tuning](/assets/images/autotuning.png)


Scaling up semiconductor quantum dot architectures for quantum computing demands automated approaches to navigate the vast parameter spaces involved in device tuning. At NIST, I developed one of the first demonstrations of fully automated quantum dot tuning using deep learning. We trained convolutional neural networks on simulated current-voltage maps to recognize charge configurations of double quantum dot devices, and then closed the loop: the CNN predictions fed into an optimization algorithm that navigated the gate voltage space to automatically bring a real device to the desired single-electron regime. This was the first in-situ demonstration of ML-based auto-tuning in quantum dots. Follow-up work with collaborators extended these ideas through the ray-based classification framework, improving robustness to noisy experimental data and establishing a physics-informed approach that significantly outperforms purely data-driven methods.

[S.S. Kalantre, J.P. Zwolak et al., Machine Learning Techniques for State Recognition and Auto-Tuning in Quantum Dots, npj Quantum Information 5, 6 (2019)](https://www.nature.com/articles/s41534-018-0118-7)

[J.P. Zwolak, T. McJunkin, S.S. Kalantre et al., Ray-Based Framework for State Identification in Quantum Dot Devices, PRX Quantum 2, 020335 (2020)](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.13.034075)



