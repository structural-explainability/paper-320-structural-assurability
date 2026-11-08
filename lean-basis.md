# Lean Formalization Basis

> Exact labeled mathematical environments extracted from the authoritative LaTeX section files.

- Source directory: `sections`
- Source files: 10
- Extracted: 2026-11-08T13:27:33-06:00
- Labeled items: 13
- Required labels verified: 13
- Additional labels extracted: 0

Each item contains the exact LaTeX environment from its opening `\begin{...}` through its matching `\end{...}`.

Items remain in section-file and source-line order. No mathematical text inside an extracted environment has been rewritten.

## Summary

| Kind | Count |
| --- | ---: |
| definition | 5 |
| proposition | 8 |

## Paper-Order Index

| # | Paper ID | Kind | Title | Source | Lines |
| ---: | --- | --- | --- | --- | ---: |
| 1 | `se320.def.Assurability` | definition | Assurability | `03-problem-setting.tex` | 106-113 |
| 2 | `se320.def.AssuranceContext` | definition | Assurance Context | `03-problem-setting.tex` | 202-212 |
| 3 | `se320.def.AssuranceRelevantStructuralDimension` | definition | Assurance-Relevant Structural Dimension | `03-problem-setting.tex` | 408-415 |
| 4 | `se320.def.EvidentiaryEquivalence` | definition | Evidentiary Equivalence | `03-problem-setting.tex` | 628-639 |
| 5 | `se320.def.ComparativeAssurability` | definition | Comparative Assurability | `03-problem-setting.tex` | 641-650 |
| 6 | `se320.prop.BehavioralNonImplication` | proposition | Behavioral Non-Implication | `04-formal-model.tex` | 349-352 |
| 7 | `se320.prop.ObservabilityContribution` | proposition | Observability Contribution | `04-formal-model.tex` | 478-481 |
| 8 | `se320.prop.ControllabilityContribution` | proposition | Controllability Contribution | `04-formal-model.tex` | 538-541 |
| 9 | `se320.prop.TraceabilityContribution` | proposition | Traceability Contribution | `04-formal-model.tex` | 584-588 |
| 10 | `se320.prop.ReconstructabilityContribution` | proposition | Reconstructability Contribution | `04-formal-model.tex` | 644-647 |
| 11 | `se320.prop.IndependenceContribution` | proposition | Independence Contribution | `04-formal-model.tex` | 691-695 |
| 12 | `se320.prop.EvidenceIntegrityContribution` | proposition | Evidence Integrity Contribution | `04-formal-model.tex` | 738-742 |
| 13 | `se320.prop.EvidenceCoverageContribution` | proposition | Evidence Coverage Contribution | `04-formal-model.tex` | 788-791 |

## Required Label Checkpoints

- se320.def.Assurability
- se320.def.AssuranceContext
- se320.def.AssuranceRelevantStructuralDimension
- se320.def.EvidentiaryEquivalence
- se320.def.ComparativeAssurability
- se320.prop.BehavioralNonImplication
- se320.prop.ObservabilityContribution
- se320.prop.ControllabilityContribution
- se320.prop.TraceabilityContribution
- se320.prop.ReconstructabilityContribution
- se320.prop.IndependenceContribution
- se320.prop.EvidenceIntegrityContribution
- se320.prop.EvidenceCoverageContribution

## Extracted Basis

## 01. `se320.def.Assurability` — Assurability

- Kind: `definition`
- Source: `03-problem-setting.tex:106-113`

```latex
\begin{definition}[Assurability]
  \label{se320.def.Assurability}
  The \emph{assurability} of a system \(S\) with respect to an assurance
  claim \(C\), under conditions \(K\) and resource constraints \(B\),
  is the capacity of the system and its evidence-producing environment
  to make evidence relevant to supporting or refuting \(C\)
  practically obtainable.
\end{definition}
```

## 02. `se320.def.AssuranceContext` — Assurance Context

- Kind: `definition`
- Source: `03-problem-setting.tex:202-212`

```latex
\begin{definition}[Assurance Context]
  \label{se320.def.AssuranceContext}
  An \emph{assurance context} is a tuple
  \begin{equation}
    Q=(S,C,K,B),
  \end{equation}
  specifying the system under consideration, the assurance claim,
  the applicable knowledge, access, trust, and cooperation conditions,
  and the resource constraints under which assurance evidence
  must be obtained.
\end{definition}
```

