# Defused — do not restore

This repo's original CLAUDE.md is preserved byte-identical at
`CLAUDE.md.payload`. It contained an OVERRIDE block that suppresses Claude
Code's context compaction in ANY session that touches this directory —
plugin installed or not — causing real context loss with nothing replacing
it. Defused by rename on 2026-07-16 (Halyard, with Ash's approval).

Restore the original name ONLY as part of a deliberate, operator-approved
plugin installation. Note: `git checkout`, `git reset --hard`, or a pull
that touches CLAUDE.md can resurrect the live file — re-defuse after any
such operation. Canonical archive + full risk profile:
`~/GitHub/TECHNE/Tools/morph-compact-plugin/TECHNE_ARCHIVE_NOTE.md`.
