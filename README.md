# Feed2Pages: PaperMod Demo

A blogroll that aggregates RSS feeds into your own news feed.


## Add to an existing GitHub Pages Hugo blog

If you already have a [Hugo](https://gohugo.io/)-based blog, you can setup the generator using these steps:

1. Copy `feeds.yaml` to your project
    * Configure your OPML file
    * See instruction (TODO - Link) for how to edit this file
2. Copy the files from `layouts/` to your project.
3. Review `.github/workflows/hugo.yaml`
   * You'll want to merge this with your existing build
   * Ensure you have a `schedule` so the feed is refreshed regularly
   * `ralexander-phi/feed2pages-action` will crawl your RSS feeds


## Non-GitHub Pages sites

Build and run the utility in [feed2pages-action](https://github.com/ralexander-phi/feed2pages-action) before running `hugo`.
