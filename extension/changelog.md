## Changelog of the extensions

### fix: - 11/17/2024 - @lumpinif

#### Observer Management and Memory Leak Prevention

- Added observer tracking using Set to manage all MutationObservers
- Added cleanup on element removal to prevent dangling observers
- Added global cleanup on window unload
- Added observer cleanup when observed elements are removed from DOM

#### Code Quality

- Fixed code formatting and linting issues flagged by Biome

#### Development Setup

- Added .vscode settings with Biome extension recommendation

#### Platform Updates

- Updated code in both Chrome and Firefox extensions
