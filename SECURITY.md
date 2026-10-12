# Selene Public Lab Security

This is a PUBLIC, zero-credential GitHub Actions test-only repository.

Never put private `creations-inbox` / `reading-room-publisher` code, owner session data, signing keys, signed publication payloads, GitHub tokens or private logs in this repository or its public Actions logs.

Permitted: reviewed, self-contained public smoke tests for Python, Git CAS and ephemeral OpenSSH SSHSIG. No private repository checkout or access to production. No privileged event triggers and no third-party marketplace actions. The workflow explicitly sets `permissions: {}` and executes only on manual dispatch.

This is not a production publisher, witness signer or independent anti-rollback authority. Mode B OFF; Batch 6 never rerun; Batch 7 not published.
