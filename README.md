# Chaotic Systems and Causal Inference with Convergent Cross Mapping

This repository contains a report on the analysis of causal relationships in a two-variable chaotic dynamical system using **Convergent Cross Mapping (CCM)**.

The goal of the project is to show how CCM can be used to infer the direction and strength of causality between two coupled time series, even when classical correlation-based methods fail.

## Overview

The system studied is a discrete dynamical system composed of two interacting variables, \(X\) and \(Y\). Although the two time series are weakly coupled, their chaotic behavior makes standard correlation analysis inconclusive.

The report compares classical approaches, such as Pearson correlation and cross-correlation, with Convergent Cross Mapping, showing that CCM is able to detect causal links that are not visible through simple correlation measures.

## Dynamical System

The analyzed system is:

```math
X(t + 1) = X(t) [ r_X - r_X X(t) - \beta_{XY} Y(t) ]
