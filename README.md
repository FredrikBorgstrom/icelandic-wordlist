# Icelandic Word List

A filtered Icelandic word list derived from **BÍN** (Beygingarlýsing íslensks nútímamáls — Database of Modern Icelandic Inflections), published by the [Árni Magnússon Institute for Icelandic Studies](https://bin.arnastofnun.is).

## Contents

- **`words_is-IS.txt`** — 2,955,060 Icelandic word forms, one per line, UTF-8. Longest word: 32 letters.

## Sources

Two BÍN-derived sources are combined:

1. **Netskrafl** ([mideind/Netskrafl](https://github.com/mideind/Netskrafl)) — ~2.77M fully-inflected word forms (3–15 chars)
2. **islenska** ([PyPI](https://pypi.org/project/islenska/)) — BÍN data compiled by Mideind ehf., used to add word forms longer than 15 characters

## Filtering

- Only words containing valid Icelandic characters: `a á b d ð e é f g h i í j k l m n o ó p r s t u ú v x y ý þ æ ö`
- Minimum word length: 3 letters, no maximum
- No proper nouns
- No words with triple repeated characters (e.g. `aaa`)

## License

**CC BY-SA 4.0** — Attribution-ShareAlike 4.0 International

This word list is a derivative of BÍN data. You are free to use, share, and adapt it, provided you give appropriate credit and distribute any derivative works under the same license.

**Attribution:** Beygingarlýsing íslensks nútímamáls (BÍN), Stofnun Árna Magnússonar í íslenskum fræðum — https://bin.arnastofnun.is
