# RAIN PREVIEW public pages

This repository contains the public landing, privacy, and support pages for
RAIN PREVIEW.

## Local preview

From the repository root, run any static file server. For example:

```sh
ruby -run -e httpd . -p 8000
```

Then open `http://127.0.0.1:8000/`.

## Published paths

- `/` — product overview and data attribution
- `/privacy/` — privacy policy
- `/support/` — support and troubleshooting

The site has no build step, third-party JavaScript, cookies, forms, or analytics.
