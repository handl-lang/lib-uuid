# lib-uuid

UUID port types for the Handl platform.

## Layout

```text
src/        the .hnl sources
pkg.hnl     package manifest — modules, deps, description, license
scripts/hnl-gate.sh   the gate
workflows/gate.yaml       bupha entry (handl-gates)
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
