# Network Kit Beta Downloads

This public repository only hosts no-sign-in beta download assets for Network Kit. The source repository is private during early testing.

Download the latest beta from:

https://github.com/andrew-servey/network-kit-beta/releases

Current beta:

https://github.com/andrew-servey/network-kit-beta/releases/tag/v0.2.0-beta.3

## Privacy

Beta 3 and later are blank by default. The app uses:

```text
~/Library/Application Support/com.networkkit.desktop/network-kit.sqlite3
```

It does not auto-read legacy Resume Studio or earlier beta data. Personal data enters only through explicit `Intake → Import data bundle`.

## Opening on macOS

The beta is not notarized yet. If macOS blocks it:

1. Unzip the download.
2. Move `Network Kit.app` to Applications or Desktop.
3. Control-click/right-click the app and choose `Open`.

If macOS still refuses and Privacy & Security does not show `Open Anyway`, run:

```sh
xattr -dr com.apple.quarantine "/Applications/Network Kit.app"
```

Adjust the path if the app is somewhere else.
