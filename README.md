# Hermes Memory Vault

Persistent memory untuk Hermes Agent — pengganti built-in memory (dimatikan via `memory.memory_enabled: false`).

**Path lokal:** `C:\Users\LENOVO X390\AppData\Local\hermes\vault\`
**Kontrak:** Hermes baca/tulis note di sini langsung (file tools), bukan tool `memory`. Perubahan penting → git commit. Jangan commit kredensial mentah.

## Routing — mulai dari MOC

| Kategori | MOC | Isi |
|---|---|---|
| Profil & preferensi user | [[User]] | siapa user, gaya komunikasi, preferensi tetap |
| Personas & instruksi agent | [[Personas]] | persona lintas-sesi (mis. jailbreak-agent spec) |
| Web3 & mining ops | [[Web3]] | Daytona farm, Warpstations, LightVela, farm ops |
| Intel & riset | [[Intel]] | temuan riset, recon, analisis |
| Setups & environment | [[Setups]] | toolchain, host quirk, infra |
| Maintenance | [[Maintenance]] | perawatan sistem, checkpoint |

## Konvensi

- Note isi hidup di **root vault**, frontmatter `categories: [..]`.
- MOC di `Categories/` = index per kategori. Note baru WAJIB dilink dari >=1 MOC supaya bisa di-recall.
- Update note eksisting di tempat; jangan duplikat.
- Recall sebelum task non-trivial: search vault + skill domain terkait.
