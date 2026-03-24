# OpenCompliance Evidence Schema

This directory is the private source of truth for the public export to `opencompliance-foundation/evidence-schema`.

The first release publishes a draft envelope for typed evidence claims and a small set of claim-type payload schemas aligned to the public synthetic examples.

## Current contents

- `STATUS.md`
- `schemas/evidence-claim.schema.json`
- `schemas/claim-types/*.schema.json`
- `examples/evidence-claim.example.json`

## Current notes

- The schema set now covers the current synthetic claim types used by the minimal, failed, medium, and issued ExampleCo corridors, including repo-policy and CI-policy connector examples in the medium pack.
- The actor ontology and deterministic rejection rules live in the private runtime and docs until the public schema registry grows beyond the seed corridor.
