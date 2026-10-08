# Sentysis Automation

GitHub Actions workflows that run Sentysis's backend automation (token launches, airdrop releases, fee sweeps, health checks).

The scripts themselves live in a private repository and are checked out at run time with a read-only deploy key. All credentials are stored as GitHub Actions secrets.

All workflows are manual / API-triggered (`workflow_dispatch`) only.
