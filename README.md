# A1 Gallery for Gemini CLI

A Gemini CLI extension that connects to the [A1 Gallery](https://www.a1.gallery) MCP server.

A1 is a hand-curated gallery of 1,150+ real websites. You can search it by style, font, colour, section and technology. Results include captured sections, full pages, fonts and design values measured off the live page: hex colours with roles, type sizes and weights, spacing, radius and layout.

## Install

```bash
gemini extensions install https://github.com/bryntay/a1-gemini-extension
```

The first call opens a browser to sign in to your A1 account (OAuth). You can also run `/mcp auth a1` in Gemini CLI.

## Details

- Server: `https://www.a1.gallery/api/mcp` (Streamable HTTP, OAuth 2.1 with PKCE and dynamic client registration)
- 17 read-only tools
- Free with an A1 account (50 calls a day). Pro: 2,000 calls a day.

## Links

- Docs: https://www.a1.gallery/mcp
- Privacy: https://www.a1.gallery/privacy
- Terms: https://www.a1.gallery/terms
- Support: hello@a1.gallery

## License

MIT for the files in this repository. The hosted service is not open source.
