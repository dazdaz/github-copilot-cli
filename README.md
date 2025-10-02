# Method 1
```bash
npm install -g @github/copilot
gh auth login
copilot
/model sonnet45
```

## Method 2
```bash
gh extension install github/gh-copilot
gh copilot config
gh auth login --hostname github.com --web
gh copilot suggest "list all files in a directory recursively in bash"
gh copilot explain "git fetch --all --prune"
```

* https://github.com/github/copilot-cli
* https://docs.github.com/en/copilot/how-tos/set-up/install-copilot-cli
* https://github.blog/changelog/2025-09-25-github-copilot-cli-is-now-in-public-preview/ github-copilot-cli blog
