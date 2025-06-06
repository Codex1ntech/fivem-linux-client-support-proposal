# Proposal: FiveM Client Support for Linux

This repository outlines a formal community-driven proposal to introduce and support a native FiveM client for Linux-based operating systems.

## 🧩 Objective

While FiveM currently supports server-side development on Linux, client-side support is still limited to Windows. This proposal aims to:

- Reduce platform exclusivity
- Improve compatibility for Linux-based GTA V players (Proton, Wine, etc.)
- Offer developers and players a more flexible environment

## 📦 Proposed Implementation Paths

1. **Evaluate Dependencies**
   - Assess critical client-side dependencies (Rockstar Launcher, DirectX, etc.)
   - Identify components that would require native or compatibility-layer adaptations

2. **Proton/Wine Integration Layer**
   - Create community-maintained installation and optimization scripts for Proton
   - Benchmark performance/stability under various Linux distros

3. **Partial Native Client Feasibility**
   - Modular rewrite of specific FiveM client modules for potential Linux compatibility
   - Consider hybrid execution (native + Wine/Proton wrappers)

## 🌐 Community Reference

This proposal originates from an active request in the FiveM community forum:  
🔗 [Client Support for Linux - Community Request](https://forum.cfx.re/t/request-client-support-for-linux/5252078)

Feedback and collaborative contributions are welcome.

---

## ⚠️ Disclaimer

This repository is community-maintained and not affiliated with the official CFX.re team. This is a technical concept proposal intended to open discussion and experimentation.
