# Indie-Sync for Obsidian

Sync your Obsidian vaults across devices with **end-to-end encryption**. Privacy-focused, usage-based pricing.

## Features

- **End-to-End Encryption**: Your notes are encrypted before leaving your device. We can't read them.
- **Sync Everything**: Notes, attachments, settings, plugins, themes, and snippets.
- **Version History**: 12 months of version history with auto-merge conflict resolution.
- **Usage-Based Pricing**: Pay only for what you use. First 10MB free, then $0.10 per 100MB/month.
- **Unlimited Devices**: Sync across as many devices as you want.
- **Unlimited Vaults**: Sync all your vaults within your storage quota.

## Pricing

| Usage | Monthly Cost |
|-------|--------------|
| 10MB | Free |
| 100MB | $0.10 |
| 500MB | $0.50 |
| 1GB | $1.00 |
| 5GB | $5.00 |

That's **$1/GB/month**. No subscriptions, no tiers - just pay for storage.

## Installation

1. Open Obsidian Settings
2. Go to Community Plugins and disable Safe Mode
3. Click Browse and search for "Indie-Sync"
4. Install the plugin and enable it
5. Create an account and start syncing!

## How It Works

1. **You set a password** - This is used to derive your encryption key
2. **Files are encrypted locally** - Using XChaCha20-Poly1305 (military-grade encryption)
3. **Encrypted blobs are uploaded** - We only see encrypted data
4. **Other devices download and decrypt** - Using the same password

We **never** see your notes, file names, or folder structure. Everything is encrypted.

## Privacy & Security

- **E2E Encryption**: XChaCha20-Poly1305 with Argon2id key derivation
- **Zero-Knowledge**: We can't read your notes even if we wanted to
- **Open Source**: The plugin code is fully open source for audit
- **No Tracking**: We don't track your usage beyond storage metering

## Support

- [Documentation](https://indie-sync.com/docs)
- [GitHub Issues](https://github.com/pubit/indie-sync-plugin/issues)
- [Email](mailto:support@indie-sync.com)

## License

MIT License - see [LICENSE](LICENSE) for details.
