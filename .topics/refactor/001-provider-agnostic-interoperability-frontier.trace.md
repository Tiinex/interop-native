# Continuity Context

- Envelope Schema: tiinex.root.v1
- Parent
  - Parent Schema: [tiinex.topic.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/topic/tiinex.topic.v1.schema.md)
  - Created At: 2026-09-09 15:45:03
  - Trace: [001-turn-2-repository-decomposition-frontier.trace.md](../../business::.topics/initiatives/refactor/repositories/001-turn-2-repository-decomposition-frontier.trace.md)
  - Origin:
    - [relative](../../business::.topics/initiatives/refactor/repositories/001-turn-2-repository-decomposition-frontier.trace.md)
- Current
  - Current Schema: [tiinex.task.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/task/tiinex.task.v1.schema.md)
  - Created At: 2026-09-09 15:48:31
  - Authors: Anchor
  - Why: Give interop its own executable Task lineage while retaining the cross-repository objective in Business.
  - Summary: Establish provider-agnostic bootstrap, external tool/capability contracts and grounding/automation integration outside Core while preserving generic Handoff mechanics in Core.
  - Status: ready/local

---

# Provider-agnostic interoperability frontier

## Objective

Establish provider-agnostic bootstrap, external tool/capability contracts and grounding/automation integration outside Core while preserving generic Handoff mechanics in Core.

## Done Criteria

- The repository boundary is explicit and independently understandable.
- Package/release identity matches `Tiinex/interop` and `@tiinex/interop`.
- Shared contracts are consumed through public neutral surfaces rather than copied sibling implementation.
- Qualification is fast, use-case oriented and fail-closed where lineage, source identity, authority or destructive behavior is involved.

## Scope

Generic external interoperability and bootstrap experience. Environment-specific policy belongs in dedicated Interop implementations such as interop-openai.

## Dependencies

- Controlling Business lineage: `business::.topics/initiatives/refactor/repositories/001-turn-2-repository-decomposition-frontier.trace.md`.
- Shared contract changes remain owned by their current repository/semantic authority and are returned to Refactor Anchor for reconciliation.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: [001-turn-2-repository-decomposition-frontier.trace.md](../../business::.topics/initiatives/refactor/repositories/001-turn-2-repository-decomposition-frontier.trace.md)
  - Value: FSTPBfQmP7ZXOwuLt5OxiGGRIC7uF4WtwqPKJO54Dzw

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: boNQgq0l2SHPjw_ibT-dZ7DIFQMDcmwQd2jY_8JMXx8