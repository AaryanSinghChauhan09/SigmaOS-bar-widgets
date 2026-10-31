# SigmaOS Bar Widgets

A Rust model for organizing status-bar widgets. It provides `BarWidget` values with position, visibility, enabled state, interaction metadata, and string configuration, plus a `BarWidgetsManager` for registration, filtering, moving, ordering, and removal.

This crate models widget state; it does not render a bar, create a desktop panel, or dispatch real pointer and scroll events. GUI integration remains the responsibility of a host application.

## Build

The manifest uses the sibling [`SigmaOS-kernel`](../SigmaOS-kernel) path dependency. From the SigmaOS checkout:

```sh
cargo check --manifest-path SigmaOS-bar-widgets/Cargo.toml --lib
```

## License

GPL-3.0-or-later. See [`Cargo.toml`](Cargo.toml).
