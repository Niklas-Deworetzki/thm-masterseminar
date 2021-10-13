# Mastersseminar – Compiler Construction and Distributed Systems

This repository contains resources for MS5001 "Masterseminar" a course at the Technische Hochschule Mittelhessen, held by Prof. Dr. Uwe Meyer in the winter of 2020.
The course expects students to prepare a critical presentation of a scientific paper on a topic of computer science or its applications.
This courses topic was "Compiler Construction and Distributed Systems".

## Contents of this Repository

This repository holds all resources I collected during this course as well as an [academic paper](paper/paper.pdf) and [prepared lecture](paper/presentation/THM-Praesentation-FB06-MNI.pdf).
The topic for my critical presentation was "Using Partial Evaluation to Generate Compilers".

Partial evaluation in general provides a unifying paradigm for program generation and program analysis.
The key feature of partial evaluation is the so called specialization of programs; an optimization technique **and** execution strategy.
Specialization uses the information provided by static inputs known to a program in order to pre-compute parts.
This pre-computation yields an often shorter program that requires less resources at runtime, where the remaining inputs are used.

My presentation on this topic introduces the basic concepts of partial evaluation and classifies them in contrast to classical approaches of program execution as well as program optimization.
Core concepts of partial evaluation and basic specialization strategies are also explained.
As one of the key insights of partial evaluation, the Futamura projections are presented, which provide a direct link between partial evaluation and compiler construction.

Copyright (C) 2021, Niklas Deworetzki

