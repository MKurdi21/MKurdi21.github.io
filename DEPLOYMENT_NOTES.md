# Deployment Notes

This repository should be named `MKurdi21.github.io` for a clean GitHub Pages user-site URL:

```text
https://MKurdi21.github.io
```

The Jekyll configuration now assumes that user-site repository name and sets:

```yaml
url: "https://MKurdi21.github.io"
baseurl: ""
repository: "MKurdi21/MKurdi21.github.io"
```

If the GitHub repository has not yet been renamed from `academicpages.github.io`, rename it in GitHub repository settings so Pages serves the site from the clean user-site URL. Keeping the old repository name may cause GitHub Pages to behave as a project site and require a non-empty `baseurl`.
