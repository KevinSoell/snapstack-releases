# Security

## Reporting a problem

Please report security problems privately through GitHub:
**https://github.com/KevinSoell/snapstack-releases/security/advisories/new**
("Report a vulnerability"). Do not open a public issue and do not include other
people's data or screenshots. Please give a reasonable time to fix it before telling others.

Helpful: the app version (menu bar → Settings → General), macOS version, what you did,
what happened, and why it is a security problem.

## Scope

- Screenshot App for macOS as downloaded from `github.com/KevinSoell/snapstack-releases`
  (DMG and updates).
- The update feed and release files in that repository.

Out of scope: problems that need an attacker who already controls your Mac, reports about
third-party services (GitHub), and social engineering.

## How the app is protected (short)

- Screenshots, History and settings stay on your Mac; this version has no upload and no account.
- Updates are accepted only with a valid EdDSA (Ed25519) signature from the developer's key;
  the update feed itself is signed too.
- The app is signed and uses the macOS hardened runtime; it asks only for Screen Recording
  (screenshots) and Accessibility (scrolling screenshots).
