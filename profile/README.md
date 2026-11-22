# Rosmaryn

**Holistic self-knowledge: Human Design, astrology and numerology, in six languages.**

[![Website](https://img.shields.io/badge/website-rosmaryn.app-1b2b32)](https://rosmaryn.app/)
[![npm](https://img.shields.io/npm/v/rosmaryn-open-data?label=npm%20rosmaryn-open-data)](https://www.npmjs.com/package/rosmaryn-open-data)
[![Data licence: CC BY 4.0](https://img.shields.io/badge/data-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)
[![mcptry](https://mcptry.com/badge/app.rosmaryn/encyclopedia)](https://mcptry.com/servers/app.rosmaryn/encyclopedia)

Rosmaryn is a holistic self-knowledge platform that brings together Human Design, astrology and numerology. It offers free calculators, an encyclopedia, software for practitioners, online courses and a library of esoteric books, in French, English, German, Spanish, Italian and Brazilian Portuguese.

Charts are computed by Rosmaryn's own engine, from NASA JPL ephemerides, directly in the visitor's browser: the birth date is not sent to a third party.

## Rosmaryn websites

| Website | What you will find |
|---|---|
| [rosmaryn.app](https://rosmaryn.app/) | Free Human Design Body Graph, birth chart, transits, compatibility and life path calculators, and an encyclopedia of Human Design, astrology and numerology |
| [Rosmaryn Pro](https://rosmaryn.pro/) | Online software for astrology, Human Design and numerology practitioners: charts with interpretations, client files, booking, branded PDF reports |
| [Rosmaryn Academy](https://academy.rosmaryn.app/) | Online courses in Human Design and astrology |
| [Rosmaryn Library](https://library.rosmaryn.app/) | A bookshop and library of esotericism, from new titles to public domain books |

## Open data

Explore the datasets online: **[rosmaryn-dev.github.io/rosmaryn-open-data](https://rosmaryn-dev.github.io/rosmaryn-open-data/)**

| Dataset | Where |
|---|---|
| Public domain esoteric books (3,296 records, 33 languages, 42 subjects) | [data.gouv.fr](https://www.data.gouv.fr/datasets/rosmaryn-library-ouvrages-esoteriques-du-domaine-public-et-articles-en-libre-acces) · [Hugging Face](https://huggingface.co/datasets/Rosmaryn/esoteric-public-domain-books) · [GitHub](https://github.com/Rosmaryn-Dev/rosmaryn-open-data) |
| Human Design and astrology frequencies in 100,000 births | [Hugging Face](https://huggingface.co/datasets/Rosmaryn/human-design-astrology-frequencies-100k-births) · [GitHub](https://github.com/Rosmaryn-Dev/rosmaryn-open-data) |
| Concordance of angels and demons (Book of Enoch, Key of Solomon, Goetia) | [Rosmaryn Library](https://library.rosmaryn.app/concordance/anges-et-demons/) · [GitHub](https://github.com/Rosmaryn-Dev/rosmaryn-open-data) |

All datasets are published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Rosmaryn with a link.

The same datasets as a JavaScript package:

```bash
npm install rosmaryn-open-data
```

## For AI assistants: MCP server

Rosmaryn runs a public [Model Context Protocol](https://modelcontextprotocol.io/) server, listed in the official MCP Registry as `app.rosmaryn/encyclopedia`. AI assistants can search the encyclopedia and cite its pages, list the free calculators, and get upcoming Moon phases, eclipses, ingresses and retrogrades, in six languages.

```
https://rosmaryn.app/wp-json/rosmaryn/v1/mcp
```

Streamable HTTP, no authentication.

## Sky calendars

Moon phases, eclipses, planets entering signs and retrogrades, as calendars you can subscribe to in Google Calendar, Apple Calendar or Outlook, in six languages: see [Astrological transits](https://rosmaryn.app/en/astrologie/transits/).

## Browser extension

[Rosmaryn Holistic Addon](https://addons.mozilla.org/firefox/addon/rosmaryn-holistic-addon/) for Firefox and Firefox for Android: select a birth date on any page to see the sun sign, then open the birth chart or the Human Design Body Graph on Rosmaryn. Source: [rosmaryn-holistic-addon](https://github.com/Rosmaryn-Dev/rosmaryn-holistic-addon).

## Cite Rosmaryn

Rosmaryn (2026). *Rosmaryn open data*. https://github.com/Rosmaryn-Dev/rosmaryn-open-data. Licence CC BY 4.0.

## Find Rosmaryn

[rosmaryn.app](https://rosmaryn.app/) · [data.gouv.fr](https://www.data.gouv.fr/organizations/rosmaryn/) · [Hugging Face](https://huggingface.co/Rosmaryn) · [npm](https://www.npmjs.com/~rosmaryn) · [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=app.rosmaryn)
