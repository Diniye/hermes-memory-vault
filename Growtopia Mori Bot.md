---
categories: [Web3, Setups]
---

# Growtopia Mori Bot

- Mori fork (CLOEI/Mori v2.0.1, Rust ENet) di `C:\Users\LENOVO X390\mori-bot`.
- Patch: identitas per-GrowID (`identities/<GrowID>.json` — hapus = ganti device), env `GT_COUNTRY` (default id).
- Exe `target/release/Mori.exe` headless, dashboard :3000. `scripts/autofarm.lua`, `README-OPERASI.md`.
- Toolchain: cargo OK, bun di `~/.bun/bin` (web perlu `bun run build`), node/npm absent.
- Windows: `taskkill -F -IM X.exe`; background `&` ditolak terminal -> background=true.
- Farm math: ftank r42 3hit grow 20h55m; pepper r47 4hit (3 pickaxe) grow 1d5h13m seed 1.22 self-expanding; root Lattice Fence cycle 6.1d, gem panen root ~103/soil (0.5-0.8M/bln/farm).
- ftank cap 200 -> farm7.lua place-break 150, state `farm7_<GrowID>.state`. 7 world/hari ~ 45-55k gem/world ~ 260-330k/hari/bot, WL 3000 gem.
