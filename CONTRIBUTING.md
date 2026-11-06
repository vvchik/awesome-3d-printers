# Contributing

Pull requests and issues are welcome. The fastest way to suggest a printer is the [Add a printer](https://github.com/vvchik/awesome-3d-printers/issues/new?template=add-printer.yml) form. The fastest way to report a wrong number is the [Fix a row](https://github.com/vvchik/awesome-3d-printers/issues/new?template=fix-row.yml) form. A project page and one sentence are enough to start. The maintainer fills the rest.

## What belongs in the catalog

To get a row, a printer must meet all of these rules:

- It is a whole FDM printer, not a mod or a toolchanger add-on.
- The author publishes the files for free. Files in a closed chat group, behind a payment, or re-uploaded by someone else do not count.
- A BOM exists. Build instructions exist too, as files or inside a manual, README, wiki, or build log. A build video, or a full CAD assembly that other people already built from, can replace them.
- The license allows other people to build it.
- At least one person other than the author built it.
- It is not a variant of a design that is already listed. Variants and sizes of the same design share a row.

If the design files and firmware of a commercial machine are public, it is included. Conversions of existing printers go to [Conversions](README.md#conversions). An unusual design without files or builds, not a plain CoreXY or bedslinger, goes to [Concepts and prototypes](README.md#concepts-and-prototypes). A design without an active group goes to [Legacy designs](README.md#legacy-designs).

Not accepted: homepages or shops instead of project pages, dead links, duplicates, and claims such as "best" or "cheapest".

## Adding a full row

Follow [Column notes](README.md#column-notes) for every column. Then:

1. Pick the table. Motion system first, then size group. If the design has no update since 2024-10 and no active group, use [Legacy designs](README.md#legacy-designs). If it shaped later printers and no longer gets updates, use [Historical designs](README.md#historical-designs).
2. Copy an existing row of that table and replace every cell. Keep the `<a id="slug">` anchor. The slug is lowercase with hyphens and is reused for the printer folder.
3. Sizes are in millimetres. Use `?` for an axis that you cannot confirm and `—` for no reliable figure.
4. Latest version: link the release, changelog, CAD commit, or file upload that proves the date.
5. Counts: only the creator's own pages and videos. For a GitHub repository, copy the star badge from an existing row and change the repository path.
6. Sort the row by GitHub stars, highest first. A row with no repository sorts by its highest like count. Rows with no counts go last.

## Adding the printer page and pictures

1. Create `printers/<slug>/README.md` from an existing page. It repeats the row as a field table and lists all pictures.
2. Name pictures `0-<slug>.jpg`, `1-<slug>.jpg`, and so on. `0-` is the main picture shown in the catalog and the gallery. Keep each picture under 800 px on the long side.
3. Credit every picture to its author on the printer page, with a link to where it was published. Pictures keep their authors' rights. See [picture credits](GALLERY.md#picture-credits).
4. Add the printer to [GALLERY.md](GALLERY.md) in the same section as its row.

## Fixing a row

Open a [Fix a row](https://github.com/vvchik/awesome-3d-printers/issues/new?template=fix-row.yml) issue with the correct value and a source link, or send a pull request that changes only that cell.

## License

Text contributions are released under [CC BY 4.0](LICENSE). Pictures are not. The author keeps all rights, and the credit on the printer page is the condition of use.
