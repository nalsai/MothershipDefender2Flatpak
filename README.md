# MothershipDefender2Flatpak

📦 Flatpak Package of Mothership Defender 2 for Linux

## Installing

I'm hosting this Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/repo/appstream/de.Nalsai.MothershipDefender2.flatpakref
```

## Building

```bash
flatpak-builder --install-deps-from=flathub --force-clean build-dir de.Nalsai.MothershipDefender2.yml
```
