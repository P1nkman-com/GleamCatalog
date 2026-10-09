# GleamCatalog

A planned public giveaway discovery platform focused on aggregating competitions hosted on Gleam.io.

## Project Overview

Our goal is to help users discover active giveaways, eliminate duplicate listings, and identify competitions they are eligible to enter based on geographical restrictions.

The platform will gather publicly available giveaway links from multiple discovery sources, including search engines, public Reddit submissions, and giveaway directories.

## Planned Reddit Integration

We are requesting read-only access to Reddit's Data API to:

- Discover public posts containing Gleam.io giveaway links.
- Search across relevant communities, including r/Sweepstakes and r/Giveaways.
- Extract external competition URLs and minimal source metadata.
- Deduplicate competitions using unique Gleam campaign identifiers.
- Link back to original Reddit submissions.

The application will not post, comment, vote, send messages, or automatically participate in giveaways.

## Technical Approach

The planned system consists of independent discovery workers, a centralized competition database, metadata extraction from Gleam.io, and a publicly accessible web interface.

Reddit will serve exclusively as a discovery source. Competition metadata will be retrieved directly from Gleam.io.

## Development Status

**Pre-development / Feasibility Assessment**

The Reddit integration has not yet been implemented. We are seeking API authorization before beginning development to ensure compliance with Reddit's policies and technical requirements.

This repository currently serves as the project's public technical overview. Source code and implementation documentation will be added as development progresses.
