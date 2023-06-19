# Doom Scribe
Gelasio variant font, with modified letter glyphs and punctuation, intended to be highly readable with a small footprint, 70KB in total. Pre-subsetted for latin, see usage for valid glyph ranges.

![](https://github.com/metaexpression/doom-scribe/blob/0c4a75f6c207a62885cb6fb17cae3b94d4500547/screenshot-1.png)
![](https://github.com/metaexpression/doom-scribe/blob/0c4a75f6c207a62885cb6fb17cae3b94d4500547/screenshot-2.png)

## usage

```
@font-face {
  font-family: 'Doom Scribe';
  font-style: normal;
  font-weight: 400;
  src: url(/fonts/doom-scribe-regular.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+2190-2199, U+2000-2029;
}

@font-face {
  font-family: 'Doom Scribe';
  font-style: italic;
  font-weight: 400;
  src: url(/fonts/doom-scribe-italic.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+2190-2199, U+2000-2029;
}

@font-face {
  font-family: 'Doom Scribe';
  font-style: normal;
  font-weight: 600;
  src: url(/fonts/doom-scribe-semibold.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+2190-2199, U+2000-2029;
}
```
