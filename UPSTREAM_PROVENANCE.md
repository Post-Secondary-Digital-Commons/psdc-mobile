# Happy Import and Provenance Policy

> Status: Normative import policy; no source imported during documentation phase
> Governing decision: ADR-0019

## Selected boundary

The evaluated upstream is `https://github.com/slopus/happy`. Only exact
MIT-licensed files approved by file-level review are eligible. Happy-hosted
accounts, relay, telemetry, endpoints, branding, provider assumptions and secrets
are excluded. The research snapshot was `main` at
`ac64b9b4677870f7b7a9eacfd0780959229717f1`, observed 2026-09-10; observation
does not itself authorize copying.

## Implementation import gate

The pull request that imports source SHALL pin the exact immutable commit and
archive checksum; inventory imported, removed, generated and vendored files;
preserve notices; lock dependencies; produce license, SBOM and vulnerability
reports; prove every hosted Happy endpoint can be disabled; review the E2EE
protocol, keys, pairing, recovery, revocation, relay metadata, deep links, wake
notifications, background behaviour and offline queues; pass iOS, Android and
accessibility tests; implement provider-neutral gateway and session adapters; and
name the responsible release and vulnerability owners.

If any requirement fails, the mobile client SHALL use a clean implementation of
the PSDC Mobile and Agent Session contracts. The architecture is complete
independently of whether the evaluated upstream is ultimately imported.
