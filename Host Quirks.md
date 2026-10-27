---
categories: [Setups]
---

# Host Quirks

- Paramiko: bg = fire() (exec_command lalu close); sleep >60s in-session = idle-drop 10054 -> reconnect per check.
- `pkill -f` self-kill: pakai pattern bracket `[.]` + pisah call dari spawn.
- Hermes home Windows: `C:\Users\LENOVO X390\AppData\Local\hermes` (BUKAN hostname). Shell = git-bash/MSYS, sintaks POSIX.
- Built-in memory Hermes DIMATIKAN (2026-10-27) -> vault ini satu-satunya persistent memory.
