# Quick Start Guide

Get started with the Covenant Mobile Standard in one week.

## The Essence

This is not a "phone" - it is a **Covenant Communication and Financial Terminal**.

### What It Does

- Securely holds and transacts cryptocurrency
- Sends encrypted, untraceable messages
- Accesses essential web tools securely
- Invisible to surveillance grid

### What It Doesn't Do

- ❌ Track your location
- ❌ Leak your data
- ❌ Phone home to Google
- ❌ Allow app surveillance

## What You Need

### Google Pixel Device

Pixel 6 or newer (Pixel 9 recommended for testing, Pixel 10 XL for production). Only Google Pixels have the hardware-backed security (Titan M2 chip) required for true sovereignty.

### Computer with Chrome/Chromium

For GrapheneOS installation via WebUSB. Any modern computer running Chrome, Chromium, or Brave browser.

### 1-2 Hours of Focused Time

The installation process requires attention and cannot be interrupted. Set aside dedicated time.

## Week 1: Build Your Sovereign Device

### Day 1-2: Factory Reset

**WARNING**: This will erase all data on the device. Back up anything important first.

1. Power off Pixel completely
2. Hold **Volume Down** + **Power** until bootloader menu appears
3. Navigate to **Recovery mode** using volume buttons, press Power to select
4. Press and hold **Power**, tap **Volume Up** once
5. Navigate to **Wipe data/factory reset**, confirm
6. Select **Reboot system now**
7. **Skip all Google account setup** - reach home screen without signing in

### Day 3-4: Install GrapheneOS

This is where the transformation happens. GrapheneOS provides hardware-backed security that makes sovereign mobile possible.

1. On Pixel, go to **Settings → About phone**, tap **Build number** 7 times to enable Developer Options
2. Go to **Settings → System → Developer options**
3. Enable **OEM unlocking**
4. Enable **USB debugging**
5. On computer, open Chrome/Chromium and go to **grapheneos.org/install**
6. Connect Pixel to computer via USB cable
7. Follow the WebUSB installer instructions precisely
8. The installer will: unlock bootloader → flash GrapheneOS → **re-lock bootloader** (critical for security)
9. Reboot device when complete

**Important**: The bootloader MUST be re-locked after installation. This is what provides verified boot and hardware-backed security.

### Day 5: Initial Configuration

Configure GrapheneOS with the Permission Doctrine - the foundation of device-level security.

1. Go through GrapheneOS setup wizard
2. **Deny all permissions by default**
3. **Skip all Google services**
4. Set strong device PIN/password (12+ characters recommended)
5. Enable biometric authentication (fingerprint)
6. Configure **Duress PIN** (Settings → Security → Duress PIN) - this wipes device if entered under coercion

### Day 6-7: Install Essential Apps

Install only the 4 essential apps via Obtainium. This is the complete sovereign stack.

#### Step 1: Install Obtainium

1. Open Vanadium browser (GrapheneOS default)
2. Go to **github.com/ImranR98/Obtainium/releases**
3. Download latest Obtainium APK
4. Install Obtainium (allow installation from Vanadium when prompted)

#### Step 2: Install The 4 Essential Apps

##### 1. Covenant Wallet

Your sovereign bank - secure cryptocurrency storage and transactions.

*Coming soon - check covenant repository*

##### 2. SimpleX Chat

Encrypted messaging with no identifiers - truly private communication.

- Repository: `github.com/simplex-chat/simplex-chat`
- Add to Obtainium and install

##### 3. Vanadium Browser

Already installed - GrapheneOS's hardened browser for essential web access.

✓ Pre-installed

##### 4. FUTO Keyboard (Optional)

100% offline keyboard with voice input - no data collection.

- Repository: `github.com/futo-org/android-keyboard`
- Add to Obtainium and install

## The Permission Doctrine (Critical)

This is the master key to safety. GrapheneOS allows you to create a device-level firewall by revoking network access from most apps.

### Permission Matrix

| App | Network | Camera | Microphone | Location |
|-----|---------|--------|------------|----------|
| Covenant Wallet | ✅ | ❌ | ❌ | ❌ |
| SimpleX Chat | ✅ | 📷 | 🎤 | ❌ |
| Vanadium Browser | ✅ | 📷 | 🎤 | ❌ |
| FUTO Keyboard | ❌ | ❌ | 🎤 | ❌ |
| All Other Apps | ❌ | ❌ | ❌ | ❌ |

✅ = Always granted | ❌ = Always denied | 📷🎤 = Optional (grant temporarily when needed)

### The Strategy

Covenant Wallet needs network to broadcast transactions. Vanadium needs network for dApp access. SimpleX needs network for messaging. Everything else has network permanently revoked.

### The Result

Your device becomes a firewall. The wallet can talk to the blockchain. Other apps cannot talk to anything. This eliminates the threat vector.

## Next Steps

Congratulations! You now have a Sovereign Mobile Device - a true Covenant Communication and Financial Terminal.

### Recommended Next Actions

1. **Test the configuration**: Verify all apps work as expected
2. **Configure SimpleX**: Set up encrypted communication channels
3. **Install Covenant Wallet**: When available, install and configure your sovereign bank
4. **Join the community**: Connect with other covenant members via SimpleX

### Advanced Configuration

- [Configure FUTO Keyboard voice input](futo-integration.md#keyboard-setup)
- [Set up self-hosted SimpleX server](mobile-standard.md#simplex-self-hosting)
- [Install GrayJay for content consumption](futo-integration.md#grayjay-setup)
- [Configure Polycentric identity](futo-integration.md#harbor-polycentric)

## Troubleshooting

### GrapheneOS Installation Issues

**Problem**: WebUSB installer doesn't detect device

**Solution**: 
- Try different USB cable (must be data cable, not charge-only)
- Use different USB port (USB 3.0 preferred)
- Disable USB debugging, re-enable, and try again

**Problem**: Bootloader won't unlock

**Solution**:
- Ensure OEM unlocking is enabled in Developer Options
- Some carriers lock bootloaders - check GrapheneOS compatibility list
- Wait 7 days after enabling OEM unlocking (carrier restriction)

### App Installation Issues

**Problem**: Obtainium won't install apps

**Solution**:
- Grant Obtainium permission to install unknown apps
- Check internet connection (needed for initial download)
- Verify repository URL is correct

**Problem**: FUTO Keyboard voice input not working

**Solution**:
- Grant microphone permission to FUTO Keyboard
- Download voice model in keyboard settings
- Ensure sufficient storage space (models are 50-200MB)

## Security Considerations

### What This Protects Against

- App-level surveillance and data exfiltration
- Network-level tracking and monitoring
- Malicious apps attempting to steal private keys
- Physical device theft (via encryption and duress PIN)
- Supply chain attacks (via verified boot)

### What It Doesn't Protect Against

- Targeted nation-state attacks with physical access
- Zero-day exploits in GrapheneOS itself (rare but possible)
- Social engineering attacks (phishing, impersonation)
- Compromise of the blockchain networks you interact with

### The Philosophy

Perfect security is impossible. The goal is to make surveillance and exploitation so difficult that you're not worth targeting. The Covenant Mobile Standard achieves this.

## Community Support

Need help? Connect with the covenant community:

- **SimpleX Group**: [Join our private support channel]
- **X (Twitter)**: [@LTTFoundation](https://x.com/LTTFoundation)
- **Documentation**: [docs.libertythroughtruth.org](https://docs.libertythroughtruth.org)

---

**You are now part of the sovereign movement. Welcome to the Kingdom's digital infrastructure.**
