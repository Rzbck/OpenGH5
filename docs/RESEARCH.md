# Research methodology

OpenGH5 research should be **reproducible, evidence-based and safe to publish**.

## Finding template

- **Title:** concise, specific statement
- **Category:** firmware / Wi-Fi / USB / Bluetooth / dashboard
- **Camera model:** exact body name (e.g. DC-GH5)
- **Firmware version:** exact version or 'unknown'
- **Claim status:** hypothesis / independently reproduced / verified
- **Method:** steps that do not expose proprietary code or secrets
- **Evidence:** original observations, sanitized protocol examples, relevant links
- **Limitations:** unresolved issues, equipment and firmware variants
- **Safety:** read-only / changes volatile state / changes persistent state
- **Date and contributors:** when and by whom

## Evidence rules

1. Cite original maintainers and canonical vendor sources.
2. Separate a source author's claim from a personally replicated result.
3. Prefer synthetic or redacted examples to raw captures.
4. Do not upload vendor firmware, memory dumps, copyrighted decompilation or credentials.
5. Note when a finding applies to GH5S, GH5 II or another camera rather than the original GH5.

## Storage

Store raw vendor firmware, camera captures and private analysis outside the repository. Check `.gitignore`, `git status`, and the staged diff before every public push.
