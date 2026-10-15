# Equation Lab progress

Research project owner / requested result credit: **Ashley Kalkowski**.

Snapshot: **2026-10-15T14:05:53Z**. Engine checkpoint: 2026-10-15T14:05:40.5504796Z.

| Measure | Observed value |
|---|---:|
| Engine health | healthy |
| Enabled / configured instances | 1662 / 1667 |
| Enabled instances with a completed batch | 1662 |
| Worker limit / scheduled duty | 16 / 70% |
| Exact completions reported by engine | 0 |
| Exact results passing both local checkers | 0 |
| Numerical candidates recorded (not proofs) | 2227 |
| Scheduled checks completed / planned | 4 / 18 |
| Missed scheduled checks | 0 |
| Completed observations waiting for export | 0 |

**Novelty and external acceptance are assessed separately. No discovery is established by this tracker.**

The engine automatically stops scheduling an exact completion. After independent exact verification, the monitor also disables that target and preserves its evidence.

## Work by family

Each counter uses its adapter's work units. These are not interchangeable trial counts or newly solved equations.

| Family | Enabled / configured | Reported work units | Completed batches |
|---|---:|---:|---:|
| Beal | 24 / 24 | 4,457,852,539 | 84,586 |
| almost-perfect | 0 / 1 | 0 | 0 |
| andrica | 0 / 1 | 0 | 0 |
| brocard | 1 / 1 | 20,561 | 11,770 |
| erdos-moser | 0 / 1 | 0 | 0 |
| factor-contributions | 1629 / 1629 | 621,673,983 | 84,585 |
| giuga | 1 / 1 | 96,677,002 | 29,530 |
| legendre | 1 / 1 | 7,480,068 | 29,136 |
| lehmer | 1 / 1 | 97,371,979 | 29,835 |
| magic-square-squares | 1 / 1 | 6,475,347,157 | 30,583 |
| odd-perfect | 0 / 1 | 0 | 0 |
| perfect-cuboid | 1 / 1 | 1,493,139,080 | 36,288 |
| quasiperfect | 0 / 1 | 0 | 0 |
| rational-square-distances | 1 / 1 | 5,861,431,588 | 30,020 |
| three-body | 1 / 1 | 995,215 | 192,003 |
| three-cubes | 1 / 1 | 29,008,534,293 | 36,555 |

The watch runs every two hours through **2026-10-16T18:05:07Z**, provided the PC is awake and Codex is running.

Health issues: none observed in this sample.

Counts record this application's computational work, not distinct unsolved problems, unique inputs, frontier coverage or proofs. Numerical candidates are approximate experiments. Updates are two-hour snapshots while the local PC and Codex are available, not a live telemetry feed.

See [methodology](METHODOLOGY.md), [machine-readable progress](progress.json), and [snapshot history](progress/history/).
