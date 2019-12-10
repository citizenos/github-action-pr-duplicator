# GitHub Action PR Duplicator

GitHub Action to duplicate pull requests (PR). Initially designed to enable Citizen OS localisation team release translations from Crowdin safely.

## The workflow

If a PR, that matches configured head and base configuration, is merged, will make a new branch from the head and creates a new PR from that to destination branch. 
All branches created by his action are prefixd with `pr_duplicator_`.
This workflow should guarantee that the PR content is the same as it was in the originally merged PR.

## Usage

See `/action.yml` for usage info.
More info on GitHub actions - https://help.github.com/en/actions/automating-your-workflow-with-github-actions
