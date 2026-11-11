<div align="center">

# 🪣 zubyr's Scoop bucket

**Windows apps by [zubairbinshaukat](https://github.com/zubairbinshaukat), one command away.**

[![Scoop](https://img.shields.io/badge/Scoop-bucket-5aa9ff?style=for-the-badge&labelColor=0b0d10)](https://scoop.sh)
[![Apps](https://img.shields.io/github/directory-file-count/zubairbinshaukat/scoop-bucket/bucket?type=file&extension=json&style=for-the-badge&label=Apps&color=3ddc97&labelColor=0b0d10)](bucket)

</div>

## Quick start

```powershell
scoop bucket add zubyr https://github.com/zubairbinshaukat/scoop-bucket
scoop install nook      # or: scoop install devpit
```

If another bucket ships an app with the same name, use the full name: `scoop install zubyr/nook`.
`scoop update *` keeps everything current.

## Apps

<table>
<tr>
<td width="50%" valign="top">

### [Nook](https://github.com/zubairbinshaukat/nook)

A Dynamic Island for Windows. Your Claude Code, Codex and Cursor agents sit at the top of the screen, with their status, usage limits, and approvals you give with one click.

```powershell
scoop install zubyr/nook
```

[Website](https://nook.zubyr.dev) · [Releases](https://github.com/zubairbinshaukat/nook/releases)

</td>
<td width="50%" valign="top">

<a href="https://nook.zubyr.dev"><img src="https://raw.githubusercontent.com/zubairbinshaukat/nook/main/site/assets/img/shots/hero-dark.webp" alt="Nook showing agent sessions at the top of the screen"></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Devpit](https://github.com/zubairbinshaukat/devpit)

A pit stop for your dev machine. Get disk space back, free stuck ports, update your tools and use the right account in every folder, all from one terminal menu.

```powershell
scoop install zubyr/devpit
```

[Website](https://devpit.zubyr.dev) · [Releases](https://github.com/zubairbinshaukat/devpit/releases)

</td>
<td width="50%" valign="top">

<a href="https://devpit.zubyr.dev"><img src="https://raw.githubusercontent.com/zubairbinshaukat/devpit/main/web/docs-site/src/assets/screens/home-menu.webp" alt="Devpit's main menu in the terminal"></a>

</td>
</tr>
</table>

## How it works

- **Verified downloads:** every manifest points at a GitHub release asset and pins its SHA-256.
- **Kept up to date:** manifests follow each app's releases. Please don't edit the JSON by hand.
- **Problems?** Open an issue on the app's own repository.

<details>
<summary><b>Adding an app</b></summary>

1. Add `bucket/<app>.json`, with `checkver` and `autoupdate` so new releases are picked up.
2. Add a row to the table above: name, one line on what it does, the install command, links and a screenshot.

</details>
