# Omi Xml Specifications

Omi universal xml binary specifications describe common exchange protocols in a single declarative format: the exchange definition xmls that carry the message layouts, enums and dispatch rules for each protocol version. Every Omi generated output — dissectors, parsers, definitions — compiles from these files.

## Layout

Each protocol version is one folder: `{Organization}/{Identifier}/` holding the protocol's exchange definition xmls. The shared framing headers and the reference manifest are omitted, so a folder carries only the definitions unique to that protocol.

## Development

Updates are greatly appreciated; however, this entire repository is source generated...including the words you are reading right now. If you wish to suggest specification updates, the recommended process is to create an issue with changes and explanation.  Time permitting, we will update the specifications and regenerate.

## Open Markets Initiative

The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi Hft projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")
## Organizations

> CixAts · Iex

## Related Definitions

The Open Markets Initiative provides protocol definitions in several formats:

- [Kaitai Struct Definitions](https://github.com/Open-Markets-Initiative/omi-kaitai-struct-definitions) — cross language binary parsers with the kaitai struct compiler
- [DFDL Definitions](https://github.com/Open-Markets-Initiative/omi-dfdl-definitions) — declarative DFDL schemas for cross language parsing
- [P4 Definitions](https://github.com/Open-Markets-Initiative/omi-p4-definitions) — P4 programs for software and hardware data planes
- [Spicy Definitions](https://github.com/Open-Markets-Initiative/omi-spicy-definitions) — Spicy grammars for the Spicy toolchain and Zeek
- [FIX Dictionaries](https://github.com/Open-Markets-Initiative/omi-fix-dictionaries) — QuickFIX-format xml dictionaries, one per FIX version
## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.

