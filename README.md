# hsp-cs — DEPRECATED

> **This plugin is obsolete.** Use **[hsp](https://github.com/holo-q/hsp)** instead — a single unified plugin that routes Python, C#, and future languages through one MCP server with built-in language detection.

hsp-cs was the original C# language server plugin for Claude Code. Its functionality has been absorbed into the unified HSP plugin, which ships built-in routes for both C# (csharp-ls) and Python (ty + basedpyright) with automatic file-extension routing, shared broker sessions, and the full graph-operator tool surface.

## Migration

1. Uninstall hsp-cs
2. Install **[hsp](https://github.com/holo-q/hsp)**
3. Done — no configuration changes needed. HSP auto-detects C# projects via `.cs`, `.sln`, `.csproj`, and `Directory.Build.props` markers.

## Links

- **[hsp](https://github.com/holo-q/hsp)** — the unified LSP-to-MCP bridge (install this)
- [csharp-ls](https://github.com/razzmatazz/csharp-language-server) — the underlying C# LSP (still used by hsp's C# route)
