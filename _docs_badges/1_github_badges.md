---
title: GitHub badge
---

To show a badge for a given Node.js, Ruby or Java GitHub repository, copy the relevant snippet below and replace "user/(repo)name" with the GitHub username and repo you want to test.

### HTML:

```html
<a href="https://snyk.io/test/github/snyk/goof"><img src="https://snyk.io/test/github/snyk/goof/badge.svg" alt="Known Vulnerabilities" data-canonical-src="https://snyk.io/test/github/snyk/goof" style="max-width:100%;"/></a>
```

### Markdown:

```md
[![Known Vulnerabilities](https://snyk.io/test/github/snyk/goof/badge.svg)](https://snyk.io/test/github/snyk/goof)
```

The badge will reflect the vulnerability state of the latest commit on the `master` branch.
To show the vulnerability state of a specific branch, release or tag, simply add its name after the repo name in the URL.

For example, to show a badge for the `4.x` branch of the `express` repo, use the URL `https://snyk.io/test/github/expressjs/express/4.x/badge.svg`.
