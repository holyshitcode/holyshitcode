> A programmer who asks "why," and digs until the source answers.

**Jun Yeong Kim** · CS @ Jeonju University · Korea

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-FF6B35?style=flat-square&logo=linuxfoundation&logoColor=white)
![JVM](https://img.shields.io/badge/JVM-007396?style=flat-square&logo=openjdk&logoColor=white)

Drawn to systems programming — kernels, tracers, runtimes, anything where the abstraction leaks.

---

## Upstream patches

| Project | PR |
|---|---|
| [uftrace](https://github.com/namhyung/uftrace) | `feat` Show callsite location with `--srcline` (DWARF via libdw) — [#2047](https://github.com/namhyung/uftrace/pull/2047) |
| [uftrace](https://github.com/namhyung/uftrace) | `feat` Add `cpu` field for per-function CPU execution info — [#2039](https://github.com/namhyung/uftrace/pull/2039) |
| [uftrace](https://github.com/namhyung/uftrace) | `feat` Support min/max timestamp in `uftrace report` — [#2032](https://github.com/namhyung/uftrace/pull/2032) |
| [uftrace](https://github.com/namhyung/uftrace) | `feat` Graph fields (total/self avg, min, max) in `cmds` & `tui` — [#1999](https://github.com/namhyung/uftrace/pull/1999) |
| [uftrace](https://github.com/namhyung/uftrace) | `fix` Lost diff event from read trigger with argument tracing — [#2048](https://github.com/namhyung/uftrace/pull/2048) |
| [uftrace](https://github.com/namhyung/uftrace) | `fix` Build error in `elf_for_each_comment()` — [#2034](https://github.com/namhyung/uftrace/pull/2034) |
| [uftrace](https://github.com/namhyung/uftrace) | `fix` `htmlLabels` config value to boolean `true` (mermaid) — [#2036](https://github.com/namhyung/uftrace/pull/2036) |
| [uftrace](https://github.com/namhyung/uftrace) | `fix` Compiler warnings in `demangle` & `session` — [#2042](https://github.com/namhyung/uftrace/pull/2042) |
| [uftrace](https://github.com/namhyung/uftrace) | `ci` Exit code of nightly `check_commits` step — [#2046](https://github.com/namhyung/uftrace/pull/2046) |
| [uftrace](https://github.com/namhyung/uftrace) | `build` Support Rocky Linux 9 in install-deps — [#2002](https://github.com/namhyung/uftrace/pull/2002) |
| [uftrace](https://github.com/namhyung/uftrace) | `test` Filter `system_initialize_function` in t295 & t296 — [#2001](https://github.com/namhyung/uftrace/pull/2001) |
| [apache/airflow](https://github.com/apache/airflow) | `feat` Task SDK: `Variable.keys()` to list variable keys by prefix — [#66022](https://github.com/apache/airflow/pull/66022) |
| [apache/airflow](https://github.com/apache/airflow) | `fix` Allow pasting full datetime strings into date picker — [#66251](https://github.com/apache/airflow/pull/66251) |
| [apache/airflow](https://github.com/apache/airflow) | `i18n` Korean translation (May 2nd batch) — [#66267](https://github.com/apache/airflow/pull/66267) |
| [valkey](https://github.com/valkey-io/valkey) | `test` Migrate cluster tests to new framework, remove legacy files — [#3382](https://github.com/valkey-io/valkey/pull/3382) |
| [stumpless](https://github.com/goatshriek/stumpless) | `feat` `stumpless_entry_to_string` with format & empty-field tests — [#501](https://github.com/goatshriek/stumpless/pull/501) |
| [stumpless](https://github.com/goatshriek/stumpless) | `i18n` Korean translation for two defines — [#502](https://github.com/goatshriek/stumpless/pull/502) |

## Building

**[VectorGuard](https://github.com/Cozymori/VectorGuard)** — eBPF runtime security daemon. Rule-engine on the fast path, behavior-embedding + Qdrant on the slow path, `bpf_send_signal(SIGKILL)` for kernel-level blocking. `Rust` · `aya` · `LSM`

**[VectorWave](https://github.com/Cozymori/VectorWave)** ⭐22 — Decorator-based framework for self-healing LLM apps. Semantic cache via HNSW, agent-authored fix PRs on runtime error. `Python` · `PyO3` · `Weaviate`

**[TransparentClass](https://plugins.jetbrains.com/plugin/28542-transparentclass)** — IntelliJ plugin. Surfaces inherited non-private members inline so you can read a subclass without jumping files. `Kotlin` · `IntelliJ PSI`

## Systems-side toys

- **[Renux](https://github.com/junyeong0619/Renux)** — Remote Linux state manager. `C++`
- **[cluster-classcache](https://github.com/junyeong0619/cluster-classcache)** — Distributed bytecode-transformation cache for JVM clusters. `Go`
- **[Alfa](https://github.com/junyeong0619/Alfa)** — Auto log filtering agent. `Java`

---

📫 [junyeonggim5@gmail.com](mailto:junyeonggim5@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/jun0619)
