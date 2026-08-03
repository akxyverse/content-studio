# Templates & Contributor Notes

Internal reference for maintaining this archive — not part of the visitor
experience. If you're browsing content, go back to the
[LinkedIn Posts gallery](../README.md).

## Structure

Posts are filed by publish date: `<Year>/<Month>/<YYYY-MM-DD>_<Post-Slug>/`.
Dates stay in the folder path for unambiguous, collision-free filing —
the gallery homepage is what visitors actually browse by category.

## What each post folder contains

| File | Purpose |
|---|---|
| `README.md` | Project documentation — Overview, Key Points/Business Problem, Skills, Repository Contents, Related LinkedIn Post, Related Repository, Version History. **Not** a copy of the LinkedIn post text — the thumbnail displays inline at the top |
| `linkedin-post.md` | The exact original post text, kept separately from the README |
| `linkedin-url.txt` | Link to the live LinkedIn post |
| `hashtags.md` | Hashtags used |
| `metadata.json` | Structured metadata (title, date, tool, category, tags) |
| `thumbnail.jpg` | The visual shared in the post — consistent filename across every post |
| `Source Files/` | Original workbook, dataset, PDF, or notes — wherever the source file exists |
| `comments.md` (optional) | Notable comments worth keeping |

Not every field will exist for every post — only what's genuinely on file
gets included. A missing source file is noted in the post's README, never
faked. Same for `metadata.json`'s optional fields, a README's Related
Repository/Related Content sections, and the archive as a whole: an entry
only gets created once the post's actual URL has been fetched and
verified — never backfilled from memory or assumption.

## Templates

One starting structure per post type:

- [`Dashboard-Post-Template.md`](./Dashboard-Post-Template.md)
- [`Guidebook-Template.md`](./Guidebook-Template.md)
- [`Carousel-Template.md`](./Carousel-Template.md)
- [`Resource-Post-Template.md`](./Resource-Post-Template.md)

---

[← Back to LinkedIn Posts](../README.md)
