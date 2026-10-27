# FITIG SEO Spider 0.1.46

Installed and checked on 2026-10-27. Partial-tested matrix coverage is 188/206 (91.3%), not full Screaming Frog equivalence.

Adds optional `response_hash`: SHA-256 of the complete HTTP payload before character decoding. The separate `content_hash` remains a normalized-content signature. Failed fetches, truncated bodies over 10 MiB and legacy crawls retain unknown response hashes. No legacy migration or inferred byte hashes are performed. Content has an exact-response duplicate filter and hash column; saved analysis groups known matching payloads. Comparison reports changes only when both crawls recorded the response hash. Full global CSV/XLSX exports retain their existing columns; current-table export includes the new column.

Fixes pacing after robots resolution/connection setup by retaining nonzero-delay admission until response headers arrive. Retries and robots requests share the gate. Slow headers can conservatively reduce concurrency with a nonzero delay; zero-delay crawling retains bounded parallelism. Initial repeated timing-test failures were investigated; the complete engine suite passed after the fix.

Validation: 204 engine unit/integration/CLI tests, 95 Vitest UI tests, 7 Node model tests and 9 Tauri tests (315 total). Three installed native suites passed 60 checks: response-hash 12, core-contract 40, concurrency 8. Independent Node crypto checks the recorded byte digest; real Content table/filter, empty response, truncated payload, SQLite read-only reload, duplicate analysis, crawl comparison and measured HTTP pacing are exercised. Historical 0.1.45 had 608 native checks across 27 suites; these were not all rerun for this release.

The installer and CLI passed targeted ESET scans with zero detections/cleaned files. The silent upgrade exited successfully, executable/loader match installer payload, and all 15 original app-data files remain byte-identical. Prior program files are backed up locally. Installer SHA-256: 1B46B981D2B43B6FAD0F6243BF98A501CE316432E8B9D069847B4EEBC79D578C.

Repository preparation uses Vitest 5.0.5, aligns Vite/Tauri dev port 1420, and preserves pinned vendor/data bytes on Windows checkout. Public source excludes credentials, user crawl databases, competitor files, local logs and acceptance recordings. GitHub build status is separate evidence and must be read from the PR checks.

Remaining limits include full Hebrew translation, form authentication, AI/semantic providers, Sheets export, complete competitor inventory, account/licensed workflow verification and code signing. This release does not claim those capabilities complete.
