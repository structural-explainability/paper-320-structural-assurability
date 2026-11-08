# Structural Explainability: Structural Assurability

<!-- CUSTOM: add arXiv, DOI, and workflow badges when the preprint and workflows exist -->

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

> Investigates the claim-relative capacity of an AI system and its
> evidence-producing environment to make assurance-relevant evidence obtainable.

## Paper Overview

**Structural Assurability**: A Claim-Relative Framework for Evidence-Based AI Assurance

- This repository contains the LaTeX source of the paper.
- The paper is SE-320 in the Structural Explainability series.

**Status:** Working research record, not intended for submission.
May be superseded.

## Main Contribution

Two AI systems can show equivalent functional behavior
while differing in what evidence their architectures make obtainable.
The paper formalizes that difference as structural assurability.

The paper makes three contributions:

- **Claim-relative assurability:**
  Assurability is defined for a system, an assurance claim,
  access and cooperation conditions, and resource constraints.
  It is kept separate from property satisfaction,
  the assurance argument, and confidence in that argument.
- **Comparison without a score:**
  Systems are compared by the claim-relevant distinctions
  their obtainable evidence enables.
  The comparison allows equivalence, strict dominance, and incomparability,
  and defines no scalar assurability score.
- **Candidate structural dimensions:**
  Seven structural dimensions are proposed.
  The companion Lean 4 formalization at v0.4.1 provides
  dimension-specific, profile-grounded separating constructions
  for observability, evidence coverage, traceability,
  and reconstructability.
  These constructions do not independently establish
  evidentiary capability non-equivalence or claim resolution.
  Controllability, independence, and integrity remain
  informal candidates and open research obligations.

Representative AI architectures show that richer instrumentation
can increase assurability for some claims, add nothing for others,
and trade internal visibility against independent evidence.

The results do not claim that the dimensions are complete, independent,
or sufficient for assurance.
Structural assurability describes the capacity for examination,
not a favorable assurance outcome.

## Links

- [Paper 1 SE 100: Neutral Substrates](https://arxiv.org/abs/2601.14271)
- [Companion Lean 4 formalization: Structural Assurability v0.4.1](https://github.com/structural-explainability/se-theory-structural-assurability/tree/v0.4.1)
- [Applied investigation: Structural Assurability pilot](https://github.com/structural-explainability/se-pilot-structural-assurability)

## Building Locally

Requires a LaTeX distribution with `latexmk` (MiKTeX, TeX Live, or MacTeX):

```bash
latexmk -pdf se320_structural_assurability.tex -f

texcount -inc -sum -total se320_structural_assurability.tex
```

## Annotations

[Annotations](./.annotations/annotations.md)

## Citation

See [CITATION.cff](./CITATION.cff).

## License

[CC BY 4.0](./LICENSE)

## References

See [references.bib](./references.bib).

## SE Manifest

[SE_MANIFEST](./SE_MANIFEST.toml)
