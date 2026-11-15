# Shironamhin Dohon Blogger Theme

Custom Blogger theme for শিরোনামহীন দহন (shironamhindohon.blogspot.com). Warm paper background, ember accent, Noto Serif Bengali wordmark, hero art, Start Here shelf, full-post feed, reading modes (light, sepia, dark), search, Surprise me, related reading, newsletter box, dated archive.

## Files

- `blogger-theme-dohon.xml`: the live theme (592 lines). Applied 2026-11-15 and verified live.
- `theme-backup-2026-11-15.xml`: the previous theme, backed up before the switch.

## How to apply it to a Blogger blog

1. In Blogger, open the blog and go to Theme.
2. Either click Restore and pick `blogger-theme-dohon.xml`, or open Edit HTML, select all, paste the file contents, and Save.
3. Check the live blog: the homepage should show the post feed, and a post page should show the full article.

## Notes

- The theme's `html` tag must NOT carry `b:version`, `class="v2"` or `expr:lang` attributes. An earlier version had them and Blogger silently ignored the post widget, leaving the feed empty. The working theme's `html` tag matches the old theme's exactly.
- Blogger has no GitHub integration and no theme API, so this repo is the master copy only. Applying a new version still needs the paste step in Blogger.
