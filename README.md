# German Capuano

A simple static personal site for posts and notes.

Frameworkless and Markdown-based. LLMs handle the file wrangling.

## Local Preview

Open `index.html` in a browser, or serve the folder with any static file server.

## Writing A Post

1. Put the source Markdown in `sources/` and post images in `assets/`.
2. Ask the LLM to process the Markdown file into a static HTML post.
3. Profit.

Suggested prompt:

```txt
Process the new Markdown file in sources/ into a static HTML post in posts/.
Preserve the source text exactly. Do not edit files in sources/ unless I ask.
Use images from assets/.
Update index.html so Latest points to the new post.
Compare the Markdown source and HTML output paragraph by paragraph before you finish.
```

There is no JavaScript, package manager, or build step. LLM is all you need.
