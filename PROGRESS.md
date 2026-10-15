# Equation Lab progress

Research project owner / requested result credit: **Ashley Kalkowski**.

Snapshot: **2026-10-15T06:30:05Z**. Engine checkpoint: 2026-10-15T06:29:46.7733183Z.

| Measure | Observed value |
|---|---:|
| Engine health | healthy |
| Enabled / configured instances | 1662 / 1667 |
| Enabled instances with a completed batch | 1662 |
| Worker limit / scheduled duty | 16 / 70% |
| Exact completions reported by engine | 0 |
| Exact results passing both local checkers | 0 |
| Numerical candidates recorded (not proofs) | 1758 |
| Scheduled checks completed / planned | 0 / 18 |
| Missed scheduled checks | 0 |

**Novelty and external acceptance are assessed separately. No discovery is established by this tracker.**

The engine automatically stops scheduling an exact completion. After independent exact verification, the monitor also disables that target and preserves its evidence.

## Work by family

Each counter uses its adapter's work units. These are not interchangeable trial counts or newly solved equations.

| Family | Enabled / configured | Reported work units | Completed batches |
|---|---:|---:|---:|
| Beal | 24 / 24 | 510,255,431 | 10,372 |
| almost-perfect | 0 / 1 | 0 | 0 |
| andrica | 0 / 1 | 0 | 0 |
| brocard | 1 / 1 | 9,863 | 1,828 |
| erdos-moser | 0 / 1 | 0 | 0 |
| factor-contributions | 1629 / 1629 | 73,941,148 | 10,371 |
| giuga | 1 / 1 | 14,685,459 | 2,316 |
| legendre | 1 / 1 | 1,741,716 | 2,293 |
| lehmer | 1 / 1 | 14,835,504 | 2,340 |
| magic-square-squares | 1 / 1 | 541,474,267 | 3,042 |
| odd-perfect | 0 / 1 | 0 | 0 |
| perfect-cuboid | 1 / 1 | 472,873,467 | 8,739 |
| quasiperfect | 0 / 1 | 0 | 0 |
| rational-square-distances | 1 / 1 | 453,697,686 | 2,999 |
| three-body | 1 / 1 | 632,063 | 117,791 |
| three-cubes | 1 / 1 | 9,574,816,977 | 8,762 |

The watch runs every two hours through **2026-10-16T18:05:07Z**, provided the PC is awake and Codex is running.

Health issues: none observed in this sample.

Counts record this application's computational work, not distinct unsolved problems, unique inputs, frontier coverage or proofs. Numerical candidates are approximate experiments. Updates are two-hour snapshots while the local PC and Codex are available, not a live telemetry feed.

See [methodology](METHODOLOGY.md), [machine-readable progress](progress.json), and [snapshot history](progress/history/).
