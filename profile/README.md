# Welcome to Sendr!

**Sendr** is an open‑source, template‑based network traffic generator for testing and emulation.

---

## Ecosystem Overview

Sendr is modular: the core engine is separate from the user interfaces.

- [`sendr-core`](https://github.com/sendrhq/sendr-core) — C++20 engine: templates, validation, packet assembly. **Active development.**
- [`sendr-gtk`](https://github.com/sendrhq/sendr-gtk) — GTK4 + LibAdwaita UI for configuration and preview. **Coming soon.**
- [`sendr-tui`](https://github.com/sendrhq/sendr-tui) — Terminal UI for quick debugging and navigation. **Coming soon.**

This structure lets you develop and release components independently.

> 📦 Legacy project: [`UdpPacketGenerator`](https://github.com/Sendrhq/UdpPacketGenerator) is maintained in maintenance mode (no new features). It remains available as a simple UDP packet generator. All new development is focused on the Sendr ecosystem.

## License

MIT
