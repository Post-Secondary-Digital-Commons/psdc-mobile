# Product Packages

This repository may use a Happy-style package workspace because these packages
form one mobile/web companion product and share a coordinated compatibility
release. They remain separate from Cloud, AI, Compute, Media, Social and desktop
Git histories.

| Package | Responsibility |
|---|---|
| `app` | Expo/React Native iOS, Android and web client |
| `agent-adapter` | Provider-neutral adapter to the Agent Session Contract |
| `cli` | Pairing and local-session command-line entry point |
| `relay-self-host` | Content-blind institution-hosted relay adapter |
| `wire` | Typed E2EE envelopes, cursors and compatibility codecs |

Upstream source is not imported until the provenance, license, cryptography,
accessibility and self-hosting gates pass.

