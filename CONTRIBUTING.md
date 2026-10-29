# Contributing to OpenGH5

OpenGH5 welcomes careful, reproducible GH5 research and contributions to interoperability tools.

## Before submitting

1. Search existing issues to avoid duplicates.
2. Explain the affected model and exact firmware version (for example, **DC-GH5**, not GH5 II or GH5S).
3. Distinguish facts from speculation. Describe how a finding was tested and what is still unknown.
4. Submit focused pull requests with a clear change summary and testing notes.
5. Prefer public documentation links and your own code over copied third-party material.

## Public repository rules

**Do not upload:** Panasonic firmware images, ROM/RAM dumps, copyrighted decompiled source, encryption keys, authentication tokens, passwords, serial numbers, MAC addresses, private IPs or unredacted packet captures.

Place raw experiments outside the Git worktree. The `.gitignore` file is only a safety net; check every staged file and commit manually.

Do not claim compatibility with a camera or firmware version that you have not tested. Clearly mark hardware-affecting experiments as experimental. Do not present untested firmware flashing instructions as safe.

## Research reports

Use [docs/RESEARCH.md](docs/RESEARCH.md) for provenance and reproducibility. If an issue could expose a security vulnerability, follow [SECURITY.md](SECURITY.md) before discussing it publicly.

## Code conventions

- Prefer small, reviewable components and clear documentation.
- Include tests for parsers, protocol handling, and other code that can be exercised without a camera.
- Keep camera-side actions opt-in and conservative; reads should not unexpectedly modify persistent camera state.
- Do not add runtime dependencies or external services without explaining the need.
