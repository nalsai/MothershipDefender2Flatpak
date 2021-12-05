# MothershipDefender2Flatpak

📦 Flatpak Package of Mothership Defender 2 for Linux

## Installing

I'm hosting this Mothership Defender 2 Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/de.Nalsai.MothershipDefender2.flatpakref
```

You can also install it from the bundle in Releases on GitHub, but you won't get updates that way.

## Building

### Install SDK and Platform

```bash
flatpak install flathub org.freedesktop.Sdk//21.08
flatpak install flathub org.freedesktop.Platform//21.08
```

### Build

```bash
flatpak-builder --repo=repo --force-clean build-dir de.Nalsai.MothershipDefender2.yml
```

### Make single-file bundle

```bash
flatpak build-bundle repo MothershipDefender2.flatpak de.Nalsai.MothershipDefender2 stable --runtime-repo="https://flathub.org/repo/flathub.flatpakrepo"
```

