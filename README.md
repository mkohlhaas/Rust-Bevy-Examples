# [![Bevy](https://bevy.org/assets/bevy_logo_light_dark_and_dimmed.svg)](https://bevy.org)

## Getting Started

```sh
# Runs the "breakout" example
cargo run --example breakout
```

To draw a window with standard functionality enabled, use:

```rust
use bevy::prelude::*;

fn main() {
    App::new()
        .add_plugins(DefaultPlugins)
        .run();
}
```
