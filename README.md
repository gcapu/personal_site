# German Capuano

A simple static personal site for posts and notes.

## Local Preview

Open `index.html` in a browser, or serve the folder with any static file server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Writing A Post

1. Put the source Markdown in `sources/`.
2. Put post images in `assets/` with short, descriptive names.
3. Ask the LLM to process the Markdown file into a static HTML post.
4. Check the diff, then commit it yourself.

Suggested prompt:

```txt
Process the new Markdown file in sources/ into a static HTML post in posts/.
Preserve the source text exactly. Do not edit files in sources/ unless I ask.
Use images from assets/. If a new image is needed, put it there with a short, descriptive name.
Update index.html so Latest points to the new post.
Compare the Markdown source and HTML output paragraph by paragraph before you finish.
```

There is no JavaScript, package manager, or build step. LLM is all you need.
