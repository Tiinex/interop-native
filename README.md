# interop-native

First-party native Tiinex interoperability — provider-agnostic bootstrap, grounding, external tool and capability contracts, and automation surfaces over Tiinex Core.

## Fresh-start boundary

Own the default environment-agnostic Interop implementation without becoming semantic authority and without embedding OpenAI-, provider-, extension- or host-specific behavior. Major 017 reduced the earlier extraction/refactor execution lineage, so no historical Task is current by default. Future Interop work starts from a new explicit bounded Task with truthful Project ancestry.

Generic bootstrap experience belongs here. Environment-specific additions belong in dedicated Interop repositories such as `interop-openai`. Generic Handoff/package mechanics remain in Core.

## Distribution

- npm: `@tiinex/interop-native`
- branch: `master`
- release policy: `.github/release-policy.json`
- bootstrap command after repository/package qualification: `npm run publish:bootstrap`

Publication remains separate from source readiness and technical qualification.
