# CHI 2026 T4T Workshop

The workshop website is [hosted here](https://ai-tools-for-thought.github.io/workshop).

This repository contains the website for the CHI 2026 Workshop on Tools for Thought.

It is built using [Jekyll](https://jekyllrb.com/), a static site generator, and hosted on [GitHub Pages](https://pages.github.com/).

Once setup in VS Code, it should run locally using:

```zsh
bundle exec jekyll serve --port 5000
```

And point your browser to http://localhost:5000/workshop

## What to edit

To make changes to the website's content, you can edit the markdown file `index.md` in the root directory.

To change the format and layout of the main page, edit include files in the the layout `/_layouts/`, `/_includes`, and the style `/assets/css/style.css` folders.

To edit/change the information about the organizers, edit the yaml file `/_data/organizers.yml`. Currently organizers have randomly generated avatars. We will replace them with real ones.

To add/change images, upload them to the `/assets/images/` folder.
