# Monarchy

Theme for [Omarchy Linux](https://omarchy.org) — a dark, sage-green and warm-gold palette.

Made with [Aether](https://github.com/omacom/aether).

![preview](preview.png)

## Installation

```bash
omarchy theme install <this-repo-url>
```

## GNOME / GTK apps (Nautilus, etc.)

Omarchy's built-in theming covers terminals, editors, and other core apps
automatically, plus GNOME's icon theme via `icons.theme` (already included
here — matches this theme's sage-green accent).

This theme also ships a `gtk-4.0/gtk.css` with real background/text colors
for GTK4/libadwaita apps (Nautilus, etc.) — Omarchy doesn't apply this
automatically yet, so copy it into place after installing the theme:

```bash
mkdir -p ~/.config/gtk-4.0
cp ~/.config/omarchy/themes/monarchy/gtk-4.0/gtk.css ~/.config/gtk-4.0/gtk.css
```

Those apps also support a system accent color Omarchy doesn't set
automatically. For a closer match, run:

```bash
gsettings set org.gnome.desktop.interface accent-color green
```

![Nautilus and GTK apps](screenshots/nautilus-and-gtk-apps.png)

## License

MIT
