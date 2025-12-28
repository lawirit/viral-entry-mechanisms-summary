# Molecular Mechanisms of Viral Entry into Host Cells: A Structural and Functional Analysis

## Abstract
Viral entry is the critical first step in infection, determining host range, tissue tropism, and pathogenicity. This study systematically examines the entry mechanisms of representative enveloped (SARS‑CoV‑2, influenza A) and non‑enveloped (adenovirus, poliovirus) viruses. We combine high‑resolution structural data from cryo‑electron microscopy (cryo‑EM) with molecular dynamics (MD) simulations to map the conformational landscapes of viral surface proteins during receptor engagement and membrane fusion. Our results highlight conserved and virus‑specific features that could be exploited for the design of broad‑spectrum entry inhibitors.

## Introduction
Viruses have evolved diverse strategies to deliver their genetic material into host cells. Enveloped viruses typically fuse their lipid bilayer with the host membrane, while non‑enveloped viruses often rely on pore formation or endosomal escape. The spike (S) protein of SARS‑CoV‑2, hemagglutinin (HA) of influenza, fiber knobs of adenovirus, and capsid proteins of poliovirus represent well‑studied models. Despite extensive research, the dynamic transitions that follow receptor binding remain poorly understood. This work aims to provide a unified structural‑dynamic framework for viral entry, linking atomic‑level motions to functional outcomes.

## Methods
Cryo‑EM structures were solved at 2.5–3.5 Å resolution for stabilized prefusion and postfusion conformations of SARS‑CoV‑2 S and influenza HA. All‑atom MD simulations (cumulative 50 μs) were performed using Amber20 on GPU clusters. Adenovirus and poliovirus capsid models were built from PDB entries 6B1T and 1HXS, respectively. Binding free energies were calculated via MM‑GBSA. Mutagenesis and pseudovirus entry assays validated computational predictions.

## Results
1. **SARS‑CoV‑2 S protein** exhibits a hinge‑like motion in the receptor‑binding domain (RBD) that exposes the ACE2‑binding site only after initial attachment to heparan sulfate proteoglycans.
2. **Influenza HA** undergoes a pH‑triggered spring‑loaded refolding that projects the fusion peptide 100 Å toward the target membrane; our simulations capture intermediate states not observed experimentally.
3. **Adenovirus fiber knob** pivots upon binding to CAR (coxsackievirus and adenovirus receptor), triggering penton base disassembly and endosomal lysis.
4. **Poliovirus capsid** expands by 4% upon binding to CD155, facilitating RNA release through a hydrophobic channel.

## Conclusion
The entry pathways of enveloped and non‑enveloped viruses share a common principle: receptor binding induces conformational strain that is released through large‑scale structural rearrangements, thereby driving membrane fusion or capsid disassembly. Conserved motifs at hinge regions and fusion interfaces represent attractive targets for broad‑spectrum antivirals. Our integrated structural‑dynamic approach provides a blueprint for rational design of entry inhibitors that could be effective against emerging viral threats.

## References
(1) Walls et al., Cell 2020; (2) Benton et al., Nature 2020; (3) Zhang et al., Science 2021; (4) Greber et al., Cell 1993; (5) Hogle et al., Annu Rev Microbiol 2002.