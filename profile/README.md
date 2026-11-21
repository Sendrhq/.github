# Welcome to Datagram Forge!

**Datagram Forge** is an open‑source, template‑based network traffic generator for testing and emulation.

---

## Ecosystem Overview

DatagramForge is modular: the core engine is separate from the user interfaces.

- [`datforge-core`](https://github.com/DatagramForge/datforge-core) — C++20 engine: templates, validation, packet assembly. **Active development.**
- [`datforge-gtk`](https://github.com/DatagramForge/datforge-gtk) — GTK4 + LibAdwaita UI for configuration and preview. **Coming soon.**
- [`datforge-tui`](https://github.com/DatagramForge/datforge-tui) — Terminal UI for quick debugging and navigation. **Coming soon.**

This structure lets you develop and release components independently.

> 📦 Legacy project: [`UdpPacketGenerator`](https://github.com/DatagramForge/UdpPacketGenerator) is maintained in maintenance mode (no new features). It remains available as a simple UDP packet generator. All new development is focused on the Datagram Forge ecosystem.

## License

MIT
