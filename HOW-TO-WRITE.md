# How to write on your site

## Write a new post
1. Open the `_posts` folder in GitHub → Add file → Create new file.
2. Name it like `2026-11-20-my-post-title.md` (date first, then words with dashes).
3. Copy the top part (between the two `---` lines) from an existing post, change the title, description and topic.
4. Write below it. Use the Preview tab to see how it looks. Commit changes. It's live in about a minute.

## Edit a page
Open `about.md`, `projects.md`, `contact.md`, `journey.md` or `index.md` → pencil icon → change the text → Commit.
(Leave the lines between `---` at the top as they are, except the title.)

## Formatting
| You type | You get |
|---|---|
| `# Title` | Big title |
| `## Heading` | Section heading |
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `- item` | bullet point |
| `1. item` | numbered list |
| `[words](https://link)` | a link |
| `![description](/images/pic.png)` | a picture (upload it to the `images` folder first) |
| `> text` | highlighted quote |

## Hide a post you're still writing
Add `published: false` in the top part. Remove it when ready.

## Contact form
Sign up free at formspree.io, create a form, and replace YOUR_FORM_ID in `contact.md`.

## Going live (one time)
GitHub repo (Public) → upload everything here → Settings → Pages → Deploy from branch `main`, root.
Then in Namecheap Advanced DNS add GitHub's four A records for `@` and a CNAME `www` → `maisu10193.github.io.`
(check the current IPs on GitHub's "custom domain" help page). Then tick Enforce HTTPS.
