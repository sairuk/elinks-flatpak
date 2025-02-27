# elinks-flatpak
Build out a flatpak version of elinks

build and install the flatpak
```
flatpak-builder build-dir --user --install-deps-from=flathub --download-only com.github.rkd77.elinks.yaml
flatpak-builder build-dir --user --force-clean --install --repo=repo com.github.rkd77.elinks.yaml
```

this repo is licensed same as main project
