Goal: Explain how I made and deployed my homepage

Main features and talking points:
- Yew + Rust
  - Setup with Trunk and rust targets
    - `cargo install trunk` (`nix-shell -p trunk` on nixos)
    - `rustup target add wasm32-unknown-unknown`
  - Basic Functional Components overview
  - Show how trunk watch works
    - Example change something
  - Another example https://github.com/mathkimchi/generic-clicker-game
- Reusing components
- Multipage with Router
  - 404 trick
- Automatic page generation by parsing JSON
- Meta-config with Trunk.toml and target.html
  - Res and stuff
- Deploying on GitHub Pages
  - Mention it is possible to forward to a custom domain
- Automation with GitHub Action
