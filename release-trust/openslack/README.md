# OpenSlack release trust root

This directory publishes the out-of-band public trust root for stable OpenSlack
releases. The signing private key must never be committed here or stored in an
OpenSlack workspace.

Each release trust record consists of:

- an Ed25519 SPKI PEM public key;
- an `openslack.release_trust_root.v1` metadata document containing the key ID
  and the SHA-256 of the public-key file;
- a commit-pinned raw URL used by operators during release verification.

Consumers must pin the repository commit in the public-key URL. A URL through
`main`, a tag, or a GitHub Release asset is not an independent trust anchor.

The metadata `keyId` is the lowercase SHA-256 hex digest of the SPKI DER bytes
and must match the key ID recorded in the OpenSlack provenance-signature
envelope. Key rotation requires a new reviewed trust record; existing records
are immutable historical verification material.
