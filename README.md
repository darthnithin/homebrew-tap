# Perch for Homebrew

A terminal workspace for UCSC Hummingbird, with animated Chip, workload preparation,
keyboard and mouse navigation, and CLI/MCP tools.

```sh
brew install darthnithin/tap/perch
perch --demo --no-config
perch setup
```

Supports Apple Silicon and Intel Macs, plus ARM64 and x86-64 Linux. Installs
prebuilt binaries with SHA-256 verification; Go and Python are not required.
OpenSSH is needed for live Hummingbird connections.

Update with `brew update && brew upgrade darthnithin/tap/perch`.
Remove with `brew uninstall darthnithin/tap/perch`. Saved Perch preferences are
not removed by uninstalling the executable.

[Perch and installation guide](https://github.com/darthnithin/perch) ·
[Releases](https://github.com/darthnithin/perch/releases)

The formula is MIT licensed. Perch software is MIT licensed; Chip artwork is
reserved under the [bundled artwork terms](https://github.com/darthnithin/perch/blob/main/assets/bird/LICENSE).
The formula installs both notices and the optional terminal profile alongside the documentation.
