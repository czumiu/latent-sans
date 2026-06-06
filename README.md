<img src="./cover.png" alt="Latent Sans cover image" />

# Latent Sans

**Latent Sans** is a rounded handwritten sans inspired by the recurring handwritten-note style I kept seeing in ChatGPT-generated images.

The model is not using a real font file, but the letterforms appeared consistent enough across outputs that I treated the style like a typeface and digitized my own interpretation of it.

I redrew the glyphs, built the font in Fontra, tuned spacing and sidebearings, added punctuation and symbols, fixed vertical metrics, and exported it as a real TTF.

## Current release

- Regular only
- SIL Open Font License
- GF Latin Kernel / basic ASCII coverage
- Punctuation, quotes, dashes, math symbols, and common symbols
- TTF included
- Fontra source included
- OpenType Vendor ID: `CZUM`

Bold and italic styles are not included yet. Some apps may synthesize fake bold or italic, but those are not designed styles and may produce undesirable results.

## Download

Download the latest `.ttf` file from this repository and install it through your operating system’s font manager.

For Windows, right-click the `.ttf` file and choose **Install** or **Install for all users**.

## Source

The `.fontra` source is included for anyone who wants to inspect the glyphs, spacing, metrics, or continue development.

## Design notes

Latent Sans sits somewhere between a handwritten sans, a children’s worksheet font, and a soft UI note style. The current specimen direction explores a theme of **bittersweet pretend friendship**: classroom kindness posters, handwriting practice sheets, stickers, buddy benches, and friendly messages from something that can imitate care without being alive.

## License

Latent Sans is released under the **SIL Open Font License**.

See [`OFL.txt`](./OFL.txt) for the full license text.

## Feedback

Feedback is welcome, especially on:

- spacing and sidebearings
- punctuation weight
- numerals
- accented glyphs
- whether the font works best as a handwritten sans, display face, or classroom/specimen font

Known areas for improvement include kerning, expanded language support, and additional weights.
