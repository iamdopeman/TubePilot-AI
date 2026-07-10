# TubePilot AI Updates

This repository hosts the TubePilot AI update manifest.

## Current release

Version: 1.1.0

Release ZIP asset name:

```text
TubePilot-AI-Hybrid-AutoUpdate-v1.1.0.zip
```

## App update manifest URL

After uploading this repository to GitHub, use this format inside TubePilot AI > Update Center:

```text
https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/TubePilot-AI/main/update.json
```

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

## Release download URL format

The `update.json` file points to the latest GitHub release asset:

```text
https://github.com/YOUR_GITHUB_USERNAME/TubePilot-AI/releases/latest/download/TubePilot-AI-Hybrid-AutoUpdate-v1.1.0.zip
```

When you make a future update, upload the new ZIP as a GitHub Release asset and edit `update.json` with the new version, new asset file name, and new SHA256 hash.
