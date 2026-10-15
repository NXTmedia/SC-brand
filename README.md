# Stationers' Company brand guide

A single-page brand guide for The Stationers' Company: logos, typefaces, digital and print colours, the Stationers' Hall sub-brand, and tone of voice.

It is plain static HTML and CSS with a little vanilla JavaScript. There is no build step.

## View it locally

Open `index.html` in a browser. To test downloads, serve the folder instead, as some browsers block downloads from `file://` pages:

```
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.

The `.nojekyll` file tells GitHub Pages to serve the files as they are.

## Structure

```
index.html            the guide
assets/logos/         primary logo files: EPS (print), SVG and PNG (screen)
assets/               crest, Hall logo and typeface images
```

## Notes

- Fonts load from Google Fonts. Fraunces stands in for Larken on headings, because Larken is licensed through Adobe Fonts and is not bundled here.
- The wordmark-only logos come from an earlier set of files and are EPS and PNG only.
- The crest and Hall logo files are captured or redrawn, not official masters.

For official artwork or questions, contact communications@stationers.org.
