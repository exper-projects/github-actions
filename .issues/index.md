# GitHub Actions is not permitted to create or approve pull requests (createPullRequest)

- Go to orgs settings => Action => General => Allow GitHub Actions to create and approve pull requests
- Make sure the workflow contains

```
    permissions:
        pull-requests: write
```
