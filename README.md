# Ὅμηρος · Homer Translations Comparison

A parallel reader for Homer's **Iliad** and **Odyssey**: the ancient Greek text
beside public-domain translations into English, Finnish, and Russian, aligned
by canonical line numbers in five-line blocks. Styled after Attic red-figure
pottery (the "Siren Vase", British Museum E440).

**Live version:** https://dardixit.github.io/odyssey-translation-comparison/

## Features

- Both poems, all 24 books each, with a work switcher (Ἰλιάς / Ὀδύσσεια)
- Any combination of versions, toggleable per column
- Diacritic-insensitive word search across the whole poem in every language
- Hover dictionary for the Greek text: inflected forms resolved to their
  dictionary form with an expandable Ancient Greek → English article
  (Wiktionary REST API; requires an internet connection), with onward links
  to [Logeion](https://logeion.uchicago.edu/) (LSJ and the other classical
  lexica) for every word
- Vase paintings and classical artworks for key episodes, with trilingual
  captions and full museum/photo attribution
- Red-figure (dark) and black-figure (light) themes; deep links like `#il.16.676`

## Texts

| Work | Language | Translation | Source | License |
|---|---|---|---|---|
| both | Ancient Greek | — | [Perseus Digital Library](https://github.com/PerseusDL/canonical-greekLit) | CC BY-SA 4.0 |
| both | English | Alexander Pope (1715–20 / 1725–26) | Project Gutenberg | Public domain |
| both | English | Samuel Butler (1898 / 1900) | Perseus | Public domain |
| both | English | A. T. Murray (1924 / 1919, Loeb) | Perseus | Public domain |
| both | Finnish | Otto Manninen (1919 / 1924) | Internet Archive scan (WSOY 1941), OCR | Public domain |
| Iliad | Russian | Н. И. Гнедич (1829) | az.lib.ru | Public domain |
| Odyssey | Russian | В. А. Жуковский (1849) | az.lib.ru | Public domain |
| both | Russian | В. В. Вересаев (1949 / 1953) | az.lib.ru | Public domain |

Pope's couplets do not correspond line-for-line to the Greek; his text is
distributed proportionally across the line blocks. The Finnish text is OCR
from a 1941 printing and may retain scanning errors.

Translations still under copyright (Lattimore, Fitzgerald, Fagles, Wilson,
Saarikoski, Castrén, and others) cannot be republished here; the in-app ⓘ
panel lists them explicitly.

## Images

Vase photographs and artwork images are embedded from Wikimedia Commons
(public domain, CC0, CC BY, or CC BY-SA); each caption names the object,
museum, photographer, and license.

## Running locally

```bash
python3 -m http.server 8377
```

then open http://localhost:8377.

## License

Code: MIT (see LICENSE). Texts and images: see the tables above.
