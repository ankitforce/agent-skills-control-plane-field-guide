# Skill approval checklist

## Package provenance

- [ ] Canonical source and immutable revision are recorded.
- [ ] Publisher and accountable internal owner are named.
- [ ] Package contents were inventoried: instructions, scripts, references, dependencies.
- [ ] No credentials, private paths, or unexplained binary artifacts are included.

## Runtime authority

- [ ] Required tools and external hosts are explicitly allowlisted.
- [ ] Data classes the skill may read or write are recorded.
- [ ] Credential use is blocked unless separately approved.
- [ ] Irreversible actions require a human checkpoint.

## Evidence and lifecycle

- [ ] Sandbox evaluation and expected-failure results are attached or linked.
- [ ] A human approver, scope, and review expiry are present.
- [ ] A revocation owner, disable path, and installed-copy inventory method are present.
- [ ] The receipt is stored with the package revision it covers.