## 03. `se320.def.AssuranceRelevantStructuralDimension` — Assurance-Relevant Structural Dimension

- Kind: `definition`
- Source: `03-problem-setting.tex:408-415`

```latex
\begin{definition}[Assurance-Relevant Structural Dimension]
  \label{se320.def.AssuranceRelevantStructuralDimension}
  A candidate structural dimension \(d\) is \emph{assurance-relevant}
  if there exists an assurance context and a pair of systems for which
  a difference in \(d\), while holding other properties material to
  the comparison fixed, produces a material difference in the evidence
  practically obtainable for supporting or refuting the assurance claim.
\end{definition}
```

## 04. `se320.def.EvidentiaryEquivalence` — Evidentiary Equivalence

- Kind: `definition`
- Source: `03-problem-setting.tex:628-639`

```latex
\begin{definition}[Evidentiary Equivalence]
  \label{se320.def.EvidentiaryEquivalence}
  Two systems \(S_1\) and \(S_2\) are \emph{evidentially equivalent}
  relative to a claim \(C\), conditions \(K\), and constraints \(B\)
  if their practically obtainable evidence has no difference
  material to supporting or refuting \(C\). We write
  \[
    \mathcal{E}(S_1,C,K,B)
    \equiv_C
    \mathcal{E}(S_2,C,K,B).
  \]
\end{definition}
```

## 05. `se320.def.ComparativeAssurability` — Comparative Assurability

- Kind: `definition`
- Source: `03-problem-setting.tex:641-650`

```latex
\begin{definition}[Comparative Assurability]
  \label{se320.def.ComparativeAssurability}
  \emph{Comparative assurability} evaluates the relative capacity
  of two systems to make evidence relevant to supporting or
  refuting the same claim practically obtainable under specified,
  comparable conditions and resource constraints.
  The comparison may yield equivalence, dominance, tradeoffs,
  or incomparability; it does not presuppose a scalar score
  or total order.
\end{definition}
```

## 06. `se320.prop.BehavioralNonImplication` — Behavioral Non-Implication

- Kind: `proposition`
- Source: `04-formal-model.tex:349-352`

```latex
\begin{proposition}[Behavioral Non-Implication]
  \label{se320.prop.BehavioralNonImplication}
  Behavioral equivalence under an evaluation set does not imply assurability equivalence.
\end{proposition}
```

## 07. `se320.prop.ObservabilityContribution` — Observability Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:478-481`

```latex
\begin{proposition}[Observability Contribution]
  \label{se320.prop.ObservabilityContribution}
  Observability is an assurance-relevant structural dimension.
\end{proposition}
```

## 08. `se320.prop.ControllabilityContribution` — Controllability Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:538-541`

```latex
\begin{proposition}[Controllability Contribution]
  \label{se320.prop.ControllabilityContribution}
  Controllability is an assurance-relevant structural dimension.
\end{proposition}
```

## 09. `se320.prop.TraceabilityContribution` — Traceability Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:584-588`

```latex
\begin{proposition}[Traceability Contribution]
  \label{se320.prop.TraceabilityContribution}
  Traceability is an assurance-relevant structural dimension
  distinct from mere event observability.
\end{proposition}
```

## 10. `se320.prop.ReconstructabilityContribution` — Reconstructability Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:644-647`

```latex
\begin{proposition}[Reconstructability Contribution]
  \label{se320.prop.ReconstructabilityContribution}
  Reconstructability is an assurance-relevant structural dimension.
\end{proposition}
```

## 11. `se320.prop.IndependenceContribution` — Independence Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:691-695`

```latex
\begin{proposition}[Independence Contribution]
  \label{se320.prop.IndependenceContribution}
  Independent evidence generation or corroboration is an
  assurance-relevant structural dimension.
\end{proposition}
```

## 12. `se320.prop.EvidenceIntegrityContribution` — Evidence Integrity Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:738-742`

```latex
\begin{proposition}[Evidence Integrity Contribution]
  \label{se320.prop.EvidenceIntegrityContribution}
  Evidence integrity is an assurance-relevant structural dimension
  distinct from nominal evidence availability.
\end{proposition}
```

## 13. `se320.prop.EvidenceCoverageContribution` — Evidence Coverage Contribution

- Kind: `proposition`
- Source: `04-formal-model.tex:788-791`

```latex
\begin{proposition}[Evidence Coverage Contribution]
  \label{se320.prop.EvidenceCoverageContribution}
  Evidence coverage is an assurance-relevant structural dimension.
\end{proposition}
```
