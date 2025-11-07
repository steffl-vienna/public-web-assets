# Public Web Assets

- Store public assetes here.
- Use **versioned filenames** (e.g., `logo.steffl.v2.svg`) to force cache busting.
- Avoid query strings.
- Prefer **SVG**. Provide PNG fallback if needed.

## Update flowassetes
1. Add new file with incremented version.
2. Merge to `main`.
3. Update templates to the new filename.

## URLs
- With custom domain: `https://assets.steffl-vienna.at/public-web-assets/<file-path>`
- Without custom domain: `https://steffl-vienna.github.io/public-web-assets/<file-path>`
