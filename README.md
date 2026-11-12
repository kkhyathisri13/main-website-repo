# main-website-repo

## Documentation overview

This repository contains the satellite-app catalog and an Oceanview property backup. The property documentation below is reconstructed from that backup; it is not an original page-template recovery or a deployment change.

- [Oceanview Luxury Suite property details](docs/properties/oceanview.md)
- [Satellite-app catalog](src/data/satelliteApps.json)
- [Preserved property backup](backups/property-listing-backup.json)

## Satellite apps

Source: [src/data/satelliteApps.json](src/data/satelliteApps.json).

| Application | ID | Application route | Catalog status |
| --- | --- | --- | --- |
| Property Analytics Hub | `app-1` | `/apps/analytics` | `active` |
| Tenant Portal | `app-2` | `/apps/tenant-portal` | `active` |

Routes are relative to the deployed application, not GitHub file paths. Catalog status is configuration data; live availability has not been verified. No deployment base URL is recorded in this repository.

## Property documentation

[Oceanview Luxury Suite](docs/properties/oceanview.md) documents every field present in the preserved backup, including its recorded publication status. Current pricing, availability, and live publication require separate verification.

## Historical merged notes

- [PR #1](https://github.com/kkhyathisri13/main-website-repo/pull/1) recorded: "Updated satellite app catalog details."
- [PR #2](https://github.com/kkhyathisri13/main-website-repo/pull/2) recorded: "Homepage layout alignment verified."

Both pull requests changed only `README.md`, and both are already merged. These statements are preserved as historical notes, not evidence that application code changed or that the deployed layout was tested during this documentation review.
