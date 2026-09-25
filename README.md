# Pockos: Idle RPG downloads

Owner-approved installers and update manifests only. The game source and player saves are not hosted here. New builds are published manually, not automatically.

## Windows Dev updater test

This is an experimental **Dev** release, not a Public game update. Dev and Public keep separate saves and account profiles.

1. Export a `.pockos` backup from your current Dev game, then close it.
2. Install [Dev 0.47.2](https://github.com/sadsoundfx/pockos-releases/releases/download/dev-0.47.2/Pockos-Dev-0.47.2-x64-setup.exe).
3. Open Settings > Game updates > Check for updates. The Dev feed offers 0.47.3 once commissioning is complete.
4. Confirm the update, then check Settings says 0.47.3 and your progress is intact.

Older portable 0.47.0/0.47.1 builds need this one-time installer; they cannot install updates themselves. The current test supports Windows x64 only.

Updates use cryptographic signatures and version verification. These test installers are **not Windows Authenticode signed**, so reputation warnings may still appear. Do not disable antivirus protection. Report any blocked launch or update to the developer.

Only the Dev update channel is configured. Social minimum-version enforcement is a separate rollout step; publishing a release does not turn it on. The offline game, save exports and existing expedition recovery are intended to remain available during online version restrictions.
