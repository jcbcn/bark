# Bark

[![Rust](https://github.com/jcbcn/bark/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/jcbcn/bark/actions/workflows/rust.yml)

## Ideas

- Daily notes
- Templates e.g Morning pages
- Tags
- Linked references
- Unlinked references

## Architecture

- bark-core
    - Disk I/O operations
    - Parsing CommonMark
    - Search
    - Linking
    - Graph
- bark-frontend
    - Text - glyph-brush
    - Window - winit
    - OpenGl - glutin
