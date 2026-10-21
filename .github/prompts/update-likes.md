# Update the Stars Likes Views column

Refresh the popularity counts for every printer row in `README.md`.

## Scope

- Process every catalog row. A row starts with `| 📷 | <a id="...">`.
- Find columns by header name (`Stars Likes Views`), not by position.
- Change only the `Stars Likes Views` cells and the checked date in the `**Stars Likes Views:**` paragraph under "Column notes".

## What to count

- Count only pages and videos by the design's author or official team account.
- Do not count re-uploads by other people, remixes, mods, copies, build logs, or automatic imports. Thangs and Cults3D often mirror Thingiverse. If the author claimed a mirror, it counts.
- To accept an account, find proof. Good proof is one of these:
  - The same handle as the creator's other accounts.
  - A profile link to the creator's site, GitHub, or YouTube.
  - A link from the project docs to the page.
- If the author has several pages on one platform, use the page with the most likes.

## Sources

- ⭐ GitHub stars: do not read them. The badge updates by itself.
- 💙 Thingiverse likes: the page needs JavaScript. Use a browser, or the Thingiverse API with a token.
- 🧡 Printables likes: GraphQL at `https://api.printables.com/graphql/`, field `likesCount`.
- 💚 MakerWorld likes: the site blocks plain requests. Use a browser.
- 💛 Cults3D likes: use a browser or a plain request.
- 🤍 MyMiniFactory likes: search results need a logged-in browser session.
- Thangs: search it too. If the author has a page there, add a new mark and explain it in "Column notes".
- ⏯️ YouTube views: the author's most-viewed video about this printer.

- For YouTube, list the author's channel with `yt-dlp --flat-playlist --print "%(id)s|%(view_count)s|%(title)s" "<channel URL>/videos"`. Pick the video with the most views that is clearly about this printer or its variant. If YouTube blocks the request, add `--extractor-args youtube:player_client=mweb`, wait, and retry.
- Report likes on model sites, not downloads, collections, or boosts.
- Never guess a number. If you cannot read a page, keep the old value and say so in the review file.
- Never click like, follow, download, or log in. If a site shows a CAPTCHA, stop using that site.

## Cell format

1. Keep the GitHub star entry exactly as it is: a light gray live badge with a gold star icon, linked to the repository. Copy the `logo=` value from an existing row. Do not put a ⭐ emoji before the badge, because the line breaks between an emoji and an image:
   `[![GitHub stars](https://img.shields.io/github/stars/<owner>/<repo>?style=flat-square&label=&color=d0d7de&logo=<star icon>)](https://github.com/<owner>/<repo>)`
2. After the star entry, add one entry per platform in this order: 💙, 🧡, 💚, 💛, 🤍, ⏯️.
3. Write each entry as `[<mark><count>](<url>)`. Put a word joiner (U+2060) between the mark and the count, so the line does not break there. For example `[🧡⁠1.8K](https://www.printables.com/model/...)`.
4. Join the star entry and the other entries with `<br>`.
5. Round counts the same way as the Groups column: `345`, `1.8K`, `15K`, `115K`, `1.2M`.
6. If nothing exists, write `—`.

## Output

- Update the cells and the checked date in "Column notes".
- Write `LIKES-REVIEW.md` with one section per printer: the current cell, the new cell, each page with its account and author proof, the chosen video with its channel, and rejected candidates.
- Open a pull request. Do not push to `main`.
