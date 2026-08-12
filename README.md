# College Mantra — link hub

Live page: https://shivee999.github.io/college-mantra/

## How to add a link

Open `links.json` in this repo, click the pencil icon (top right of the file view),
add a new entry to the array, and commit to `main`. It goes live in 1–2 minutes.

```json
{
  "name": "Website",
  "url": "https://example.com",
  "tag": "Live",
  "desc": "One short line describing this link.",
  "image": ""
}
```

- `image` is optional. Leave it `""` and the site shows a two-letter tile instead —
  it will never show a broken image icon.
- `tag` is optional. Defaults to "Live" if left out.
- Order in the JSON array = order on the page.

No HTML editing required for adding links — just this one file.
