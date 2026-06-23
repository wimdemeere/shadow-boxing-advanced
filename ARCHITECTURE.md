# Architecture Decisions

## Overview

The advanced version moves from a single-file application to a lightweight modular architecture while remaining framework-free for as long as possible.

## Key Decisions

### 1. No Heavy Framework
- We will use vanilla JavaScript with a lightweight module/component pattern.
- Goal: Keep the app fast, simple to deploy, and easy to maintain.

### 2. Audio Strategy
- Replace Web Speech API with pre-recorded audio clips.
- Audio will be organized by mode (boxing, kickboxing, etc.).
- Audio will be lazy-loaded when a mode is selected.

### 3. State Management
- Use a central workout engine module.
- UI components will react to state changes via simple event system or direct method calls.

### 4. Build Process
- Start with no build step.
- Consider adding a simple bundler (Vite or esbuild) only when the project grows significantly.
