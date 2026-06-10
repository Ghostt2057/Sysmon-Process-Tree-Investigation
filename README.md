# Sysmon Process Tree Investigation

## Introduction

This project demonstrates the investigation of Windows process execution using Sysmon Event ID 1 (Process Creation).

The objective of the lab was to generate a controlled process chain, analyze Sysmon telemetry, investigate parent-child process relationships, and reconstruct the complete execution path of multiple processes.

Process tree analysis is a fundamental technique used by SOC analysts, incident responders, and threat hunters to understand how applications are launched, identify suspicious execution chains, and investigate potential malicious activity.

## Lab Environment

* Windows 10
* Sysmon
* Event Viewer

## Investigation Objectives

* Analyze Sysmon Event ID 1
* Investigate process creation events
* Identify parent-child process relationships
* Review command-line execution
* Reconstruct a process tree
* Understand process monitoring techniques
