# PFSP-Research
# Taillard Benchmark Instances for the Permutation Flow Shop Scheduling Problem (PFSP)

## 1. Overview

This repository contains Taillard benchmark instances for the Permutation Flow Shop Scheduling Problem (PFSP).

The benchmark instances provide processing times for different jobs across multiple machines. They are used to evaluate and compare optimisation algorithms designed to minimise the makespan in flow shop scheduling problems.

## 2. Dataset Description

The dataset contains processing-time information for scheduling jobs on a set of machines.

Each benchmark instance specifies:

- **Number of jobs (n):** Total number of jobs to be scheduled.
- **Number of machines (m):** Total number of machines involved in processing.
- **Processing times (pᵢⱼ):** Time required to process job i on machine j.

The processing times are used to construct the scheduling problem and evaluate the performance of different solution methods.

## 3. Repository Structure

```text
PFSP-Research/
│
├── benchmarks/
│   └── Taillard/
│       ├── tai001.txt
│       ├── tai002.txt
│       ├── tai003.txt
│       └── ...
│
└── README.md
```

## 4. Purpose

The benchmark instances are used in a comparative evaluation of optimisation methods for minimising makespan in the PFSP.

The methods considered include:

- Mixed Integer Linear Programming (MILP)
- Branch and Bound (BB)
- Iterated Greedy (IG)
- Genetic Algorithm (GA)

The objective is to compare the solution quality and computational performance of these methods using common benchmark instances.

## 5. Usage

The processing-time files can be downloaded from this repository and imported into Python for scheduling experiments.

The processing-time matrix is represented as:

\[
P = [p_{ij}]
\]

where \(p_{ij}\) denotes the processing time of job \(i\) on machine \(j\).

## 6. Research Application

These benchmark instances support experimental analysis of:

- Makespan minimisation.
- Scheduling algorithm performance.
- Computational time comparison.
- Solution quality evaluation.
- Comparison of exact and metaheuristic methods.

## 7. Acknowledgement

The benchmark instances originate from the Taillard flow shop scheduling benchmark collection.

They are used for academic and research purposes in evaluating solutions to the Permutation Flow Shop Scheduling Problem (PFSP).
