# pylcs-rs

This is a Rust port of the [pylcs](https://github.com/Meteorix/pylcs) project.

## development

test Rust Modules
```
cargo test
```

install dev dependencies
```
uv sync
source .venv/bin/activate
```

build for editable package
```
maturin develop --uv
```

test Python Module (with uv)
```
uv run pytest
```

build for release
```
maturin build --release
```

Artifact Example on MacOS: `.../target/wheels/pylcs_rs-0.1.0-cp311-cp311-macosx_11_0_arm64.whl`
