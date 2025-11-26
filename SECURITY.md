# Security Policy — QuadHandz-One v1 Sealed Engine

## Scope

This repository is an **immutable provenance archive** for the QuadHandz-One v1 sealed engine of the Quadnition Protocol.

- It is **not** a production deployment.
- It is **not** a hosted service.
- It is **not** an integration SDK.

All content is provided for **verification, research, and review** only.

---

## Supported Versions

| Version        | Status        |
| -------------- | ------------- |
| QuadHandz-One v1 (this repo) | Sealed / archival only |

No hotfixes or security patches will be shipped to this archive.  
Any future engines will live in separate, clearly versioned repositories.

---

## Security Principles

1. **Zero-PII**  
   The design forbids capturing personally identifiable information in logs, chains, or proofs.

2. **Tamper-Evident, Not Surveillance**  
   Micro-Seal and related mechanisms are built for *integrity and provenance*, not user tracking.

3. **Immutable Record**  
   This repo exists as a timestamped, cryptographically verifiable snapshot.  
   History will not be rewritten to hide or “clean up” design decisions.

4. **No Secret Material**  
   - No private keys  
   - No live credentials  
   - No production endpoints  
   If you believe you have found secret material in this repo, treat it as a bug and report it.

---

## Reporting a Security Issue

If you discover:

- A flaw in the cryptographic design
- A way to bypass integrity guarantees
- An issue that could mislead auditors or downstream users
- Accidental inclusion of sensitive data

Please report it **privately and responsibly**.

**Contact (primary):**  
`noncom.maleelectron@protonmail.com`  

Include, where possible:

- A clear description of the issue  
- Steps to reproduce  
- Files, hashes, or commits involved  
- Any potential impact you see

You will receive acknowledgment when the report is read and triaged.

---

## Disclosure & Handling

- Issues affecting **future live engines** may be addressed in separate, non-public repos.  
- This archival repo will not be edited except to:
  - Add clarifying notes
  - Mark known issues
  - Link to fixed versions or superseding designs

If a reported issue materially affects the claims of this engine, a note will be added to the README or SECURITY.md describing:

- The nature of the issue  
- Its impact on the guarantees  
- Where a corrected design can be reviewed (when applicable)

---

## Out of Scope

The following are **not** treated as security vulnerabilities in this repo:

- Theoretical disagreements with the philosophical framing of Quadnition / Doctrine of Humanness  
- Performance benchmarks on non-optimized code samples  
- Attacks that assume access to keys or data that are explicitly not shipped here  
- Misuse of the engine outside the documented model

---

## Commitment

QuadHandz-One is part of a larger effort to make human–machine provenance **provable, inspectable, and fair**.

Security researchers, cryptographers, and engineers are welcome to:

- Review the design  
- Challenge the assumptions  
- Publish independent analyses (with proper citation)

The goal is simple:  
if it claims integrity, it should survive being hit with a hammer.
