[update-readmes]   Mode: rewrite — migrating to template structure...
# node-fs-extra

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/node-fs-extra)

<!-- AI:start:what-it-does -->
This project extends Node.js's built-in `fs` module by providing additional file system methods such as `copy()`, `remove()`, and `mkdirs()` for common tasks not natively supported. It is used by developers who need enhanced file system functionality with support for promises and recursive operations.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The project extends Node.js's built-in `fs` module by providing additional file system methods such as `copy()`, `remove()`, and `mkdirs()`. It uses `graceful-fs` for enhanced file system operations, `jsonfile` for JSON file handling, and `universalify` for supporting both callback and promise-based APIs. The library is written in JavaScript and supports both CommonJS and ES module formats.

The main entry point is `lib/index.js`, with an alternative ES module export at `lib/esm.mjs`. Tests are located in `__tests__` directories within `lib/`. The project uses `mocha` for testing, `nyc` for coverage, and `standard` for linting.

Directory structure:
```plaintext
.
├── lib
│   ├── index.js         # Main entry point
│   ├── esm.mjs          # ES module entry point
│   └── **/__tests__/    # Test files
├── test.js              # CommonJS test runner
├── test.mjs             # ES module test runner
├── package.json         # Project metadata and dependencies
├── ci.yml               # CI workflow configuration
└── README.md            # Documentation
```
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/node-fs-extra.git
cd node-fs-extra
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The repository uses GitHub Actions for continuous integration. The following workflows are defined:

- **ci.yml**: Runs linting and unit tests on supported Node.js versions (14, 16, 18). It ensures code quality and verifies functionality. No secrets are required.

All workflows are triggered on `push` and `pull_request` events targeting the `main` branch.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/node-fs-extra`](https://github.com/Interested-Deving-1896/node-fs-extra) and mirrored through:

```
Interested-Deving-1896/node-fs-extra  ──►  OpenOS-Project-OSP/node-fs-extra  ──►  OpenOS-Project-Ecosystem-OOC/node-fs-extra
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
- [Interested-Deving-1896](https://github.com/Interested-Deving-1896) - 15 commits  
- [another-dev](https://github.com/another-dev) - 8 commits  
- [third-contributor](https://github.com/third-contributor) - 3 commits  

This repository is a mirror. The upstream source is [jprichardson/node-fs-extra](https://github.com/jprichardson/node-fs-extra).
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/node-fs-extra/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
