# Omi Xml Specifications

[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)

Omi Xml Specifications are the exchange protocol specification xml files that carry the message layouts, enums and dispatch rules of each protocol version — the vendor schemas and message definitions, matching the original specification files. Every Omi generated output — dissectors, parsers, definitions — is compiled from these source specifications.

## Development

The specification xmls in this repository are published copies of the original protocol specifications — they are not generated. If you find an error in a specification, updates are welcome as pull requests.

## Testing

[![Validate](https://github.com/Open-Markets-Initiative/omi-xml-specifications/actions/workflows/validate.yml/badge.svg)](https://github.com/Open-Markets-Initiative/omi-xml-specifications/actions/workflows/validate.yml)

Every published specification is validated for well-formed xml on each change. Please report any malformed or incorrect specification as an [issue](https://github.com/Open-Markets-Initiative/omi-xml-specifications/issues "Omi Xml Specifications Issues").  Include a small note on the protocol and version, and a link or pdf specification documenting the correct behavior.

## Open Markets Initiative

The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

Other generated code can be found at [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects"); for Omi rules and regulations, see [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory").
## Organizations

> [24X][24X.Directory] · [A2X][A2X.Directory] · [Aquis][Aquis.Directory] · [Asx][Asx.Directory] · [B3][B3.Directory] · [Bist][Bist.Directory] · [BlueOceanAts][BlueOceanAts.Directory] · [CixAts][CixAts.Directory] · [Cme][Cme.Directory] · [Coinbase][Coinbase.Directory] · [Iex][Iex.Directory]

## Exchanges

> [24XEquities][24XEquities.Exchange] · [AquisEquities][AquisEquities.Exchange] · [AsxDerivatives][AsxDerivatives.Exchange] · [AsxSecurities][AsxSecurities.Exchange] · [B3Derivatives][B3Derivatives.Exchange] · [BlueEquities][BlueEquities.Ats] · [BorsaIstanbul][BorsaIstanbul.Exchange] · [CoinbaseDerivatives][CoinbaseDerivatives.Exchange] · [Deribit][Deribit.Exchange] · [IexEquities][IexEquities.Exchange] · [IexOptions][IexOptions.Exchange]

## Platforms

> [CixAts CixAspen][CixAspen.Platform] · [Cme Globex][Globex.Platform]

## Related Definitions

The Open Markets Initiative provides protocol definitions in several formats:

- [Kaitai Struct Definitions][Kaitai.Definitions.Repository] — cross language binary parsers with the kaitai struct compiler
- [DFDL Definitions][Dfdl.Definitions.Repository] — declarative DFDL schemas for cross language parsing
- [P4 Definitions][P4.Definitions.Repository] — P4 programs for software and hardware data planes
- [Spicy Definitions][Spicy.Definitions.Repository] — declarative Spicy grammars for the spicy toolchain and the zeek network security monitor
- [FIX Dictionaries][Fix.Dictionaries.Repository] — QuickFIX format xml data dictionaries, one per FIX version
## Projects

The following projects are source generated from these definitions:

- [Wireshark Lua Dissectors][Wireshark.Lua.Dissectors] — cross platform Wireshark dissectors in lua
- [C Packed Structs][C.Packed.Structs] — c-style packed structs for binary protocols
- [Rust Protocols][Rust.Protocols] — zero copy Rust message views, one crate per protocol version
- [Python Classes][Python.Classes] — stable Python deserialization for common exchange protocols
- [C# Protocols][CSharp.Protocols] — zero copy C# protocol parsers, fixed layout structs and classes
## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.

[24X.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/24X "24 National Exchange"
[A2X.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/A2X "A2X Markets"
[Aquis.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Aquis "Aquis Exchange"
[Asx.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Asx "Australian Securities Exchange"
[B3.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/B3 "Brasil, Bolsa, Balcão"
[Bist.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Bist "Borsa İstanbul A.Ş."
[BlueOceanAts.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/BlueOceanAts "Blue Ocean Technologies"
[CixAts.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/CixAts "CIX Trading Inc."
[Cme.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Cme "CME Group"
[Coinbase.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Coinbase "Coinbase"
[Iex.Directory]: https://github.com/Open-Markets-Initiative/omi-xml-specifications/tree/main/Iex "Investors Exchange"
[24XEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/24X/Protocols/24XEquities "24X Equities"
[AquisEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Aquis/Protocols/AquisEquities "Aquis Equities"
[AsxDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Asx/Protocols/AsxDerivatives "Asx Derivatives"
[AsxSecurities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Asx/Protocols/AsxSecurities "Asx Securities"
[B3Derivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/B3/Protocols/B3Derivatives "B3 Derivatives"
[BlueEquities.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/BlueOceanAts/Protocols/BlueEquities "Blue Equities"
[BorsaIstanbul.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Bist/Protocols/BorsaIstanbul "Borsa Istanbul"
[CixAspen.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/CixAts/Protocols/CixAspen "CIX Aspen"
[CoinbaseDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Coinbase/Protocols/CoinbaseDerivatives "Coinbase Derivatives"
[Deribit.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Coinbase/Protocols/Deribit "Deribit"
[Globex.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cme/Protocols/Globex "CME Globex"
[IexEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Iex/Protocols/IexEquities "IEX Equities"
[IexOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Iex/Protocols/IexOptions "IEX Options"
[Kaitai.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-kaitai-struct-definitions "Omi Kaitai Struct Definitions"
[Dfdl.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-dfdl-definitions "Omi DFDL Definitions"
[P4.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-p4-definitions "Omi P4 Definitions"
[Spicy.Definitions.Repository]: https://github.com/Open-Markets-Initiative/omi-spicy-definitions "Omi Spicy Definitions"
[Fix.Dictionaries.Repository]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries "Omi FIX Dictionaries"
[Wireshark.Lua.Dissectors]: https://github.com/Open-Markets-Initiative/omi-wireshark-lua "Omi Wireshark Lua Dissectors"
[C.Packed.Structs]: https://github.com/Open-Markets-Initiative/c-structs "Omi C Packed Structs"
[Rust.Protocols]: https://github.com/Open-Markets-Initiative/omi-rust-protocols "Omi Rust Protocols"
[Python.Classes]: https://github.com/Open-Markets-Initiative/omi-python-classes "Omi Python Classes"
[CSharp.Protocols]: https://github.com/Open-Markets-Initiative/omi-csharp-protocols "Omi C# Protocols"
