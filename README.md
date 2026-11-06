# CaSkBot — An Ontology for Capabilities and Skills of Heterogeneous Autonomous Robots

CaSkBot is the robotics-domain layer of the three-level CaSkade ontology
architecture for modelling capabilities and skills. It extends
[CaSk](https://github.com/CaSkade-Automation/CaSk) with standards for robotics —
IEEE 1872, IEEE 1872.2, MQTT — to describe autonomous robots (UAV, UGV, USV),
their capabilities, and the skill interfaces through which those capabilities are
executed.

It is the counterpart to [CaSkMan](https://github.com/CaSkade-Automation/CaSkMan),
which covers manufacturing.

> **Status: work in progress.** The model was published in 2023 (see *Citing*
> below); the alignment ontology is currently being built.

## Architecture

```
L1  CSS       Capability/Skill/Service reference model (Plattform Industrie 4.0)
L2  CaSk      VDI 3682, VDI 2206, DIN EN 61360, PackML, OpenMath
L3  CaSkMan   manufacturing
    CaSkBot   robotics  <- this repository
```

Each layer imports the one above it. CaSkBot itself contains **only alignment
axioms**: the ontology design patterns (ODPs) it connects are maintained in
separate repositories and stay independently reusable.

## Citing

The model is published as:

> L. M. Vieira da Silva, A. Köcher, A. Fay, "A capability and skill model for
> heterogeneous autonomous robots", *at – Automatisierungstechnik* 71(2), 2023,
> pp. 140–150. DOI [10.1515/auto-2022-0122](https://doi.org/10.1515/auto-2022-0122)

The publication refers to this ontology as *RoboCaSk* and to the repository
`Miguel2617/robocap`. Both were renamed; this repository is the continuation.

## Developed at

Institut für Automatisierungstechnik (IfA), Helmut-Schmidt-Universität Hamburg.
