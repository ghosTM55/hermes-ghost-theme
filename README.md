# Hermes Ghost Theme

A custom Hermes Agent CLI theme: `mono-ghost`.

It is a dark, high-contrast terminal skin with cyan accents, a retro MS-DOS / Windows 3.x banner, and minimal spinner styling.

## Files

```text
skins/mono-ghost.yaml
```

The Hermes Agent skin file.

It configures:

- `colors`: CLI banner, prompt, response border, status bar, completion menu, warnings, and error colors.
- `spinner`: waiting / thinking indicators and verbs.
- `branding`: agent welcome text, goodbye text, response label, prompt symbol, and help header.
- `tool_prefix`: prefix used before tool activity lines.
- `tool_emojis`: per-tool emoji overrides. Currently empty.
- `banner_logo`: custom Rich-markup ASCII logo.
- `banner_hero`: custom Rich-markup Windows 3.x style hero art.

## Install

Copy the skin file into your Hermes skins directory:

```bash
mkdir -p ~/.hermes/skins
cp skins/mono-ghost.yaml ~/.hermes/skins/mono-ghost.yaml
```

Then activate it inside Hermes:

```text
/skin mono-ghost
```

To make it your default theme:

```bash
hermes config set display.skin mono-ghost
```

Restart Hermes after changing the default config.

## Follow me on Twitter

- [@ghosTM55](https://x.com/ghostm55)
