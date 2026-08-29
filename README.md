# Epic F.A.I.L. — web archive

Published episodes of the Epic F.A.I.L. comic. Each episode is one image
(the three-panel strip with its paired F.A.I.L. facts poster as the
fourth screen) plus a JSON file with the dialogue transcript and the
poster text.

- `index.json` — list of all episodes (id, image, texts, title)
- `<n>.jpg` — the episode image
- `<n>.json` — the episode texts

Fetch via raw URLs, e.g.:

```
https://raw.githubusercontent.com/storax-io/epicfail-public/main/index.json
https://raw.githubusercontent.com/storax-io/epicfail-public/main/17.jpg
```

or through the jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/storax-io/epicfail-public@main/17.jpg
```

This repository is generated automatically from a private source
repository — do not open pull requests here. See LICENSE: all rights
reserved; this is not open-content material. Syndication inquiries:
henri.sundelin@stor.ax
