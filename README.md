# AiAnonymousPT.github.io

### Run locally

- run dev server (live reload and serve) inside the Pelican dir

`pelican -r -l`

- create new content: add Markdown files inside the Pelican/content dir for blog-style posts, add them inside Pelican/content/pages to create standalone pages

- publish: run this command from inside the Pelican dir

`pelican content -o .. -s publishconf.py`