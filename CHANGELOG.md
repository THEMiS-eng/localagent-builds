# LocalAgent Build Changelog

## [1.0.006] - 2026-02-01

### Summary
Modular architecture with build versioning system

### Highlights
- New modular build system with independent module versions
- Build check API for update notifications  
- Banner shows module-level updates

### Module Changes

#### localagent-service v3.3.032
- Added `/api/build/check` endpoint
- Added `/api/build/modules` endpoint
- `/api/app` now returns BUILD version and module list

#### themis-ui v0.1.7
- Landing page shows BUILD version
- Update check uses new build manifest
- Banner shows module update count

---

## [1.0.005] - 2026-02-01

### Summary
Initial modular build release

### Modules
| Module | Version |
|--------|---------|
| localagent | 0.1.0 |
| localagent-service | 3.3.031 |
| ai-chat-module-pro | 0.1.0 |
| prompt-linter | 0.1.0 |
| themis-ui | 0.1.6 |
| dashboard | 0.1.0 |
| skills-engine | 0.1.0 |
| whisper-module | 0.1.0 |
