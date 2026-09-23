# Project Overview

## Scope

This document provides a concise engineering overview of the Cadence Virtuoso project represented by the available screenshots.

## Design Hierarchy

The evidence shows a progression from basic CMOS gates to arithmetic circuits:

1. AND gate
2. OR gate
3. XOR gate
4. 1-bit full adder
5. Ripple-carry adder

The full adder combines the logical operations required to generate a sum and carry. Multiple full-adder stages can then be cascaded to form a ripple-carry adder.

## Evidence Types

The available screenshots fall into four categories:

- **Schematics:** transistor/gate-level circuit representations.
- **Layouts:** physical layout views for the available circuits.
- **Testbenches:** simulation setup views for the full adder and ripple-carry adder.
- **Simulation:** transient waveform/result views, including extracted/post-layout evidence.

## Reproducibility Status

The original Cadence Virtuoso project is not available. Consequently, the repository is an evidence archive/documentation package rather than a directly reproducible Cadence project.

A future reproducible version should include the original Cadence libraries/cells, technology/PDK information where licensing permits, ADE configuration, simulation setup, and verification reports.

## Verification Status

The supplied screenshots show simulation waveforms, but they do not provide formal DRC/LVS reports or explicit DRC/LVS pass statements. Therefore, this repository does not claim DRC or LVS completion/pass status.
