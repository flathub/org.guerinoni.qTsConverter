# qTsConverter

___A simple tool to convert qt translation file___

A simple tool to convert qt translation file (ts) to other format (xlsx / csv) and vice versa.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub org.guerinoni.qTsConverter
flatpak run org.guerinoni.qTsConverter
```

## Building

```bash
git clone git@github.com:flathub/org.guerinoni.qTsConverter.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.guerinoni.qTsConverter.yml
```

---

**Technologies**: KDE, QT, C++
