# Utah Smart Homes — Home Assistant add-ons

Add-on repository for **Home Intelligence**, the local interface that runs on the
Home Intelligence appliance beside Home Assistant.

## Install

Home Assistant → **Settings → Add-ons → Add-on Store → ⋮ → Repositories**, add:

```
https://github.com/Cashby71/uhs-addons
```

Then install **Home Intelligence**, set `secret_key` (and a Home Assistant
long-lived token), and start it.

## What's here

Manifests only. The application source is private; the container image is
published to GitHub Container Registry and pulled by each appliance, so no
customer hardware ever compiles the app.

| | |
| --- | --- |
| Image | `ghcr.io/cashby71/home-intelligence-{arch}` |
| Architectures | `amd64` (the appliance), `aarch64` (bench) |
