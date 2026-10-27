# FITIG SEO Spider

Independent Windows SEO crawl workbench using Rust, Tauri 2, React, TypeScript and SQLite. Source baseline: **0.1.46**.

## Status

188 of 206 tracked entries (91.3%) have partial implementation/test evidence. This measures matrix coverage, **not full Screaming Frog parity**. See [feature matrix](docs/feature-parity-matrix.md) and [scope and limitations](docs/milestone-90-coverage.md). This repository snapshot does not include private crawl data, credentials, installed competitor files, acceptance recordings or local build logs.

The local 0.1.46 release was checked with 315 automated tests and 60 installed native assertions across 3 targeted suites. These historical results are recorded in the release notes; they are not claims that all these checks run in CI. Integrations requiring accounts, complete Hebrew translation, form login, AI/semantic services and signed packaging remain incomplete. Local security policies and antivirus exclusions are not required build steps.

## Build on Windows 11

Install current stable Rust (MSVC toolchain), Visual Studio C++ build tools, WebView2 Runtime and Node.js 24. From this directory:

```powershell
npm ci
npm --prefix ui ci
cargo test --locked --manifest-path engine/Cargo.toml
npm --prefix ui test
npm --prefix ui run test:core
npm --prefix ui run build
npm exec -- tauri build --bundles nsis --ci
cargo build --release --locked --manifest-path engine/Cargo.toml
```

The installer is under `src-tauri/target/release/bundle/nsis`. The CLI is `engine/target/release/fitig-engine.exe`. Binaries are unsigned. Test native Windows desktop features in an interactive session; CI builds cannot replace GUI acceptance and licensed/account service checks. Some OS-provider tests require Windows spelling services and per-user credential storage.

Development: `npm run dev` (UI on port 1420). Crawls are user-owned SQLite files; do not commit them.

## Rights and dependencies

This is an independent implementation. No proprietary competitor code, artwork, branding or licensing mechanism is distributed. No open-source license grant for original FITIG code has been selected; all rights are reserved. Third-party assets retain their own licenses and notices under `assets/third-party` (axe-core MPL-2.0; AMP validator Apache-2.0). Rust/npm dependencies retain their respective licenses.

## Release 0.1.46

See [release evidence and limits](docs/release-0.1.46.md). Adds complete received-payload SHA-256, exact response duplicate grouping/filtering and byte-only crawl comparison while retaining unknown legacy/truncated observations. Fixes global nonzero request pacing after robots/connection waits; slow response headers can conservatively reduce concurrency. The 0.1.45 baseline separately had 608 native checks, which were not all rerun or combined into a new full certification. GitHub CI status is reported by the PR checks.
