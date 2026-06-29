# Network Kit Beta

Network Kit is a local-first macOS workspace for relationship-centered internship and job-search tracking: people, company context, outreach, tailored resumes, matching cover letters, and portable data exports.

This public repository is only the no-sign-in beta download mirror. The source repository is private during early testing.

## Latest Download

Current beta: **Network Kit Beta 10**

- Release: https://github.com/andrew-servey/network-kit-beta/releases/tag/v0.2.0-beta.10
- macOS zip: https://github.com/andrew-servey/network-kit-beta/releases/download/v0.2.0-beta.10/Network.Kit.Beta.10.macOS.zip
- SHA-256: `aebfff50c61985fc83325cc991c0c7a7da4c3585905f1709f2a2491702f4d35b`

After unzipping, open `Network Kit Beta 10.app`.

## What Is New In Beta 10

- First-class contacts with relationship source, outreach stage, tags, next action, last-contacted date, and follow-up date.
- Per-contact activity timelines for notes, email, calls, meetings, documents sent, and other follow-up.
- Contact pipeline stages: identified, reached out, replied, met, intro made, and active.
- Import/export support for `schemaVersion: 2` data bundles, while still importing `schemaVersion: 1` bundles from earlier betas.
- A blank public seed by default. Personal data enters only through explicit import.

## Privacy And Data

Network Kit stores local beta data at:

```text
~/Library/Application Support/com.networkkit.desktop/network-kit.sqlite3
```

The public beta uses the app identity `com.networkkit.desktop`. It does not auto-read legacy Resume Studio or early private-beta data. Move personal data between builds with explicit `Intake -> Export my data` and `Intake -> Import data bundle` using `network-kit-data.json`.

## Opening On macOS

The beta is not notarized yet. If macOS blocks it:

1. Unzip the download.
2. Move `Network Kit Beta 10.app` to Applications or Desktop.
3. Control-click/right-click the app and choose `Open`.

If macOS still refuses and Privacy & Security does not show `Open Anyway`, run:

```sh
xattr -dr com.apple.quarantine "/Applications/Network Kit Beta 10.app"
```

Adjust the path if the app is somewhere else.

## Older Betas

Older releases are kept only for comparison and recovery. Use Beta 10 or later for active testing.
