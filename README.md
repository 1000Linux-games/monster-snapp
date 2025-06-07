# Monster Snapp
Ein Spiel, in dem du Monster in eine Kiste stoßen musst.


# 🧰 Installation von Monster Snapp (für alle Linux-Distributionen)

Monster Snapp ist über **Flathub** verfügbar – der App-Store für Linux. Du kannst es ganz einfach mit Flatpak auf allen gängigen Distributionen installieren.

---

## ✅ Voraussetzungen

Flatpak muss installiert sein. Wenn es auf deinem System noch fehlt, folge diesen Schritten:

### 🐧 Ubuntu / Linux Mint / Pop!\_OS:
```bash
sudo apt install flatpak
```

### 🐧 Debian:
```bash
sudo apt install flatpak
```

### 🐧 Fedora:
Flatpak ist bereits vorinstalliert ✅

### 🐧 Arch Linux / Manjaro:
```bash
sudo pacman -S flatpak
```

### 🐧 openSUSE:
```bash
sudo zypper install flatpak
```

---

## ✅ Flathub als Quelle hinzufügen

```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

---

## ✅ Monster Snapp installieren

```bash
flatpak install flathub com.david.MonsterSnapp
```

---

## ✅ Monster Snapp starten

```bash
flatpak run com.david.MonsterSnapp
```

---

## 📌 Hinweis

Nach der Installation erscheint Monster Snapp auch im **Anwendungsmenü** deines Desktops (GNOME, KDE, XFCE etc.). Sollte es dort nicht erscheinen, kannst du es immer mit dem obigen Befehl starten.

---

## 🧪 Für Entwickler: Lokaler Flatpak-Build

```bash
flatpak-builder --user --install --force-clean build-dir com.david.MonsterSnapp.yaml
```

---

Viel Spaß mit dem Spiel!
