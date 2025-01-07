# ghrs

## Description

This is a GitHub Action originally built to overcome the 14-day limitation of GitHub's built-in traffic statistics. Run this daily to collect potentially valuable data.

- This GitHub Action runs once per day. Each run yields a snapshot of repository traffic statistics (influenced by the past 14 days). Snapshots are persisted via git.
- Each run performs data analysis on all individual snapshots and generates a report from the aggregate — covering an arbitrarily long time frame.

## Credits

This project was forked from [jgehrcke/github-repo-stats](https://github.com/jgehrcke/github-repo-stats)