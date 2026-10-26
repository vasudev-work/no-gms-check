# no-gms-check — Nijatva

**Build guard**

A Gradle plugin and a GitHub Action that fail the build when a resolved dependency pulls in com.google.android.gms, com.google.firebase or any play-services artefact. Also checks that the manifest does not quietly gain the INTERNET permission where the app claims not to have it.

## Why this exists first

A promise in a README is worth nothing. This is the enforcement that makes the no-GMS claim checkable by anyone.

Part of the [Nijatva](https://vasudev-work.github.io) suite by **DEVIRA**.

## Status

Repository created. Implementation follows the app build order in the suite tracker.

## Licence

All rights reserved until a licence is added before the first release.
