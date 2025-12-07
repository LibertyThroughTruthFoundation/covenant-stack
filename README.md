# The Covenant Stack

> **Building the Kingdom's Digital Infrastructure: A comprehensive framework for sovereign technology, covenant community, and divine order in the digital age.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GrapheneOS](https://img.shields.io/badge/GrapheneOS-Aligned-blue.svg)](https://grapheneos.org)
[![FUTO](https://img.shields.io/badge/FUTO-Integrated-green.svg)](https://futo.org)
[![SimpleX](https://img.shields.io/badge/SimpleX-Enabled-purple.svg)](https://simplex.chat)

## The Mission

For too long, the sovereignty movement has been fragmented - excellent tools built in isolation, unable to work together, lacking the theological framework to guide their use toward divine purposes.

**The Covenant Stack changes this.** We are not building from scratch - we are **assembling prepared components** into a unified, consecrated whole. We are the **integrators, the theologians, the unifiers**.

> *"They build the sword; you consecrate it for the King's service."*

## The Four Pillars of Sovereignty

### 1. Absolute Offline Capability

Applications must be fully functional without network connection. The network is for synchronization only, never for operation.

### 2. User-Controlled Data

All data resides locally on the user's device. The "cloud" is merely a mirror, never the primary source of truth.

### 3. No External Dependencies

The runtime must not phone home to Google, Mozilla, or any adversarial entity for fonts, APIs, or services.

### 4. Covenant Integration

Designed from the start to integrate with Covenant Wallet and the broader NationOS stack with theological foundation.

## The Stack Components

### Layer 1: Covenant Mobile Standard

**GrapheneOS + FUTO Tools = The First Truly Sovereign Mobile Device**

The Covenant Mobile Standard transforms your mobile device from a surveillance tool into a sovereign node. It combines:

- **GrapheneOS**: Hardware-backed security with Titan M2 chip, verified boot, and bootloader re-locking
- **FUTO Tools**: 100% offline keyboard, GrayJay media platform, Harbor/Polycentric identity
- **Permission Doctrine**: Device-level firewall that eliminates the primary attack vector

**The Result**: A secure communication hub AND financial terminal in one device.

[Read the Complete Mobile Standard →](docs/mobile-standard.md)

### Layer 2: Sovereign PWA Runtime

**Offline-First Application Platform That Replaces Browsers**

We're not building a better browser. We're building a **sovereign application runtime** - a platform where covenant-aligned PWAs run offline-first, store data locally, and never phone home.

Inspired by SilverBullet's architecture, the runtime provides:

- **Service Worker Layer**: Cache-first strategy for complete offline operation
- **Local Storage Layer**: IndexedDB for all application data
- **Sync Engine**: Optional encrypted sync to self-hosted servers
- **Identity Layer**: Polycentric integration for cryptographic authentication

[Explore the PWA Runtime Architecture →](docs/pwa-runtime.md)

### Layer 3: FUTO Integration

**Leveraging Best-in-Class Sovereign Tools**

FUTO (Fund for Useful Technology Optimization) is building the exact infrastructure we need for sovereignty. Their Five Pillars align perfectly with our mission:

1. **Source First / Open Source**: Auditable, verifiable code
2. **Self Manageable Servers**: True data sovereignty through self-hosting
3. **Sovereign Identity**: Public/private key cryptography, no central servers
4. **Open Databases**: No vendor lock-in, free data migration
5. **End-to-End Encryption**: Servers cannot read user data

**The Three Essential Tools**:

- **FUTO Keyboard**: 100% offline with on-device AI voice input
- **GrayJay**: Content aggregation with offline download capabilities
- **Harbor (Polycentric)**: Decentralized identity using cryptographic keys

[See the Complete FUTO Integration Strategy →](docs/futo-integration.md)

## Quick Start Guide

### What You Need

- **Google Pixel Device** (Pixel 6 or newer, Pixel 9 recommended)
- **Computer with Chrome/Chromium** (for GrapheneOS installation)
- **1-2 Hours of Focused Time** (installation cannot be interrupted)

### Week 1: Build Your Sovereign Device

#### Day 1-2: Factory Reset Pixel

1. Power off device completely
2. Hold **Volume Down** + **Power** until bootloader menu appears
3. Navigate to **Recovery mode**, select **Wipe data/factory reset**
4. Skip all Google account setup - reach home screen without signing in

#### Day 3-4: Install GrapheneOS

1. Enable **Developer Options** on Pixel (tap Build number 7 times)
2. Enable **OEM unlocking** and **USB debugging**
3. On computer, open Chrome and go to **grapheneos.org/install**
4. Follow WebUSB installer instructions precisely
5. The installer will unlock bootloader → flash GrapheneOS → **re-lock bootloader**

**Critical**: The bootloader MUST be re-locked for hardware-backed security.

#### Day 5: Configure Permission Doctrine

1. Go through GrapheneOS setup wizard
2. **Deny all permissions by default**
3. **Skip all Google services**
4. Set strong device PIN/password (12+ characters)
5. Configure **Duress PIN** (wipes device if entered under coercion)

#### Day 6-7: Install The 4 Essential Apps

Via Obtainium (F-Droid alternative):

1. **Covenant Wallet** - Your sovereign bank (coming soon)
2. **SimpleX Chat** - Encrypted messaging with no identifiers
3. **Vanadium Browser** - Pre-installed hardened browser
4. **FUTO Keyboard** - 100% offline keyboard with voice input

[Complete Installation Guide →](docs/quick-start.md)

## The Permission Doctrine

This is the master key to safety. GrapheneOS allows you to create a device-level firewall by revoking network access from most apps.

| App | Network | Camera | Microphone | Location |
|-----|---------|--------|------------|----------|
| Covenant Wallet | ✅ Always | ❌ Denied | ❌ Denied | ❌ Denied |
| SimpleX Chat | ✅ Always | 📷 Optional | 🎤 Optional | ❌ Denied |
| Vanadium Browser | ✅ Always | 📷 Optional | 🎤 Optional | ❌ Denied |
| FUTO Keyboard | ❌ Denied | ❌ Denied | 🎤 Voice Only | ❌ Denied |
| **All Other Apps** | ❌ Denied | ❌ Denied | ❌ Denied | ❌ Denied |

**The Result**: Your device becomes a firewall. The wallet can talk to the blockchain. Other apps cannot talk to anything. This eliminates the threat vector.

## Implementation Roadmap

### Weeks 1-2: Pixel 9 Test Lab
Install GrapheneOS, configure FUTO stack, test sovereign mobile device prototype

### Weeks 3-6: Sovereign Mobile Standard
Perfect configuration, deploy to Pixel 10 XL, validate with community

### Months 2-4: Covenant PWA Runtime
Build application platform, integrate Polycentric identity, deploy first PWA (Wallet)

### Months 5-12: Complete Covenant Stack
Build Communications, Content, Governance, and Commerce PWAs

### Months 13-18: Ecosystem Growth
Developer onboarding, community apps, optimization, and scaling

## Documentation

Comprehensive documentation is available in the `docs/` directory:

- [Quick Start Guide](docs/quick-start.md) - Get started in one week
- [Covenant Mobile Standard](docs/mobile-standard.md) - Complete mobile architecture
- [Sovereign PWA Runtime](docs/pwa-runtime.md) - Application platform design
- [FUTO Integration](docs/futo-integration.md) - Tool integration strategy
- [Security Model](docs/security.md) - Threat model and protections
- [Troubleshooting](docs/troubleshooting.md) - Common issues and solutions

## Technology Stack

### Mobile Layer
- **OS**: GrapheneOS (Android-based, hardened)
- **Security**: Titan M2 chip, verified boot
- **Apps**: Obtainium, SimpleX, FUTO tools

### Application Layer
- **Runtime**: Custom PWA runtime (SilverBullet-inspired)
- **Framework**: React 19 or Svelte 5
- **Storage**: IndexedDB (Dexie.js or PouchDB)
- **Identity**: Polycentric (FUTO's decentralized identity)

### Infrastructure Layer
- **Blockchain**: PulseChain, Ethereum
- **Storage**: IPFS, self-hosted servers
- **Sync**: CouchDB replication or custom CRDT-based
- **Encryption**: Web Crypto API (AES-256-GCM)

## Contributing

We welcome contributions from the covenant community. Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Community

- **Website**: [libertythroughtruth.org](https://libertythroughtruth.org)
- **Documentation**: [docs.libertythroughtruth.org](https://docs.libertythroughtruth.org)
- **X (Twitter)**: [@LTTFoundation](https://x.com/LTTFoundation)
- **SimpleX**: [Join our private group](https://simplex.chat/contact#/?v=1&smp=smp%3A%2F%2F...)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built with support from the Liberty Through Truth Foundation community and inspired by the excellent work of:

- **GrapheneOS Team** - For building the most secure mobile OS
- **FUTO** - For creating sovereignty-focused tools
- **SimpleX Chat** - For truly private communication
- **SilverBullet** - For demonstrating local-first architecture

---

**Liberty Through Truth Foundation** - Building the Kingdom's digital infrastructure, one sovereign device at a time.

> *"We are not building from scratch. We are assembling prepared components. We are the integrators, the theologians, the unifiers."*

## Related Resources

### The 95 Theses of Covenant Finance

Before building covenant technology, we must understand what we're building against. The **[95 Theses of Covenant Finance](https://github.com/LibertyThroughTruthFoundation/95-theses-covenant-finance)** exposes the hollow slogans of modern crypto and replaces them with covenant truth.

**Key Theses:**
- Thesis #1: "Code is Law" → "Covenant is Law"
- Thesis #2: "Trustless Systems" → "Trust-Worthy Systems"
- Thesis #4: "Financial Sovereignty" → "Covenant Stewardship"
- Thesis #95: "In Code We Trust" → "In God We Trust"

Read the complete manifesto: https://github.com/LibertyThroughTruthFoundation/95-theses-covenant-finance

