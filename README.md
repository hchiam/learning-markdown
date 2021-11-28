# Learning markdown [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-template/blob/main/LICENSE)

Just one of the things I'm learning. https://github.com/hchiam/learning

## How to disable [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)'s bare URL linting

In VSCode settings menu for markdownlint, "Edit in settings.json":

```json
  "markdownlint.config": {
    "default": true,
    "MD034": false // allow bare URLs in .md files
  }
```

https://superuser.com/a/1295410
