# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Language

ユーザーとの対話には日本語を使用すること。

## Build Commands

```bash
cargo build          # Build the project
cargo run            # Run the application
cargo test           # Run all tests
cargo test <name>    # Run a specific test
cargo clippy         # Run linter
cargo fmt            # Format code
```

## Project Overview

**taskrem** is a Rust application (currently in early development).

Entry point: `src/main.rs`

## Notes

**Fix Required:** The Cargo.toml specifies `edition = "2024"` which is not a valid Rust edition. Valid editions are `2015`, `2018`, or `2021`. Change to `edition = "2021"` for the project to compile.
