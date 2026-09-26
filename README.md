# Eugene Barsky

Software developer working with Vue, Nuxt, TypeScript and Node.js, mostly on data-heavy interfaces: dashboards, charts, graph visualisation and performance. I also build AI features: an in-app assistant and an MCP server for agents.

Website: [evb-stack.com](https://evb-stack.com/en)

## EVB Viewer

[EVB Viewer](https://github.com/evb0110/evb-viewer) is my open-source application for reading and editing PDF and DjVu files on macOS, Windows, Linux and the web. The desktop version adds OCR and annotation. Its main feature is the AI assistant I built into it: it answers questions about the open document in minutes that would otherwise take hours of tedious reading, and it does the manual work too, such as rebuilding a book's outline from the printed table of contents or finding every mention of a term across a scanned volume. It runs on the user's own ChatGPT or Claude subscription through the Codex app-server and the Claude Agent SDK, so the app ships no API key of its own. The same tools, about 28 of them, are exposed through a local MCP server, so Claude Code, Cursor or any MCP client can drive the viewer.

[Website](https://evb-viewer.com) · [Try it in the browser](https://web.evb-viewer.com)

## Tools for humanities research

- [Thompson Motif-Index](https://github.com/evb0110/thompson-motif-index): a searchable interface for all 47,431 motifs of Stith Thompson's Motif-Index of Folk Literature (Vue).
- [Turoyo Verb Glossary](https://turoyo-verb-glossary.vercel.app/): 1,696 Turoyo verbs with conjugation tables and etymology.
- [Comma](https://github.com/evb0110/comma): converts large TEI XML manuscripts to DOCX and PDF (Nuxt, TypeScript).
- [Diacritics Editor](https://diacritics-editor.vercel.app/): a rich-text editor for multilingual text with diacritical marks (Nuxt 4, TipTap).
- [Modern Western Aramaic Dictionary](https://github.com/evb0110/mwa-dictionary): dictionary search for Modern Western Aramaic (Vue).
- Older Raku tools for Syriac and Turoyo corpora: [Syriac transliteration](https://github.com/evb0110/Syriac-to-translit), [Turoyo corpus statistics](https://github.com/evb0110/turoyo_new_statistics).
