# ZED Bootstrap 5 Autocomplete

An autocomplete plugin for the [Zed Editor](https://zed.dev/) that provides intelligent suggestions for [Bootstrap 5](https://getbootstrap.com/) classes. Inspired by the [ST-BootstrapAutocomplete](https://github.com/jfcherng-sublime/ST-BootstrapAutocomplete) plugin for Sublime Text.

This plugin is designed to help front-end developers using Bootstrap 5 speed up their workflow by offering contextual, class-aware autocompletions.

## Features

- Autocomplete for all major Bootstrap 5 utility classes
- Fast, lightweight, and easy to use
- Matches partial inputs (e.g., typing `m-` suggests all margin utilities)
- Includes support for:
  - Spacing utilities (e.g., `m-`, `p-`)
  - Color utilities (e.g., `bg-`, `text-`)
  - Display, flex, grid, border, position, sizing classes, and more
- Regularly updated to track the latest Bootstrap 5 changes

## Installation

> ⚠️ This plugin requires [Zed Editor](https://zed.dev/). Ensure it's installed and up-to-date.

### Using Zed Plugin Manager (recommended)

1. Open Zed.
2. Go to `Preferences > Plugins`.
3. Search for **Bootstrap 5 Autocomplete**.
4. Click **Install**.

### Manual Installation

1. Clone or download this repository.
2. Copy the plugin folder into Zed's plugin directory:
   - **macOS/Linux**: `~/.config/zed/plugins`
   - **Windows**: `%APPDATA%\zed\plugins`
3. Restart Zed.

## Usage

Simply start typing any Bootstrap 5 class in your HTML, JSX, or other supported markup files. Suggestions will appear automatically.

Example:

```html
<div class="m-">
