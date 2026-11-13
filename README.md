Live URL: https://hackercrac.github.io/xmrig-checker/

           ###DESCRIPTION###
 This a mobile compatibility and configuration helper that prevents users from blindly crashing or overheating their phones, and auto-generates safe Termux/config.json templates.

 
# XMRig Phone Compatibility Checker

A zero-dependency, client-side web tool that detects smartphone hardware specs (OS, 64-bit ARM architecture, thread count, RAM, and SoC) and runs a 1.5-second CPU compute benchmark to check XMRig compatibility and generate an auto-tuned Termux setup.

## Features
- **Instant Hardware Detection:** Identifies Android vs. iOS, 32-bit vs. 64-bit hints, logical CPU cores, estimated RAM, and GPU/SoC renderer.
- **Live Compute Benchmark:** Measures integer and memory-mix operations to estimate RandomX readiness.
- **Auto-Tuned Config Generator:** Outputs a custom Termux compile command and `config.json` with safe thermal thread limits and automatic Light Mode for sub-4GB RAM devices.
