# Publishing Sinhabahu from Ulysses

Sinhabahu is built automatically whenever a Markdown article is pushed to the `main` branch. Keep essays in `content/posts/` and use the front matter in `_template.md`.

## Mac

1. Install GitHub Desktop and clone `Sinhabahu-V/Sinhabahu-V.github.io`.
2. In Ulysses, choose **File → Add External Folder**, then select `content/posts` inside the clone.
3. Duplicate `_template.md`, rename it `YYYY-MM-DD-short-title.md`, and write the essay.
4. Keep `draft: true` while writing. Change it to `draft: false` when ready.
5. In GitHub Desktop, commit with `Publish: Article title`, then select **Push origin**.

## iPhone and iPad

1. Install Working Copy and clone `Sinhabahu-V/Sinhabahu-V.github.io`.
2. In Ulysses, add an external folder through **On My iPhone/iPad → Working Copy → Sinhabahu-V.github.io → content → posts**.
3. Duplicate `_template.md`, give it a dated filename, and write in Ulysses.
4. Change `draft: true` to `draft: false` when ready.
5. Open Working Copy, commit the article, then push it to GitHub.

## Metadata

- `title`: headline.
- `date`: publication date and time; use `+05:30` for Sri Lanka.
- `draft`: `true` hides the article; `false` publishes it.
- `description`: one concise homepage and search-preview sentence.
- `categories`: one main section, such as `Strategy`, `Sri Lanka`, or `Indo-Pacific`.
- `tags`: specific subjects, people, places, or concepts.

The website normally updates within a few minutes. GitHub's **Actions** tab shows publishing progress.
