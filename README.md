# Personal Webpage

Built with [Hugo](https://gohugo.io/).

## Setup

```bash
hugo server -D        # dev server with drafts at http://localhost:1313
hugo                  # build to /public for deployment
```

## Structure

```
/
├── hugo.toml              # site config
├── archetypes/default.md  # template for new posts
├── content/
│   └── posts/             # blog posts as .md files
├── layouts/
│   ├── index.html         # homepage
│   └── _default/          # base, list, single post templates
└── static/
    └── css/main.css       # all styles
```

## Writing a new post

```bash
hugo new posts/my-post-title.md
# Edit content/posts/my-post-title.md
# Set draft: false to publish
```
