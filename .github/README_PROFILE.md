# PatrykBochenek

Personal GitHub profile — renders at https://github.com/PatrykBochenek

This is the special `<username>/<username>` repo: the root `README.md` is shown
at the top of the profile page.

## Structure

- `README.md` — profile content (hook, current work, pinned projects, stack, stats, contact)
- `.github/workflows/waka-readme.yml` — optional daily refresh of WakaTime coding stats

## WakaTime stats (optional)

The README includes a `<!--START_SECTION:waka-->` block filled by the
`waka-readme` workflow. To activate:

1. Create a [WakaTime](https://wakatime.com) account and install the editor plugin.
2. Add your WakaTime API key as a repository secret named `WAKATIME_API_KEY`
   (Settings → Secrets and variables → Actions).
3. Ensure Actions has read/write permissions
   (Settings → Actions → Workflow permissions).

Until the secret is added, the waka section stays empty and the rest of the
profile is unaffected.
