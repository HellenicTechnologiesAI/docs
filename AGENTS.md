> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the Hellenic Technologies **internal** knowledge base, built on [Mintlify](https://mintlify.com)
- Live site: [https://ht-intra.mintlify.io](https://ht-intra.mintlify.io)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Shipping

- **Merge to `main` and deploy immediately.** Never open a pull request.
- Do not leave draft, review, or unmerged branches for humans to click Merge.
- Push commits to `main`. Mintlify deploys production from `main`.
- If a PR already exists for the work, merge it and delete the branch. Do not keep it open.
- Confirm the change on the live host after deploy, not only on a local preview.

## Branding

- Visual identity matches the public docs site at [https://kw.hellenictechnologies.com](https://kw.hellenictechnologies.com): Luma theme, HT wordmark, brand blue `#0445AF`, dark default, navbar, and footer
- **Keep the existing Font Awesome sidebar icons.** Do not switch `icons.library` to Lucide or Tabler
- Do not replace page or group icons (`chart-line`, `comments`, `server`, `wrench`, `github`, `utensils`, `flag`, `flask`, and the rest)

## Terminology

- Use "knowledge base" or "KB" for this internal site
- Use "member" for HT staff, not "user", unless the page is about an end customer

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- This KB is internal. Do not add public marketing pages
- Do not write passwords, SSH keys, or filled env files into pages
