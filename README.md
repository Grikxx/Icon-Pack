
# Icon-Pack

A custom icon pack designed for GNOME and Linux desktop environments.

## Installation

### 1. Download the Theme
Clone this repository directly into your local icons directory:

```bash
git clone [https://github.com/Grikxx/Icon-Pack.git](https://github.com/Grikxx/Icon-Pack.git) ~/.local/share/icons/Icon-Pack
```


*Note: If the `~/.local/share/icons` directory does not exist, create it first using `mkdir -p ~/.local/share/icons`.*

### 2. Apply the Icons

You can enable the icon pack using your desktop environment's customization tool:

* **GNOME:** Open **GNOME Tweaks** -> **Appearance** -> **Icons** and select `Icon-Pack`.
* **CLI/Arch:** Alternatively, apply it directly via the terminal:
```bash
gsettings set org.gnome.desktop.interface icon-theme "Icon-Pack"

```



## Repository Structure

* `apps/scalable` & `apps@2x`: High-quality scalable vector application icons.
* `places/scalable` & `places@2x`: System folders and navigation location icons.
* `index.theme`: The configuration file that defines icon directory paths, sizes, and context for the desktop environment.
* `icon-theme.cache`: Pre-compiled graphical cache to ensure fast rendering performance.
