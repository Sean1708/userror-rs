# userror

Some basic functions and macros for printing user-facing errors in command-line programs.

## Installation

Simply mark userror as a dependency in your Cargo.toml

```toml
[dependencies]
userror = "0.1.0"
```

By default userror prints coloured messages with ansi_term, if you do not want this use
`default-features = false`

```toml
[dependencies]
userror = { version = "0.1.0", default-features = false }
```
