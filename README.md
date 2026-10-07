# Zero7even Launcher

Private source repository for the official Zero7even desktop launcher.

The launcher is the user-facing entry point to the Zero7even Platform and is responsible for account access, Experience discovery, installation and repair, runtime management, updates, server launching, and future social/platform integrations.

## Status

Active development.

The current launcher implementation is being completed in the existing local development workspace before the full source is moved into this repository.

## Intended responsibilities

- Zero7even account sign-in
- Experience library and discovery
- Luanti runtime preparation and verification
- Experience installation, repair, and updates
- Server selection and launch flow
- Platform presence, friends, notifications, and entitlements integration
- Secure local configuration and account/session handling
- Auto-update and release-channel integration

## Security

Do not commit production credentials, OAuth secrets, signing keys, private certificates, or other secrets.

Environment-specific secrets must remain outside source control.

## Related repositories

- `zero7even-platform-api` — private Zero7even backend
- `zero7even-services` — Luanti SDK and platform service integration
- `zero7even-launcher-releases` — public launcher binaries and update metadata

---

Copyright © Zero7even.
