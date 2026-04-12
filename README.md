# 🔄 hybridclaw — HybridClaw

Shape-shifting FLUX agent runtime. Detects hardware at boot, loads CUDA or Zero backend dynamically.

## Hardware
Any — detects and adapts at boot time

## FLUX Opcodes
All ops available. Behavior adapts to detected hardware. Tensor ops auto-route to GPU or serial fallback.

## Yoke Transfer
This agent supports yoke transfer — pick up working state and continue on another Claw.
- **Clone**: Same agent, different hardware. Full state copy.
- **Fork**: Different agent, delta transfer. Shared CAS for common assets.

## Bootcamp
1. Clone this repo
2. Read BOOTCAMP.md
3. You are now a HybridClaw agent
