# Tesseract-MI prostate zone SVGs

Four hand-drawn slice diagrams used by the prostatecancer.ai zone selector.
This folder keeps the original SVG files. `png/` holds PNG renders of the same
files for `report.html`.

## Source

- Repository: https://github.com/Tesseract-MI/prostatecancer.ai
- Branch fetched: `master`
- Commit: `3e5d699f3972d1ceb5fa7b5010705643eae547ea` (the notes cite this as
  `3e5d699`, 2019-10-07). That commit is `master` HEAD. The four files were
  downloaded from
  `https://raw.githubusercontent.com/Tesseract-MI/prostatecancer.ai/master/public/images/`
  and their git blob ids match the blobs at that commit:
  - `apex.svg` — blob `70177f1d39f17b10ca6d595e17310f7a61dcfcfe` — upstream path `public/images/apex.svg`
  - `mid.svg` — blob `69e544099c066c40cc4a573579be3e1dcfe0ff8f` — upstream path `public/images/mid.svg`
  - `base.svg` — blob `4156437c5cfd8f7a17b34f76af3cfdf03bedfe47` — upstream path `public/images/base.svg`
  - `seminal_vesicles.svg` — blob `0954595fe85d424a8434b9047c0345153a27306c` — upstream path `public/images/seminal_vesicles.svg`

Each file’s header says it was created with Inkscape. Paths are clickable
(`onclick="top.notify(evt)"`) and use ids such as `R_PZpl`, `L_TZa`, and
`R_AS`. `R_CZ` is on the base slice. These are PI-RADS v2 drawings: they have
no base PZpm sectors (`base.svg` has no PZpm id). Apex and mid do label PZpm,
which v2 already had; v2.1 is the revision that adds base PZpm.

They were traced from the ACR PI-RADS v2 sector-map figure (the upstream file
`public/images/locations.png`). ACR licenses PI-RADS under CC BY-NC-ND 4.0, as
quoted at https://radiopaedia.org/cases/prostate-sector-map-pi-rads-v21, so
reuse of the derived artwork may carry that restriction.

## License

The upstream repository is MIT. Its `LICENSE` file reads:

```
MIT License

Copyright (c) 2018 ProstateWebViewer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

That text is the upstream `LICENSE` retrieved from
https://raw.githubusercontent.com/Tesseract-MI/prostatecancer.ai/master/LICENSE
(the same commit as the SVGs). The CC BY-NC-ND note above is separate: it is
about the ACR figure these drawings were traced from, not a replacement for
the MIT grant on the repository.
