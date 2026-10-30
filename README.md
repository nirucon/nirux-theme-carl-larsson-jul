# NIRUX Theme: Carl Larsson Jul

A NIRUX suite theme pack based on the Carl Larsson Christmas wallpaper.

- Theme ID: `niru-carl-larsson-jul`
- Display name: **Niru Carl Larsson Jul**
- Background: `#0b0a09`
- Foreground: `#e9dfcf`
- Muted: `#a89b89`
- Border: `#332c25`
- Focus: `#b45a48`
- Wallpaper: `nirux-wallpaper-carl-larsson-jul-4k.png` (4K)

## Install

NIRUX must be installed and `niructl` must be in `PATH`.

```sh
./install.sh
niructl theme niru-carl-larsson-jul
```

The installer uses `niructl theme-import`, so it validates the theme and
installs both the palette and wallpaper into the standard per-user locations.
No root access is required.

To replace an existing installation after a pack update:

```sh
./install.sh --replace
niructl theme niru-carl-larsson-jul
```

## Uninstall

```sh
./uninstall.sh
```

## Compatibility

The theme is a user theme, so the suite discovers it without being added to any
built-in theme list. Components that follow the shared NIRUX theme pick it up:
NIRUWM, NIRUBAR, NIRU Launcher, NIRUNOTIFY, NIRULOCK, NIRUSCREENSAVER,
NIRUSHOT, NIRUPRES editor chrome, NIRUFLOW, NIRUORG and NIRUNOTE with
**Follow NIRUX**. NIRUPRES slide themes remain independent by design.
