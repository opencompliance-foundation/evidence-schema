# OpenCompliance Evidence Schema

This directory is the private source of truth for the first public export to `opencompliance-foundation/evidence-schema`.

The first release publishes a draft envelope for typed evidence claims and a small set of claim-type payload schemas aligned to the public synthetic examples.

## Current contents

- `STATUS.md`
- `schemas/evidence-claim.schema.json`
- `schemas/claim-types/*.schema.json`
- `examples/evidence-claim.example.json`

## Current notes

- The schema set now covers the current synthetic claim types used by the blocked, medium, and issued ExampleCo corridors.
- The actor ontology and deterministic rejection rules live in the private runtime and docs until the public schema registry grows beyond the seed corridor.
