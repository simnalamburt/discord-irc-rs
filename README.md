# discord-irc-rs

A Discord to IRC and vice-versa bridge bot written in Rust.

## Usage

Requires 1.39+ version of rustc.

```bash
cp sample.toml config.toml
# Edit config.toml ...

RUST_LOG=info cargo run -- config.toml
```

You can also run discord-irc-rs with Docker.

```bash
# If config.toml is located at /YOUR/PATH/TO/CONFIG
docker run -d --restart=always \
  --mount type=bind,source=/YOUR/PATH/TO/CONFIG,target=/a \
  ghcr.io/simnalamburt/discord-irc-rs
```

------

_discord-irs-rs_ is distributed under the terms of both [MIT license] and [Apache License 2.0]. See [COPYRIGHT] for details.

[MIT license]: LICENSE-MIT
[Apache License 2.0]: LICENSE-APACHE
[COPYRIGHT]: COPYRIGHT
