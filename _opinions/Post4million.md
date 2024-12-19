---
title:  "Nekoo et al. In-space collisions"
date:   2064-12-09 17:45:00
comments: true
toc: true
categories:
  - Space Robotics
  - Collisions
  - Dynamics and Control
---

_These are some notes on the paper ["Free-floating space
manipulator impacting a floating object: Modeling and
output SDRE controller design"](https://www.sciencedirect.com/science/article/pii/S1270963824000786)
by Nekoo et al._

# Abstract
This work investigates the dynamics modeling, control, and impact resolution between a floating object
and a free-floating space manipulator (FFSM). The controller design is carried out by using an output- and
state-dependent Riccati equation (OSDRE) approach. In a collision between an object and a mechanism, the
computation of the generalized velocities and the impact force or impulse, which are interrelated, is a challenging
problem. Taking into account the free-floating conditions of the space environment, the conservation of linear
and angular momentum equations, combined with the conservation of kinetic energy under the elastic impact
assumption, are used to find the unknown variables of the impact problem. The control problem addressed for
the FFSM is to regulate its end-eﬀector in a point-to-point motion scenario, this while the space manipulator
suﬀers an unintended impact with a floating object, such as a damaged satellite or space debris. By proposing
a safety pause starting with the occurrence of impact and for a short duration thereafter, the proposed OSDRE
design succeeds in achieving the end-eﬀector regulation control. Although the FFSM can reach the target point,
it is shown that maintaining the end-eﬀector regulation at the target is not feasible due to the momentum
imparted to the FFSM as a result of the collision. To this end, we employ a simple thruster control on the
space manipulator base to complete the regulation task. The theoretical development and controller design are
demonstrated through a simulation case study of a spacecraft equipped with a three-link manipulator colliding
with an object.


# Introduction

The ideal scenario in such a
situation would be the completion of a control task by the space manip-
ulator, even though it suﬀered a collision. 

# Modeling: Mathematical Representation of Dynamics
## Dynamics Model of the Floating Object
## Dynamics Model of FFSM
## Impact Modeling
## Reduced-order Dynamics for Controller Design

# Output Feedback SDRE Control

# Case Study: FFSM with a Three-DoF Manipulator
## System Definition
## Simulation: Baseline Scenario
## Simulation: FFSM Response to Impact Without Post-impact Actuation
## Free-flying in Safety Pause: Compensating for Impact Momentum
## Asymptotic Convergence, Velocity of the End-effector

# Conclusions
## Concluding Remarks
## Future Studies: Penetration, Pushing, and Passing Through the Object