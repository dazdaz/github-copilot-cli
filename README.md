## Step 1: Ensure the Policy is Enabled (Admin Action for Enterprise/Business)

* As an admin, log in to github.com and navigate to Profile > Settings > Copilot (or organization settings if managing at the org level).
* Scroll to the policies section and toggle the Claude Sonnet 4.5 option to Enabled.
* This makes the model available organization-wide in Copilot Chat and CLI.

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
