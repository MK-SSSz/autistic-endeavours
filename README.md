# Autistic Endeavours

A small static website of questions I've looked into, with the figures and sources, so I can share a link instead of a screenshot.

Plain HTML and one CSS file. No build step. Published with GitHub Pages from the `main` branch root.

## Adding a topic

1. Copy `covid-deaths.html` to a new file and edit the content.
2. Add a link to it, with the date, in the topic list in `index.html`.
3. Update the "Last updated" footer.

## Renaming the site

The site title ("Autistic Endeavours") is marked with a `<!-- SITE TITLE -->` comment wherever it appears: the `<title>` and `<h1>` on `index.html`, and the back link at the top of each topic page. To rename everywhere at once:

```
sed -i 's/Autistic Endeavours/New Name/g' *.html README.md
```

## Main website link

Each page footer links to the main site (https://www.smartersurveyingsystemz.com). Copy the same footer into any new topic page.
