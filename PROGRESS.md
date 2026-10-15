# Equation Lab progress

Research project owner / requested result credit: **Ashley Kalkowski**.

Snapshot: **2026-10-15T08:05:52Z**. Engine checkpoint: 2026-10-15T08:05:45.9547216Z.

| Measure | Observed value |
|---|---:|
| Engine health | healthy |
| Enabled / configured instances | 1662 / 1667 |
| Enabled instances with a completed batch | 1662 |
| Worker limit / scheduled duty | 16 / 70% |
| Exact completions reported by engine | 0 |
| Exact results passing both local checkers | 0 |
| Numerical candidates recorded (not proofs) | 1859 |
| Scheduled checks completed / planned | 1 / 18 |
| Missed scheduled checks | 0 |
| Completed observations waiting for export | 0 |

**Novelty and external acceptance are assessed separately. No discovery is established by this tracker.**

The engine automatically stops scheduling an exact completion. After independent exact verification, the monitor also disables that target and preserves its evidence.

## Work by family

Each counter uses its adapter's work units. These are not interchangeable trial counts or newly solved equations.

| Family | Enabled / configured | Reported work units | Completed batches |
|---|---:|---:|---:|
| Beal | 24 / 24 | 1,300,929,668 | 26,121 |
| almost-perfect | 0 / 1 | 0 | 0 |
| andrica | 0 / 1 | 0 | 0 |
| brocard | 1 / 1 | 13,872 | 5,081 |
| erdos-moser | 0 / 1 | 0 | 0 |
| factor-contributions | 1629 / 1629 | 187,587,050 | 26,119 |
| giuga | 1 / 1 | 36,748,619 | 8,050 |
| legendre | 1 / 1 | 3,524,655 | 7,946 |
| lehmer | 1 / 1 | 37,077,579 | 8,141 |
| magic-square-squares | 1 / 1 | 1,699,345,981 | 8,845 |
| odd-perfect | 0 / 1 | 0 | 0 |
| perfect-cuboid | 1 / 1 | 677,400,774 | 14,531 |
| quasiperfect | 0 / 1 | 0 | 0 |
| rational-square-distances | 1 / 1 | 1,476,382,314 | 8,700 |
| three-body | 1 / 1 | 709,209 | 133,536 |
| three-cubes | 1 / 1 | 13,432,918,920 | 14,621 |

The watch runs every two hours through **2026-10-16T18:05:07Z**, provided the PC is awake and Codex is running.

Health issues: none observed in this sample.

Counts record this application's computational work, not distinct unsolved problems, unique inputs, frontier coverage or proofs. Numerical candidates are approximate experiments. Updates are two-hour snapshots while the local PC and Codex are available, not a live telemetry feed.

See [methodology](METHODOLOGY.md), [machine-readable progress](progress.json), and [snapshot history](progress/history/).
