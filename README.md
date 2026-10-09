# Umain US homepage prototype

A working prototype of the homepage for Umain's US launch, made for internal review. It is not a production site.

- **Live site:** https://billywcollins.github.io/new-crew/
- **Design brief:** [Umain US Homepage Brief](https://claude.ai/code/artifact/079d1947-8478-4edf-9463-a5be1c39d4a2) (private, ask for access)
- **Earlier direction:** [v1.html](v1.html), kept for comparison

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The homepage. One self-contained file: markup, styles and scripts. Fonts load from Google Fonts. |
| `assets/` | Product shots, team photos, partner logos and two short video clips, taken from umain.com as stand-ins. |
| `v1.html` | The first, more systematic direction. |
| `robots.txt` | Asks search engines not to index the site. Both pages also carry a `noindex` tag. |

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Before anything goes further

- Client results come from the [Eidra.Punchkick work page](https://eidra.punchkick.com/work) and haven't been cleared for public use in the US.
- Imagery and video are placeholders from [umain.com](https://www.umain.com) and aren't tied to the cases they sit next to.
- Case study links show a "not built yet" note.
