# JENI Studio — Pastel Signal

Experimental full Discourse theme, version 0.1.0. Manually scaffolded with owner authorization.

## Install and configure

Import this repository as a theme in Discourse. Because the repository is private, use the private-repository authentication supported by your installation, or import the supplied ZIP. Keep it non-default while testing.

Upload `space-bling-bg-opacity-20.jpg` to the theme setting `background_image`. The downloadable package includes the original in `reference/`; the repository contains text source only. Choose Pastel Signal Light or Pastel Signal Dark in the theme color configuration. With no upload, the theme uses a plain fallback background.

The image is already pale: no additional opacity is applied. Opaque content panels preserve readability. Background uses cover, so cropping varies with screen proportions. No JavaScript, animation, block layout registrations, external fonts, or remote image dependencies.

## Testing status

Source package checks only; not compiled or browser-tested against a running Discourse instance. The included core-feature RSpec spec requires the Discourse test environment; it has not been run. No compatibility version is asserted.

Before enabling by default, check desktop and mobile topic lists, categories, long topics, sidebar, composer, search, menus, keyboard navigation, light/dark color schemes, and the background upload. Check contrast with real content. Test alongside existing theme components.

## Structure

`common/common.scss` contains imports only. Brand colors are CSS tokens on `:root`; app files contain core variable overrides, background styling, and panels. This is a minimal test theme, not the complete CLI-generated tooling scaffold.

## Artwork

Background supplied by the repository owner. No license or redistribution permission is inferred for the artwork or code.
