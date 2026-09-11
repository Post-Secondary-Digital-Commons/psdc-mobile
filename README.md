# PSDC Mobile Client

This Expo/React Native companion is derived from Happy, as selected by ADR-0019.
Source has not been imported.

Mobile supervises sessions through a deployment's end-to-end encrypted Commons
Session Relay. It
does not execute a privileged local agent, store provider credentials, or depend
on Happy-hosted services. The Session Host and Commons AI Gateway remain authoritative.

See `UPSTREAM_PROVENANCE.md` and the canonical mobile foundation and Happy feature
scope in the umbrella architecture.

Distribution, white-labelling, institutional OIDC and device pairing are defined
by `psdc-architecture:docs/clients/Institution-Branded-Client-Distribution-and-Access.md`.

Apple App Store and Google Play builds are planned convenience channels, with a
self-hosted PWA and signed Android packages as portable alternatives. There is no
published public-store build yet; upstream source import, branding, signing,
privacy review and release automation are still pending.
