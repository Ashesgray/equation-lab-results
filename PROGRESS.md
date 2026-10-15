# Equation Lab progress

Research project owner / requested result credit: **Ashley Kalkowski**.

Snapshot: **2026-10-15T10:06:03Z**. Engine checkpoint: 2026-10-15T10:05:34.9855675Z.

| Measure | Observed value |
|---|---:|
| Engine health | healthy |
| Enabled / configured instances | 1662 / 1667 |
| Enabled instances with a completed batch | 1662 |
| Worker limit / scheduled duty | 16 / 70% |
| Exact completions reported by engine | 0 |
| Exact results passing both local checkers | 0 |
| Numerical candidates recorded (not proofs) | 1984 |
| Scheduled checks completed / planned | 2 / 18 |
| Missed scheduled checks | 0 |
| Completed observations waiting for export | 0 |

**Novelty and external acceptance are assessed separately. No discovery is established by this tracker.**

The engine automatically stops scheduling an exact completion. After independent exact verification, the monitor also disables that target and preserves its evidence.

## Work by family

Each counter uses its adapter's work units. These are not interchangeable trial counts or newly solved equations.

| Family | Enabled / configured | Reported work units | Completed batches |
|---|---:|---:|---:|
| Beal | 24 / 24 | 2,298,495,259 | 45,868 |
| almost-perfect | 0 / 1 | 0 | 0 |
| andrica | 0 / 1 | 0 | 0 |
| brocard | 1 / 1 | 16,623 | 7,832 |
| erdos-moser | 0 / 1 | 0 | 0 |
| factor-contributions | 1629 / 1629 | 323,565,738 | 45,866 |
| giuga | 1 / 1 | 57,842,117 | 15,121 |
| legendre | 1 / 1 | 5,002,059 | 14,905 |
| lehmer | 1 / 1 | 58,334,215 | 15,287 |
| magic-square-squares | 1 / 1 | 3,153,499,427 | 16,012 |
| odd-perfect | 0 / 1 | 0 | 0 |
| perfect-cuboid | 1 / 1 | 930,138,482 | 21,724 |
| quasiperfect | 0 / 1 | 0 | 0 |
| rational-square-distances | 1 / 1 | 2,802,058,869 | 15,747 |
| three-body | 1 / 1 | 805,701 | 153,283 |
| three-cubes | 1 / 1 | 18,248,457,763 | 21,886 |

The watch runs every two hours through **2026-10-16T18:05:07Z**, provided the PC is awake and Codex is running.

Health issues: none observed in this sample.

Counts record this application's computational work, not distinct unsolved problems, unique inputs, frontier coverage or proofs. Numerical candidates are approximate experiments. Updates are two-hour snapshots while the local PC and Codex are available, not a live telemetry feed.

See [methodology](METHODOLOGY.md), [machine-readable progress](progress.json), and [snapshot history](progress/history/).
