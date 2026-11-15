# Bible Languages Studio – personal copy (private)

**by Larry Dalton**

This repository is **private**. It holds my own copies of two English Bible translations and of the commentaries and
books I own, for [Bible Languages Studio](https://github.com/larrycd/bible-languages-studio), and a personal installer
that includes them. They are copyrighted and are for my own study only: **do not make this repository public, fork it,
or add collaborators.**

| | |
|---|---|
| `my-translations/ESV.json` | English Standard Version – ESV® Bible, © 2001 by Crossway |
| `my-translations/CSB.json` | Christian Standard Bible®, © 2017 by Holman Bible Publishers |
| `my-translations/*.json` (15 more) | My Galatians Bible Study and 14 commentaries and books (listed below) |
| `installer/bible-personal.nsi` | NSIS script for the personal installer (the public studio plus all of the above) |
| Releases | `BibleLanguagesStudio-Personal-Setup.exe` and `SHA256SUMS.txt` |

The ESV and CSB were converted on 14/11/2026 from my own PDF copies: all 66 books and 1,189 chapters of each, with
Psalm titles as verse 0 (matching the Hebrew).

## Commentaries and books (converted 15/11/2026, studio 1.0.5)

- My own **Galatians Bible Study** (Studies 1–7)
- A. Blake White, *The Abrahamic Promises in Galatians*; *What is New Covenant Theology?*
- Peter J. Gentry and Stephen J. Wellum, *God's Kingdom through God's Covenants*
- Stephen J. Wellum and Brent E. Parker (eds.), *Progressive Covenantalism*
- Brent E. Parker, *Christ Jesus the True Israel*
- Benjamin L. Merkle, *Discontinuity to Continuity*
- Jason C. Meyer, *The End of the Law*
- Gary D. Long, *New Covenant Theology: Time for a More Accurate Way*
- Trey Talley, *Sticks, Stones, Sabbaths and Sundays*
- John G. Reisinger, *The New Covenant Church (Ekklesia) of Christ*; *In Defense of Jesus, the New Lawgiver*;
  *Tablets of Stone*; *New Covenant Theology and Prophecy*; *Christ, Our New Covenant Prophet, Priest and King*

They appear in the **Commentary** panel below the Word panel. **All my books and commentaries** lists every place in
them that cites the passage being read (about 14,600 Scripture references, with their notes) and opens each at that
paragraph. They can be edited in the panel; each save keeps the previous version in a `backups` folder.

## Install on a new computer

1. Sign in to GitHub as larrycd, open **Releases** and download `BibleLanguagesStudio-Personal-Setup.exe`
   (latest: v1.0.5-personal).
2. Run it. It installs Bible Languages Studio 1.0.5 (per user, no administrator rights) and puts the translations,
   commentaries and books in `Documents\bible-languages-studio-my-translations`. A commentary that is already there
   (and may have been edited) is never replaced.
3. In the studio, choose ESV or CSB from the **English** menu, and a commentary or **All my books and commentaries**
   from the **Commentary** menu.

The public studio, its installer and its GitHub releases never contain any of these files.
