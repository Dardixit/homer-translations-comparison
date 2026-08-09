# Ὀδύσσεια · Odyssey · Одиссея

A parallel reader for Homer's *Odyssey*: the ancient Greek original, A. T. Murray's
English translation, and V. A. Zhukovsky's Russian translation, aligned line by line
in three synchronized columns. Styled after Attic red-figure stamnos vases
(the "Siren Vase", British Museum E440).

**Live version:** https://dardixit.github.io/odyssey-translation-comparison/

## Features

- All 24 books, aligned by canonical line numbers in 5-line blocks
- Book navigation (α′–ω′), go-to-line, deep links (`#9.105`)
- Column toggles (ΕΛ / EN / РУ), click-to-pin rows
- Red-figure (dark) and black-figure (light) themes, following your system
  preference with a manual toggle
- Vase paintings of each book's episode with trilingual captions and museum
  attribution

## Texts

| Language | Source | License |
|---|---|---|
| Ancient Greek | Homer, *Odyssey* — Perseus Digital Library ([perseus-grc2](https://github.com/PerseusDL/canonical-greekLit)) | CC BY-SA 4.0 |
| English | A. T. Murray, 1919 (Loeb Classical Library, via Perseus) | Public domain |
| Russian | В. А. Жуковский, 1849 ([az.lib.ru](http://az.lib.ru/g/gomer/text_0060.shtml)) | Public domain |

## Images

Vase photographs are embedded from Wikimedia Commons; each caption in the app names
the object, museum, photographer, and license (public domain, CC0, CC BY 2.0,
CC BY-SA 2.0, or CC BY-SA 4.0).

## Running locally

Any static file server works:

```bash
python3 -m http.server 8377
```

then open http://localhost:8377.

## License

Code: MIT (see LICENSE). Texts and images: see the tables above — the ancient Greek
text and the CC-licensed photographs require attribution as given in the app's
captions and this README.
