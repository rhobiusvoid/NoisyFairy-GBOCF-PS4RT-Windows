# Contributing

Bug reports with a log are the most useful contribution: use the bug report form under Issues and
attach the newest file from `out\CUSA28763\user\log`.

For code changes:

1. Build with `scripts/build-windows.sh` (see [BUILDING.md](BUILDING.md)).
2. Run the tests: `python3 -m unittest discover -s tests -p 'test_*.py'`.
3. The executables in `bin/` are what `scripts/build-windows.sh` produces; do not replace them with a build you cannot reproduce. Releases carry the full zip.
4. One change per commit, with a message that says what and why.

Game data, keys, PKGs and decrypted executables must never be committed or posted.
