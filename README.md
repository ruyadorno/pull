# @npmcli/pull

This is a script for landing pull requests with the npm CLI team's
annotations.

## Dependencies

Make sure you have [json](https://www.npmjs.com/package/json) installed:
```
npm install -g json
```

## USAGE

```bash
npm i @npmcli/pull

# from the main branch of a repo, land PR-123
pull 123

# if any git rebasing was required, leaving you in the PR-123
# branch, then run this when you're done, to merge into the
# master or latest branch
pull finish master  # or latest, or release-1.2.3, or whatever
```
