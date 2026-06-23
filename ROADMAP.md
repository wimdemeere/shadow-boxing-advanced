# Shadow Boxing Randomizer - Advanced Version Roadmap

## Project Vision

Build a reliable, practical, and progressively more powerful shadow boxing training tool. The advanced version moves beyond a simple single-file utility into a maintainable, feature-rich web application while staying true to the original goal: helping martial artists train effectively with minimal friction.

## Core Principles

- Reliability first (especially audio and timing)
- Practical training value over flashy features
- Progressive enhancement (start simple, add depth)
- Good offline experience
- Maintainable codebase

## Phased Roadmap

### Phase 1: Foundation & Reliability (v2.0)

**Goal**: Make the app stable and trustworthy.

**Key Deliverables**:
- Fix speech reliability (proper `onerror` + conservative watchdog)
- Remove `user-scalable=no` from viewport meta
- Add Skip button during active rounds
- Add boxing bell sound effect at round start/end
- Improve Service Worker for better caching
- Basic code cleanup and documentation

**Status**: Ready to start

---

### Phase 2: Core Infrastructure (v2.1)

**Goal**: Lay the technical foundation for future features.

**Key Deliverables**:
- Replace Web Speech API with **pre-recorded audio clips**
- Move from single `index.html` to a **lightweight modular/component structure**
- Set up proper project folder structure
- Implement basic audio manager
- Create initial component system (no heavy framework)
- Improve PWA capabilities (better offline support)

**Status**: Next major phase

---

### Phase 3: Core Value Features (v2.2)

**Goal**: Add the features that deliver the biggest long-term value.

**Key Deliverables**:
- Session history + basic statistics
- Training streaks
- Simple session logging
- Enhanced PWA (installable with better offline experience)

**Status**: Planned

---

### Phase 4: Training Depth (v2.3+)

**Goal**: Add features that support serious, targeted training.

**Key Deliverables**:
- Custom combo authoring and saving
- Technique exclusion / blacklist
- Defense-only and footwork-only modes
- Optional "Endless" mode

**Status**: Future

---

### Phase 5: Polish & Advanced Features (v3.0+)

**Goal**: Long-term improvements and scalability.

**Potential Features**:
- Voice picker + speed control
- More advanced statistics and visualizations
- Optional cloud sync (only if demand exists)
- Component architecture improvements

**Status**: Future

---

## Current Status

- **Current Version**: v1.5 (single HTML file)
- **Target for v2.0**: Phase 1 completion
- **Target for v2.1**: Phase 2 completion (modular structure + audio)

---

## Next Steps

1. Create project structure and initial files
2. Set up `ARCHITECTURE.md` and supporting documents
3. Begin Phase 1 implementation
4. Plan audio recording strategy for Phase 2
