<p align="center">
  <img src="assets/icon.png" alt="ArticleHelper" width="140">
</p>

<h1 align="center">ArticleHelper</h1>

<p align="center">
  Write, organise and publish CivitAI articles and bounties — from your own machine.<br>
  Free, offline, no account.
</p>

<p align="center">
  <a href="https://github.com/valerie-4659/articlehelper-app/releases/latest"><b>⬇ Download</b></a> ·
  <a href="https://github.com/valerie-4659/articlehelper-app/wiki">Wiki</a> ·
  <a href="https://github.com/valerie-4659/articlehelper-app/issues">Report a problem</a>
</p>

---

## What it does

CivitAI's article editor is a browser text box. It has no drafts you can trust, no version
history, no way to reuse a heading style across twenty articles, and nothing at all for
keeping a series straight. This is a desktop application for the writing part, which then
hands the finished thing over.

### Writing

| | |
|---|---|
| **Markdown editor** | Full toolbar, live preview beside it, autosave |
| **Heading style guide** | Define colour, font and Unicode style per heading level once — applied automatically on export |
| **Unicode fonts** | Script, bold, fraktur, monospace for headings, so your articles are recognisable at a glance |
| **Save history** | Versions per article, restorable at any point |
| **Translations** | Several language versions of one article, switched by a click. Untranslated lines are highlighted |
| **Series** | Group articles, navigate with prev/next, split one long piece into parts at the cursor |
| **Search & replace** | `Ctrl+F` in the editor, case toggle, replace one or all |

### Images

Preview image with a built-in 850×400 crop tool, an image pool you click into the text, and
an export that gives you only the images the article actually uses — in the order they appear,
preview first.

### Publishing to CivitAI

**Copy HTML** puts the whole article on the clipboard as formatted HTML, heading styles
already inlined. Paste it into CivitAI's editor and you are done — no restyling on the other
side.

### Universes

A planning canvas for story worlds: drag story nodes around, connect them, group them into
coloured arcs. Character cards with portraits, roles and appearances. Locations and
world-building notes, searchable, with an auto-layout button when the canvas gets away from
you.

### Bounties

Import entries by drag and drop, file picker, `Ctrl+V`, or straight from a CivitAI URL —
image and author are fetched for you. **Fetch All** pulls every submission of a bounty at
once. Rate entries, leave notes, then assign winners by dragging; the placements below shift
themselves.

## Install

Download the file for your system from the
[latest release](https://github.com/valerie-4659/articlehelper-app/releases/latest).

| System | File |
|---|---|
| macOS | `.dmg` |
| Windows | `.exe` |
| Linux | `.AppImage` |

### The first launch will warn you

These builds are not code-signed, so your system does not recognise the publisher.

- **macOS** — right-click the app, choose **Open**, then confirm. Once is enough.
- **Windows** — SmartScreen shows a blue box. **More info** → **Run anyway**.

The warning is about a missing certificate, not about the file.

## Privacy

Your articles, images, universes and bounty entries live on your machine. There is no
account, no sync and no telemetry.

The application reaches the network when you ask it to: fetching a bounty entry or an author
from CivitAI by URL, and posting where you tell it to. Nothing is uploaded on its own — even
publishing an article is a clipboard hand-off you paste yourself.

## Something broken?

[Open an issue](https://github.com/valerie-4659/articlehelper-app/issues/new) with your
platform, the version, and what you did just before it went wrong.

## About this repository

This is where the releases, the wiki and the issue tracker live. The source is not public.

---

<p align="center"><sub>Built by Valerie</sub></p>
