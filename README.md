# Bennett Legal — Cowork Plugin Registry

Public registry of Cowork plugins for Bennett Legal staff. Install any plugin by downloading the `.zip` and going to **Settings → Plugins → Install Plugin** in the Claude desktop app.

## Available Plugins

| Plugin | Version | Description | Download |
|--------|---------|-------------|----------|
| bennett-legal-health-check | v2.0.0 | Department-aware diagnostic — tests all connectors and posts a pass/fail report to Linear | [Download](https://github.com/bennettlegal/bl-cowork-plugins/releases/download/health-check-v2.0.0/bennett-legal-health-check-v2.0.0.zip) |

## How to Install a Plugin

1. Click the **Download** link above to get the `.zip` file
2. Open the Claude desktop app
3. Go to **Settings → Plugins → Install Plugin**
4. Select the `.zip` file — do not unzip it
5. The plugin appears in your list immediately

## How to Update a Plugin

Ask Cowork: *"Download the latest [plugin-name] plugin from GitHub"* — it will fetch the zip and save it to your workspace folder. Then go to Settings → Plugins → Install Plugin and select it.

## Adding a New Plugin

1. Create a folder: `your-plugin-name/`
2. Add the `.zip` and a `CHANGELOG.md`
3. Create a GitHub Release with tag `your-plugin-name-vX.Y.Z`
4. Update this README table

## Release Naming Convention

Tags follow `{plugin-name}-v{semver}` — e.g. `health-check-v2.0.0`
