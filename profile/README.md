# Abyss Linux

A Void-based Linux distribution designed around secure defaults, simple tooling, and predictable administration.

It builds on Void Linux and runit while remaining close to upstream
behavior, adding a small set of auditable tools rather than replacing
existing components.

## Core Components

- **svpm** - a POSIX shell wrapper around `xbps`.
- **svcctl** - a runit management tool that
  provides profile-based service management, configuration snapshots,
  auditing, and rollback.

These tools can also be used on any Void Linux system, although made for Abyss.

## Status

Abyss Linux is under active development and should be considered
experimental.

## License

The Abyss Project's tools are licensed under the MIT License <3
