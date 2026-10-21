# Update the Latest version column

Refresh the date of the latest public revision for every printer row in `README.md`.

## Scope

- Process every catalog row. A row starts with `| 📷 | <a id="...">`.
- Find columns by header name (`Latest version`), not by position.
- Change only the `Latest version` cells.

## Which date to use

Use the first source in this list that exists:

1. A tagged release (GitHub release or tag) or a dated changelog entry. Changelogs can be on the project site, in the repo, or in the Thingiverse "Thing details" or description.
2. The last commit that changed the design files on GitHub. Find the design folders by name, such as `CAD`, `STEP`, `STL`, `cad`, `step`, `stl`, `Printed Parts`, or `Models`. Use `gh api "repos/<owner>/<repo>/commits?path=<folder>&per_page=1"`. Ignore commits that change only docs, images, or firmware.
3. The newest design file upload on Printables or Thingiverse. Read the per-file dates (Printables GraphQL `stls{created}` and `otherFiles{created}`, or the Thingiverse files tab "Updated" dates).
4. The first publication date of the linked page.

Also apply these rules:

- If a tagged release exists, keep it, even when a later commit changed the CAD without a new version.
- If no file changed on a page "updated" date, ignore that date. Edits to page text are not a new revision.
- Use the page that the row links to. Do not use a later design with a different name.
- If the original source is lost, write `—`.

## Cell format

Write `<label><br>[YYYY-MM](<source URL>)`. Find the exact day, and keep it in the review file, but show only the year and month in the cell.

Labels:

- The version name, for example `V2.4r2` or `Rev E`: a tagged release or named revision.
- `Log`: a dated changelog entry.
- `CAD` or `STEP`: a commit to the design files.
- `Files`: a design file upload.
- `Update`: a dated page or file update with no version name.
- `First release`: the first publication.
- `First video`: a design with no public files, dated by its first video.

- Keep labels short. Do not repeat the printer name in the label.
- If the source gives only a year, write `YYYY`.

## Output

- Write `RELEASES-REVIEW.md` with one section per printer: the current cell, the new cell, the kind of source, a quote or commit message as proof, and notes on rejected dates.
- Open a pull request. Do not push to `main`.
