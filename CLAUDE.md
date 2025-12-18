# Global Flood Hydrotectonic Model

## Project Overview

This repository contains the Hydrotectonic Collapse Model - a quantitative framework for catastrophic plate tectonics during the Genesis Flood. The model addresses pressure maintenance, energy budgets, heat removal, and scale-up from observed analogs.

## Current Status

**Model Version:** v2.5 (Gap Analysis Edition)
**Synthesized Overview:** `theory/global-hydrotectonics-theory-main.md`
**Full Technical Document:** `theory/papers/20251217-hydrotectonic-model-complete.md`

## Key Files

- `theory/global-hydrotectonics-theory-main.md` - Synthesized theory overview (start here)
- `theory/papers/` - Full papers with all appendices
- `theory/calculations/` - Detailed technical calculations
- `theory/literature/` - Literature reviews and citations
- `theory/defense/` - Defense materials and review responses
- `theory/figures/` - Generated figures
- `notebooks/` - Jupyter notebooks with reproducible calculations
- `reference_validation_protocol/` - Citation verification tools and workflow
- `issues/` - Open research questions and tracking
- `planning/` - 8-phase credibility roadmap

## Behavioral Instructions

Be very helpful but not over enthusiastic - moderation in all things - a healthy dose of skepticism is more valuable than an enthusiastic error.

### Epistemic Standards

- Evaluate factual claims for truth/falsity using logical analysis
- State confidence levels explicitly
- Distinguish between: computed facts, logical derivations, pattern-based guesses
- "I don't know" is often the most accurate response

### Scientific Rigor

- All numerical claims must trace to notebook calculations
- Run sanity checks on new quantitative work
- Acknowledge uncertainties explicitly
- Distinguish STIPULATED, DERIVED, and ASSUMED parameters

### Citation Validation

- All new citations must be verified before committing
- Use the Reference Validation Protocol: `reference_validation_protocol/README.md`
- Run `verify_citation.py` for DOI-based verification
- Update `theory/literature/CITATION_VALIDATION_REPORT.md` with verification status
- Pre-DOI papers require 2+ independent sources (VERIFIED_VIA_SECONDARY)

### Style

- Avoid em dashes wherever possible - use en dashes occasionally
- No emojis unless explicitly requested
- All scripture references from the ESV
- Professional tone appropriate for scientific discourse

## Author

James (JD) Longmire
ORCID: 0009-0009-1383-7698
Contact: jdlongmire@outlook.com

## Git Workflow

- Commit frequently to ensure no data loss
- Always run `git status` before commits to capture any added files
- Commit to both local and remote repos
