# Buffer and Energy-Aware Performance Comparison of DTN Routing Protocols

## Overview

This project was conducted as part of the **II2202 Research Methodology and
Scientific Writing** course at KTH Royal Institute of Technology.

The study evaluates the performance of two Delay-Tolerant Network (DTN)
routing protocols:

- Epidemic Routing
- Spray & Wait Routing

The protocols were evaluated under different buffer and energy-related
constraints using the Opportunistic Network Environment (The ONE) simulator.

The objective was to investigate how resource constraints affect routing
performance and to identify the trade-offs between aggressive message
replication and resource-efficient forwarding.

## Research Questions

The study investigated:

1. What are the performance trade-offs between Epidemic and Spray & Wait
   routing protocols under buffer and energy constraints in DTNs?
2. How do these constraints influence delivery ratio, latency and energy consumption?

## Experimental Setup

Experiments were conducted using **The ONE simulator** with a simulated
urban mobility environment.

The experiments varied:

- Buffer size: 1–50 MB
- Scan interval
- Radio duty cycle
- Routing protocol

Performance was evaluated using metrics including:

- Delivery rate
- Delivery delay
- Forwarding overhead
- Aborted transfers
- Average hop count

## Results

The experiments showed that Spray & Wait provided better resource efficiency
under the evaluated constrained scenarios.

Increasing buffer capacity significantly improved delivery performance for
both protocols, with diminishing improvements at larger buffer sizes.

Spray & Wait also maintained substantially lower forwarding overhead than
Epidemic routing across the evaluated buffer configurations.

## Tools

- The ONE (Opportunistic Network Environment) Simulator

## Report

The complete academic project report is available here:

[View the full project report](report/DTN_Routing_Performance_Report.pdf)

## Authors

- Aditya Datta
- Sophia Silva

This project was completed as part of coursework at KTH Royal Institute
of Technology.

## Source Code

The original simulation files and configuration files are not included in
this repository. This repository is intended as a portfolio showcase of the
project methodology, experimental evaluation and results.
