# Testing Notes

Notes on testing e2e icq wasm contract <> icq module.

- two pre generated chain configs in `.sender/` and `.receiver/`
- `icq.wasm` contract is already deployed to `.sender/` 
  - can verify by issuing wasm queries
- validator key name for both `.receiver/` and `.sender/` is just `validator`
- keyring backend is `test`
