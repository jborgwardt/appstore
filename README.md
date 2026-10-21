# Vohef App Store (Umbrel Community Store)

This repository is a custom Umbrel Community App Store.

## Store manifest

- `umbrel-app-store.yml`
  - `id`: `vohefapps`
  - `name`: `VohefAppStore`

## Included app

- `vohefapps-mediastorm`
  - MediaStorm app manifest: `vohefapps-mediastorm/umbrel-app.yml`
  - Docker services: `vohefapps-mediastorm/docker-compose.yml`

## Imported app catalogs

This store now also includes imported apps from:

- BigBearCasaOS (`vohefapps-bbcasaos-*`)
- RunTipi (`vohefapps-runtipi-*`)
- Unraid community templates (`vohefapps-unraid-*`)

Each imported app is namespaced by source in its Umbrel app ID to avoid collisions.

## Add this store to umbrelOS

1. In umbrelOS, open **App Store**.
2. Click **Community App Stores**.
3. Add this repository URL as a custom store.
4. Install **MediaStorm** from the `VohefAppStore` listing.
