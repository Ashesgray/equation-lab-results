# Equation Lab progress

Research project owner / requested result credit: **Ashley Kalkowski**.

Snapshot: **2026-10-15T12:07:13Z**. Engine checkpoint: 2026-10-15T12:07:05.4950731Z.

| Measure | Observed value |
|---|---:|
| Engine health | healthy |
| Enabled / configured instances | 1662 / 1667 |
| Enabled instances with a completed batch | 1662 |
| Worker limit / scheduled duty | 16 / 70% |
| Exact completions reported by engine | 0 |
| Exact results passing both local checkers | 0 |
| Numerical candidates recorded (not proofs) | 2105 |
| Scheduled checks completed / planned | 3 / 18 |
| Missed scheduled checks | 0 |
| Completed observations waiting for export | 0 |

**Novelty and external acceptance are assessed separately. No discovery is established by this tracker.**

The engine automatically stops scheduling an exact completion. After independent exact verification, the monitor also disables that target and preserves its evidence.

## Work by family

Each counter uses its adapter's work units. These are not interchangeable trial counts or newly solved equations.

| Family | Enabled / configured | Reported work units | Completed batches |
|---|---:|---:|---:|
| Beal | 24 / 24 | 3,399,577,514 | 65,319 |
| almost-perfect | 0 / 1 | 0 | 0 |
| andrica | 0 / 1 | 0 | 0 |
| brocard | 1 / 1 | 18,830 | 10,039 |
| erdos-moser | 0 / 1 | 0 | 0 |
| factor-contributions | 1629 / 1629 | 473,606,048 | 65,318 |
| giuga | 1 / 1 | 78,790,105 | 22,468 |
| legendre | 1 / 1 | 6,376,895 | 22,165 |
| lehmer | 1 / 1 | 79,354,331 | 22,697 |
| magic-square-squares | 1 / 1 | 4,853,159,572 | 23,434 |
| odd-perfect | 0 / 1 | 0 | 0 |
| perfect-cuboid | 1 / 1 | 1,218,738,660 | 29,137 |
| quasiperfect | 0 / 1 | 0 | 0 |
| rational-square-distances | 1 / 1 | 4,380,167,843 | 23,045 |
| three-body | 1 / 1 | 900,870 | 172,735 |
| three-cubes | 1 / 1 | 23,760,798,707 | 29,344 |

The watch runs every two hours through **2026-10-16T18:05:07Z**, provided the PC is awake and Codex is running.

Health issues: none observed in this sample.

Counts record this application's computational work, not distinct unsolved problems, unique inputs, frontier coverage or proofs. Numerical candidates are approximate experiments. Updates are two-hour snapshots while the local PC and Codex are available, not a live telemetry feed.

See [methodology](METHODOLOGY.md), [machine-readable progress](progress.json), and [snapshot history](progress/history/).
