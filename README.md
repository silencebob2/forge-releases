# Forge

A Kodi 21 (Omega) video add-on. Access your content from your Debrid cloud.

> You must own the content of any media you play through this add-on. The author does not host any content and has no affiliation with any content provider.

---

## Install

Forge installs from this repository. Once installed, Forge keeps itself up to date — you only do this once.

### 1. Allow add-ons from unknown sources

In Kodi: **Settings → System → Add-ons** → turn on **Unknown sources**. Confirm the warning.

### 2. Add this repository as a source

In Kodi: **Settings → File manager → Add source**.

- Click **`<None>`** and paste this exactly (including the trailing slash):

  ```
  https://silencebob2.github.io/forge-releases/
  ```

- Name it **`Forge`** and click **OK**.

### 3. Install the repository

Go back to the Kodi home screen, then: **Add-ons → Add-on browser** (the open-box icon, top-left) **→ Install from zip file → Forge** → click:

```
repository.forge-0.1.0.zip
```

Wait for the "Forge Repository installed" notification.

### 4. Install Forge

In the same Add-on browser: **Install from repository → Forge Repository → Video add-ons → Forge → Install**.

Kodi will pull in the required dependencies automatically. When it finishes, Forge is in **Add-ons → Video add-ons**.

---

## Updates

After install, Forge checks for new versions on its own and prompts you to update — you don't need this repository again. You can change how it checks (Prompt / Automatic / Notification / Off) inside Forge's settings, under the update options.

---

## Troubleshooting

- **"Failed to install a dependency."** Make sure Kodi's official add-on repository is enabled (it is by default): **Add-ons → Add-on browser → Install from repository → Kodi Add-on repository** should be present. Forge's dependencies (`script.module.requests`, `script.module.pil`) come from there.
- **Nothing shows up in the zip list.** The source URL must be typed exactly as above and end with a trailing slash. Re-check step 2, then re-open **Install from zip file → Forge**.
- **Update says "no new version" but you expect one.** GitHub Pages links are cached for a few minutes after a release — wait a bit and try again.

---

*Forge is a streamlined Kodi video addon for browsing and playing content from your debrid services, built around a modernized codebase. Forked from FenLight AM. Licensed GPL-3.0-or-later.*
