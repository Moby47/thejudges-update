# thejudges-update

This repository hosts the remote version information for **The Judges**.

The game checks the `version.json` file during startup to determine whether a newer version is available and, if necessary, prompts the player to update.

## Purpose

- Notify players when a new update is available.
- Support optional and forced update prompts.
- Redirect players to the correct store page based on their platform.

## Current JSON Structure

```json
{
  "latest_version": 10,
  "force_update": false,
  "title": "UPDATE AVAILABLE",
  "message": "• Improved performance\n• Fixed boss teleport bug\n• Better enemy balancing\n• Various bug fixes",
  "android_url": "https://play.google.com/store/apps/details?id=com.prayerpathgames.thejudges",
  "ios_url": "",
  "windows_url": ""
}
