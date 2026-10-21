# Update the Groups column

Refresh the builder communities for every printer row in `README.md`.

## Scope

- Process every catalog row. A row starts with `| 📷 | <a id="...">`.
- Find columns by header name (`Groups`), not by position. Tables in "Other motion systems" and "Concepts and prototypes" have an extra `Build type` column.
- Change only the `Groups` cells and the checked date in the `**Groups:**` paragraph under "Column notes".

## What to find

- Find communities for the printer, its family, or its creator. Do not list general communities such as r/3Dprinting.
- Search Discord, Facebook groups, Telegram, Reddit, forums, and Google Groups.
- Search in English, Spanish, and other large languages (German, French, Portuguese, Russian, Italian, Turkish, Chinese).
- Look for links in the project README, docs, PDF manuals, the creator's website, and the creator's YouTube channel description.

## How to read member counts

- Discord: `https://discord.com/api/v10/invites/<code>?with_counts=true`, field `approximate_member_count`.
- Telegram: the number on the public `https://t.me/<name>` page.
- Reddit: the subscriber count in the sidebar. If reddit.com blocks the request, use a Redlib mirror.
- Facebook: the "total members" figure on the group's `/about` page. This page needs a logged-in browser session. Read it only. Do not join or click anything.
- Forums: if the forum shows a member count, use it.
- If a platform hides the count, show no number. Never guess a count.

## Rules for the cell

1. Put official communities first. Then sort by member count, largest first.
2. Drop a group that has less than 10% of the members of the largest group on the same platform and language. Keep a group that is specific to this printer model.
3. Drop a group with fewer than 100 members, unless it is specific to this printer model.
4. Mark a group with 1,000 or more members and no posts in the last year as `inactive`. Drop smaller inactive groups.
5. Show at most 10 groups.
6. Write each group as `[Platform](url) LANG count`. Use only the platform name for the link text: `Discord`, `Facebook`, `Telegram`, `Reddit`, `Forum`, or `Google Groups`. If the group is inactive, put `inactive` after the count.
7. Join groups with `<br>`. Do not use `·`.
8. Round counts. Under 1,000, show the exact number. Under 100,000, show one decimal and `K`, and drop `.0` (`1.4K`, `15K`). From 100,000, show whole `K` (`257K`). From 1,000,000, show one decimal and `M`.
9. If no group exists for the printer, family, or creator, write `—`.

Example: `[Discord](https://discord.gg/voron) EN 40.8K<br>[Facebook](https://www.facebook.com/groups/479932403103163/) DE 2.6K`

## Output

- Update the cells and the checked date in "Column notes".
- Write `COMMUNITIES-REVIEW.md` with one section per printer: the current cell, the new cell, and each group with its source URL, the place where you found it, and the count.
- Open a pull request. Do not push to `main`.
