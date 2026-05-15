# Repository Guidance

This is a simple static personal site for German Capuano. Keep it lightweight:
plain HTML and CSS, no JavaScript unless explicitly requested, and no build
step unless the project direction changes.

## Content Rules

- Treat files in `sources/` as source material owned by German.
- Do not edit source text in `sources/` unless explicitly asked.
- When converting a source post to HTML, preserve the wording exactly. Do not
  fix typos, punctuation, grammar, contractions, capitalization, or style.
- If a source typo looks accidental, ask before changing it.
- After converting a post, compare the Markdown source and HTML output
  paragraph by paragraph. Report any differences before committing.
- It is acceptable for Markdown syntax to become HTML formatting, such as
  `**bold**` to `<strong>`, backticks to `<code>`, and Markdown links to
  `<a>`, but the visible text must remain unchanged.
- Use short post filenames, such as `on_learning.html`, so public links stay
  concise.
- Prefix post asset filenames with the short post date in `YY-MM` format, such
  as `26-05-knowledge-collapse.svg`.

## Design Preferences

- Keep the site minimal and readable.
- Avoid JavaScript, animations, decorative UI, and framework churn.
- Use simple semantic HTML.
- Use restrained CSS and keep visual treatments compact.
- Do not over-explain features in the UI.

## Git And Workflow

- Keep commits small and focused.
- Do not create commits unless explicitly requested.
- Do not modify unrelated content.
- Before committing post conversions, run a paragraph-by-paragraph text check
  between `sources/` and `posts/`.
