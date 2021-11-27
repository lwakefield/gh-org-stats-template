# GH Org Stats

Paired with [gh-org-stats](https://github.com/lwakefield/gh-org-stats), use this project to pull PR Throughput, p90 Time To Merge and p50 Time To Merge stats for your GitHub Organization.

To get started:
1. Hit the "Use this template" button above.
2. Setup a `GH_API_KEY` personal token in Repo > Settings > Secrets with `read:org,repo` permissions.
3. Setup a `GH_ORGS` as a comma-separated list of orgs you want to pull stats for in Repo > Settings > Secrets.
4. Wait ~6h for the scheduled run or `git commit --allow-empty && git push` to give it a kickstart.
