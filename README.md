
# Example package

## Install

```bash
vpkg install github.com/valk-lang/pkg-example
```

## Usage

```rust
use example:funcs

fn main() {
    let msg = funcs:example_func()
    println(msg)
}
```

## How to add a new version

```bash
git tag 0.0.2
git push --tags
```