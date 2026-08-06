# noevisai-web

## Review features locally

This is a static website, so no dependency installation or build step is required. Serve the files over HTTP instead of opening them directly with a `file://` URL; this more closely matches production browser behavior.

From the repository directory, start a local server:

```sh
python3 -m http.server 8000
```

Then open the following pages in a browser:

- Homepage: <http://localhost:8000/>
- CogniScan: <http://localhost:8000/mripredictor.html>
- SWAI: <http://localhost:8000/swai.html>

When reviewing a feature:

1. Follow its links from the homepage as well as opening its page directly.
2. Check the page at desktop and mobile viewport widths.
3. Confirm navigation links, email calls to action, images, video, and page anchors work as expected.
4. Hard-refresh the browser if an older version appears from cache.

Stop the local server with `Ctrl+C` in the terminal where it is running.
