# Contributing

Pull requests and issues are welcome. The fastest way to suggest a printer is the [Add a printer](https://github.com/vvchik/awesome-3d-printers/issues/new?template=add-printer.yml) form. The fastest way to report a wrong number is the [Fix a row](https://github.com/vvchik/awesome-3d-printers/issues/new?template=fix-row.yml) form. A project page and one sentence are enough to start; the maintainer fills the rest.

## What belongs in the catalog

- Open-design FDM printers with published files that you can build, modify, or study.
- One row per design. Variants and sizes of the same design share a row.
- Commercial machines only when the design files and firmware are public.
- Conversions of existing printers go to [Conversions](README.md#conversions). Designs that stopped before a buildable release go to [Concepts and prototypes](README.md#concepts-and-prototypes).

Not accepted: homepages or shops instead of project pages, dead links, duplicates, and claims such as "best" or "cheapest".

## Adding a full row

Follow [Column notes](README.md#column-notes) for every column. Then:

1. Pick the table. Motion system first, then size group. If the design has no update since 2024-10 and no active group, use [Legacy designs](README.md#legacy-designs). If it shaped later printers and no longer gets updates, use [Historical designs](README.md#historical-designs).
2. Copy an existing row of that table and replace every cell. Keep the `<a id="slug">` anchor; the slug is lowercase with hyphens and is reused for the printer folder.
3. Sizes are in millimetres. Use `?` for an axis you could not confirm and `—` for no reliable figure.
4. Latest version: link the release, changelog, CAD commit, or file upload that proves the date.
5. Counts: only the creator's own pages and videos. For a GitHub repository, copy the star badge from an existing row and change the repository path.
6. Sort the row by GitHub stars, highest first. A row with no repository sorts by its highest like count. Rows with no counts go last.

## Adding the printer page and pictures

1. Create `printers/<slug>/README.md` from an existing page. It repeats the row as a field table and lists all pictures.
2. Name pictures `0-<slug>.jpg`, `1-<slug>.jpg`, and so on. `0-` is the main picture shown in the catalog and the gallery. Keep each picture under 800 px on the long side.
3. Credit every picture to its author on the printer page, with a link to where it was published. Pictures keep their authors' rights; see [picture credits](GALLERY.md#picture-credits).
4. Add the printer to [GALLERY.md](GALLERY.md) in the same section as its row.

## Fixing a row

Open a [Fix a row](https://github.com/vvchik/awesome-3d-printers/issues/new?template=fix-row.yml) issue with the correct value and a source link, or send a pull request that changes only that cell.

## License

Text contributions are released under [CC0 1.0](LICENSE). Pictures are not; the author keeps all rights, and the credit on the printer page is the condition of use.
