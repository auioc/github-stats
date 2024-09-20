# github-stats

Forked from: <https://github.com/jstrieb/github-stats>

## Environment Variables

- `USERNAME`
- `ACCESS_TOKEN`
  - [Personal access tokens (classic)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic) with `public_repo`, `read:org`, `read:user`, `repo:status` scopes
- `EXCLUDED_REPOS`
  - Repos in `owner/name` format separated by commas
- `EXCLUDED_LANGS`
  - [Language names](https://github.com/github-linguist/linguist/blob/main/lib/linguist/languages.yml) separated by commas
- `INCLUDED_OWNERS`
  - Owners separated by commas to show statistics for repos you have contributed to
