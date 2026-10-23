# Autentic Connector

Connect your Claude or Codex subscription to [Autentic](https://app.autentic.ai) from your Mac.

## Production / Staging selector beta

[Download the selector beta (Apple Silicon)](https://github.com/autenticai/autentic-connector-releases/releases/download/connector-v0.0.1-selector.1/Autentic-Connector-arm64.dmg)

One app with separate Production and Staging sessions and a visible environment label. The selector is restricted to verified superadmins. A new installation starts in Production. The selector requires the production backend rollout and an explicitly linked production account; deploying Staging alone does not unlock it. See the [release notes and checksums](https://github.com/autenticai/autentic-connector-releases/releases/tag/connector-v0.0.1-selector.1) before installing.

## Earlier environment-specific builds

[Download for production (Apple Silicon)](https://github.com/autenticai/autentic-connector-releases/releases/download/connector-v0.0.1/Autentic-Connector-arm64.dmg)

[Download for staging (Apple Silicon)](https://github.com/autenticai/autentic-connector-releases/releases/download/connector-v0.0.1-staging.1/Autentic-Connector-arm64.dmg) connects to staging.autentic.ai.

Requires an Apple Silicon Mac running macOS 14 or later and an Autentic account with connector access.

Open the disk image and drag Autentic Connector into Applications. Open the installed app, link your Autentic account, then connect your subscription.

Updates are installed manually. Choose Quit in the connector's menu before replacing the app; closing its window keeps it running.

Each release includes checksums and an artifact provenance manifest. This repository distributes installers; it does not contain the application source.
