# scoop-bucket

A [Scoop](https://scoop.sh) bucket for tools by [zubairbinshaukat](https://github.com/zubairbinshaukat).

## Install

Add the bucket once, then install anything in it:

```powershell
scoop bucket add zubyr https://github.com/zubairbinshaukat/scoop-bucket
scoop install devpit
```

Update everything from this bucket the usual way:

```powershell
scoop update
scoop update devpit
```

## Apps

| App | What it does | Source |
| --- | --- | --- |
| `devpit` | A pit stop for your dev machine: free disk space, fix stuck ports, update your tools | [zubairbinshaukat/devpit](https://github.com/zubairbinshaukat/devpit) |

## How this bucket is maintained

Manifests in `bucket/` are written by GoReleaser from each project's release
workflow. A new tagged release updates the manifest here automatically, so
please do not edit the JSON files by hand. To report a broken install, open an
issue on the app's own repository.

Every manifest points at a GitHub release asset and pins its SHA256, so Scoop
verifies what it downloads.
