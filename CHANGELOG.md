# Changelog

## v2.7.3-vegas-stable (2026-06-08) — Stable Release

Community DXVK build for Adreno Android Emulation (Star Emulator / Winlator).

### Features
- Master Switch (dxvk.enableStarProfile) — Auto/True/False
- Auto Tier Detection — Adreno 5xx→8xx into 3 performance tiers
- FSR 1.0 Upscaler — Async compute upscale, zero CPU stall
- Frame Generation — 3-pass motion-compensated
- Adaptive Governor — TBDR-inverted threshold tuning
- Live HUD Colors — Frametime graph by perf state
- Dynamic VRAM — 40% of system RAM
- Driver Safeguards — Zero-init, HAAE, QCOM ext mgmt

### Build Details
- Commit (private): ff4c1fe
- Branch: vegas
- Target: Android aarch64 (Adreno via Turnip/Mesa)

---

## v2.7.3-vegas (2026-06-06) — Initial Community Release

Community DXVK build for Adreno Android Emulation (Star Emulator / Winlator).

### Features
- Adreno Tier Governor — Auto‑classifies GPU, tunes draw‑call submission
- VegasHud Overlay — Real‑time tier, GPU load, frame time, perf state
- FSR 1.0 Upscaler — Compute‑based spatial upscaler
- 3‑Pass Frame Generation — Frame interpolation for smoother motion
- ARM64 Compiler Cap — Max 4 shader compiler threads on big.LITTLE
- Bind‑Skip Optimization — Reduces redundant descriptor binds
- Periodic Shader Cache Flush — 60s incremental cache flush
- Aspect Ratio Fix — Proper D3D9 aspect on modern displays
- HAAE Frame Pacing — Prevents submission bursts on Adreno
- GPU Persona Masking — Reports as GTX 1050 Ti / 1070 / RTX 3060
- VRAM Auto‑Tuning — 40% of system RAM reported as VRAM

### Build Details
- Commit (private): ff4c1fe
- Branch: vegas
- Target: Android aarch64 (Adreno via Turnip/Mesa)
