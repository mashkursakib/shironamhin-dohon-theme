# Shironamhin Dohon Blogger Theme

Custom Blogger theme for শিরোনামহীন দহন (shironamhindohon.blogspot.com). Warm paper background, ember accent, Noto Serif Bengali wordmark, watercolour hero art, Start Here shelf, featured post, dropdown post list, reading modes (light, sepia, dark), search, Surprise me, in-page reader, related reading, newsletter box, dated archive.

Posts are loaded from the Blogger JSON feed by JavaScript, not rendered through the Blog widget, so the homepage stays a fast single page and the full text of each post shows in the in-page reader.

## Files

- `blogger-theme-dohon.xml`: the live theme. This is Mashkur's own version of the theme (downloaded from Blogger 2026-11-17), with the homepage feed changed 2026-11-17 from full posts under a "সব লেখা" heading to a dropdown list: one collapsed row per post (title, date, category, reading time), expanding to a short summary and a read button.
- `theme-backup-2026-11-17.xml`: the live theme exactly as downloaded from Blogger 2026-11-17, before the dropdown change. Restore this to undo the dropdown change.
- `theme-backup-2026-11-15.xml`: the previous theme, backed up before the 2026-11-15 switch.

The earlier Leo-built theme (592 lines, full-post feed) was replaced on the live blog by Mashkur himself on 2026-11-15. It is superseded; it remains in this repo's git history only.

## How to apply it to a Blogger blog

1. In Blogger, open the blog and go to Theme.
2. Either click Restore and pick `blogger-theme-dohon.xml`, or open Edit HTML, select all, paste the file contents, and Save.
3. Check the live blog: the homepage should show the dropdown post list under "লেখার তালিকা", and opening a post should show the full article in the reader.

## Notes

- Blogger has no GitHub integration and no theme API, so this repo is the master copy only. Applying a new version still needs the paste or restore step in Blogger.
- The live theme's `html` tag carries `b:version='2'` and works fine, because posts render through the JavaScript feed, not the Blog widget. The old warning about `b:version` breaking the post widget applied only to the superseded widget-based theme.
