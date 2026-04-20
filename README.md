# Crono Cachy

> *A Chrono Trigger inspired desktop —Windows looks like an old parchment to represent the RPG style*

Built on **CachyOS** + **Hyprland**, themed around the warm tones and aged textures of Chrono Trigger.

---

## Stack

| Role | Tool |
|---|---|
| Compositor | Hyprland |
| Status Bar | Waybar |
| Terminal | Kitty |
| Shell | Fish |
| Login Manager | SDDM + Astronaut Theme |
| Color Generator | Matugen |

---

## Colors

Colors are generated dynamically from the wallpaper using **Matugen**, keeping the palette consistent across Waybar and the rest of the system.

To regenerate colors from a new wallpaper:

```bash
swww img ~/path/to/wallpaper.png && matugen image ~/path/to/wallpaper.png
```

---

## Installation

> These are personal dotfiles. Remember to adapt to your files and so on.

```bash
git clone git@github.com:Gonalves3236/My_Little_Cachy.git
cd My_Little_Cachy
cp -r hypr/ waybar/ ~/.config/
```

---

## Structure

```
~/.config/
├── hypr/          # Hyprland config (binds, rules, animations)
├── waybar/        # Bar configs and styles
```

---
