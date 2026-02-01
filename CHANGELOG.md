# LocalAgent Build Changelog

## [1.0.003] - 2026-02-01

### Build Changes
- Initial modular architecture release
- 8 independent modules

### Module Versions
| Module | Version | Changes |
|--------|---------|---------|
| localagent | 0.1.0 | Initial |
| localagent-service | 3.3.029 | Core service with 4 connectors |
| ai-chat-module-pro | 0.1.0 | Standalone chat extracted |
| prompt-linter | 0.1.0 | Linting, depends on ai-chat-module-pro |
| themis-ui | 0.1.5 | Flexbox fix for input expansion |
| dashboard | 0.1.0 | Service monitoring |
| skills-engine | 0.1.0 | 8 ADR skills |
| whisper-module | 0.1.0 | Audio transcription |

---

## Module Changelogs
- [localagent-service CHANGELOG](https://github.com/THEMiS-eng/localagent-service/blob/main/CHANGELOG.md)
- [themis-ui CHANGELOG](https://github.com/THEMiS-eng/themis-ui/blob/main/CHANGELOG.md)
- [ai-chat-module-pro CHANGELOG](https://github.com/THEMiS-eng/ai-chat-module-pro/blob/main/CHANGELOG.md)
