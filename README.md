# LocalAgent Builds

Central repository for LocalAgent modular builds.

## Structure
- `manifest.json` - Current build version and module versions
- `CHANGELOG.md` - Global changelog
- `releases/` - Release notes per build

## API
Fetch latest build info:
```
GET https://raw.githubusercontent.com/THEMiS-eng/localagent-builds/main/manifest.json
```

## Versioning
- **BUILD**: `X.Y.ZZZ` (major.minor.patch)
- **Modules**: Independent semver per module
