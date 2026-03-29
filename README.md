# CyberGuard AI

Lightweight Cybersecurity Threat Analyzer (CPU-Based)

## Overview
CyberGuard AI is a lightweight cybersecurity threat analyzer focused on fast, practical log analysis. It classifies activity into three levels:

- Safe
- Suspicious
- Malicious

It also returns a short explanation and preventive actions.

## Problem
Many security AI systems depend on expensive cloud/GPU infrastructure, which can cause:

- High cost
- Limited accessibility for small teams
- Cloud dependency
- Slower response in critical moments

## Solution
CyberGuard AI aims to provide a specialized, efficient approach by:

- Using a task-focused model design for cybersecurity logs
- Running on CPU-oriented environments
- Delivering fast classification with actionable output
- Supporting low-resource/offline-friendly use

## Features
- Log/activity input analysis
- Threat classification (Safe / Suspicious / Malicious)
- Structured output:
  - Classification
  - Explanation
  - Preventive Actions
- Minimal dark-themed web UI
- Mock inference flow for prototype/demo

## Example
Input:

```text
Multiple failed login attempts from unknown IP
```

Output:

```text
Classification: Malicious
Explanation: Possible brute-force behavior detected
Preventive Actions: Block source IP, enable account lockout, enforce MFA
```

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- UI Theme: Dark, minimal card layout
- Analyzer Logic: Mock JavaScript classifier (no backend)

## Future Improvements
- Connect to real ML inference backend
- Add SIEM/log pipeline integration
- Improve anomaly detection and confidence scoring

## Author
Adarsh
