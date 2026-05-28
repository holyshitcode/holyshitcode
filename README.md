> A programmer who asks "why," and digs until the source answers.

**Jun Yeong Kim** · CS @ Jeonju University · Korea

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-FF6B35?style=flat-square&logo=linuxfoundation&logoColor=white)
![JVM](https://img.shields.io/badge/JVM-007396?style=flat-square&logo=openjdk&logoColor=white)

Drawn to systems programming — kernels, tracers, runtimes, anything where the abstraction leaks.

---

## Upstream patches

| Project | ★ | Merged |
|---|---|---|
| [namhyung/uftrace](https://github.com/namhyung/uftrace) | 3.4k | `--srcline` callsite resolution [#2047](https://github.com/namhyung/uftrace/pull/2047) · per-fn CPU field [#2039](https://github.com/namhyung/uftrace/pull/2039) · graph min/max/avg fields [#1999](https://github.com/namhyung/uftrace/pull/1999) · report timestamp range [#2032](https://github.com/namhyung/uftrace/pull/2032) · lost-diff fix in `mcount` [#2048](https://github.com/namhyung/uftrace/pull/2048) · _+6 more_ |
| [apache/airflow](https://github.com/apache/airflow) | 45k | Task SDK `Variable.keys()` [#66022](https://github.com/apache/airflow/pull/66022) · datetime paste in picker [#66251](https://github.com/apache/airflow/pull/66251) · Ko i18n [#66267](https://github.com/apache/airflow/pull/66267) |
| [valkey-io/valkey](https://github.com/valkey-io/valkey) | 26k | Cluster test framework migration [#3382](https://github.com/valkey-io/valkey/pull/3382) |
| [goatshriek/stumpless](https://github.com/goatshriek/stumpless) | 521 | `struct to_string` [#501](https://github.com/goatshriek/stumpless/pull/501) · Ko i18n [#502](https://github.com/goatshriek/stumpless/pull/502) |

## Building

**[VectorGuard](https://github.com/Cozymori/VectorGuard)** — eBPF runtime security daemon. Rule-engine on the fast path, behavior-embedding + Qdrant on the slow path, `bpf_send_signal(SIGKILL)` for kernel-level blocking. `Rust` · `aya` · `LSM`

**[VectorWave](https://github.com/Cozymori/VectorWave)** ⭐22 — Decorator-based framework for self-healing LLM apps. Semantic cache via HNSW, agent-authored fix PRs on runtime error. `Python` · `PyO3` · `Weaviate`

**[TransparentClass](https://plugins.jetbrains.com/plugin/28542-transparentclass)** — IntelliJ plugin. Surfaces inherited non-private members inline so you can read a subclass without jumping files. `Kotlin` · `IntelliJ PSI`

## Systems-side toys

- **[Renux](https://github.com/junyeong0619/Renux)** — Remote Linux state manager. `C++`
- **[cluster-classcache](https://github.com/junyeong0619/cluster-classcache)** — Distributed bytecode-transformation cache for JVM clusters. `Go`
- **[MyOS](https://github.com/junyeong0619/MyOS)** — Toy OS with virtual memory. `C++`
- **[Alfa](https://github.com/junyeong0619/Alfa)** — Auto log filtering agent. `Java`

---

📫 [junyeonggim5@gmail.com](mailto:junyeonggim5@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/jun0619)
