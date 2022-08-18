# mtznbot

The GitHub Bot Account for @amatzen.

## Why mtznbot?

GitHub Actions have some limitation using the Personal Access Token ("PAT") provided in `${{ secrets.GITHUB_TOKEN }}`, this account is meant to deal with those scenarios.

## Security Risks using PAT

Unfortunately, you aren't able to create any PAT scoped to specific repositories, and I'm still trying to figure out how to deal with this issue.
You have any idea? Please tell me!
