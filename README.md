# Acuity Broker Intelligence

An interactive view of a normalised forex and CFD broker registry, covering regulatory
footprint, entity resolution and documented research-tool relationships.

## What this contains

- 1,627 canonical broker and regulated-entity profiles
- 133 documented Trading Central relationships
- A 25-account verified set and a 100-account priority set
- Regulator licence records drawn from official public registers

## Method

Evidence classification is kept separate from commercial priority. First-party and
regulator sources rank above directories and secondary reporting. Unresolved people,
licences and technology relationships stay explicitly labelled as unresolved rather
than being inferred, and leadership records that could only be confirmed historically
are marked as last confirmed rather than current.

## Running locally

The interface is static. Serve this directory with any web server, or open it through
a local HTTP server:

    python -m http.server 8000

The registry data loads from `data/brokers-data.js`.

## About

Published by Acuity Trading. Acuity Trading is authorised and regulated by the
Financial Conduct Authority (FRN: 787261).
