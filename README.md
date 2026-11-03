# @lavertia/vue-ui

Production Vue 3 renderer of Lavertia component protocol v1. This package owns the UI markup and interactivity; `lavertia/playground` is only a consumer.

The shared `@lavertia/ui` package supplies protocol types, table helpers and validated theme tokens. `lavertia/panels` supplies PHP definitions and the installer shim.

## Development

```sh
npm install github:lavertia/vue-ui#main
```

The page imports `@lavertia/ui/theme.css`, binds `themeVariables(lavertia.theme)` on its root, and uses semantic classes for accents, primary actions and focus. Configure the backend via `lavertia.panels.admin.theme = \Lavertia\ThemeDefault\ClassicTheme::class` after installing `lavertia/theme-default`.

No stable npm release is implied. Pin Git commits when consuming alpha builds.
