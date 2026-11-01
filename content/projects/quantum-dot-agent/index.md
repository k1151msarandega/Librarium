---
title: "Autonomous agent for tuning quantum-dot devices"
date: 2025-10-01
summary: "An uncertainty-driven software agent that decides which measurement to take next when calibrating a quantum-dot device. In development."
tags: ["Computation", "Devices"]
featured: true
---

**Status:** in development, started October 2025.

**The problem.** Tuning a quantum-dot device means finding good settings in a multi-dimensional space of gate voltages. The usual approach, raster scanning, measures everywhere and is slow.

**The approach.** A closed-loop, active-inference agent keeps a belief over the device parameters using Rao-Blackwellised particle filtering with per-particle Kalman estimation. At each step it picks the measurement with the highest closed-form information gain, updates its belief in real time, and repeats. The pipeline is written in Python and integrates QArray.

**What I am learning.** Early benchmarks of single-step greedy acquisition across six simulation seeds isolated specific failure modes, which now guide the design of multi-step planning.

The code is under active development, so this page describes the method rather than fixed results.
