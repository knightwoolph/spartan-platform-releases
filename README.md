# Spartan Platform Releases

Remote configuration, OTA updates, and data packs for the Spartan Dealer Platform.

## Files

- `remote-config.json` — Remote config fetched by all dealer platforms (announcements, commands, feature flags)
- GitHub Releases — OTA installer updates with SHA256 manifests

## Config Format

```json
{
  "version": 1,
  "updatedAt": "ISO timestamp",
  "announcements": [],
  "featureFlags": {},
  "commands": [],
  "minAppVersion": "1.0.0"
}
```

Managed via the Admin Dashboard in the master platform.
