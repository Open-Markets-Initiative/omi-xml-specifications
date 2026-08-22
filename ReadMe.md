# Omi Xml Specifications

[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)

Omi Xml Specifications are the exchange protocol specification xml files that carry the message layouts, enums and dispatch rules of each protocol version — the vendor schemas and message definitions, matching the original specification files. Every Omi generated output — dissectors, parsers, definitions — is compiled from these source specifications.

## Layout

Each protocol version is one folder: `{Organization}/{Identifier}/` holding the protocol's specification xmls as published, matching the original files. The shared framing headers and the reference manifest are omitted, so a folder carries only the definitions unique to that protocol.

## Development

Updates are greatly appreciated; however, this entire repository is source generated...including the words you are reading right now. If you wish to suggest specification updates, the recommended process is to create an issue with changes and explanation.  Time permitting, we will update the specifications and regenerate.

## Testing

[![Validate](https://github.com/Open-Markets-Initiative/omi-xml-specifications/actions/workflows/validate.yml/badge.svg)](https://github.com/Open-Markets-Initiative/omi-xml-specifications/actions/workflows/validate.yml)

Every published specification is validated for well-formed xml on each change. Please report any malformed or incorrect specification as an [issue](https://github.com/Open-Markets-Initiative/omi-xml-specifications/issues "Omi Xml Specifications Issues").  Include a small note on the protocol and version, and a link or pdf specification documenting the correct behavior.

## Open Markets Initiative

The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi Hft projects see [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects"); for details of Omi rules and regulations see [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory").
## Organizations

> CIX Trading Inc. · Investors Exchange

## Related Definitions

The Open Markets Initiative provides protocol definitions in several formats:

- [Kaitai Struct Definitions][Kaitai.Definitions.Repository] — cross language binary parsers with the kaitai struct compiler
- [DFDL Definitions][Dfdl.Definitions.Repository] — declarative DFDL schemas for cross language parsing
- [P4 Definitions][P4.Definitions.Repository] — P4 programs for software and hardware data planes
- [Spicy Definitions][Spicy.Definitions.Repository] — declarative Spicy grammars for the spicy toolchain and the zeek network security monitor
- [FIX Dictionaries][Fix.Dictionaries.Repository] — QuickFIX format xml data dictionaries, one per FIX version
## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.

[Kaitai.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-kaitai-struct-definitions "Omi Kaitai Struct Definitions"
[Dfdl.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-dfdl-definitions "Omi DFDL Definitions"
[P4.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-p4-definitions "Omi P4 Definitions"
[Spicy.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-spicy-definitions "Omi Spicy Definitions"
[Fix.Dictionaries.Repository]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries "Omi FIX Dictionaries"
