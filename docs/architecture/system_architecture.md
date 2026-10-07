# System Architecture

## Target Pipeline

Real-world sources
→ ingestion
→ raw-data validation
→ normalization
→ temporal/spatial alignment
→ feature engineering
→ analytical modules
→ evaluation
→ data/API services
→ visualization

## Design Principles

- Preserve raw data and provenance.
- Never silently overwrite source data.
- Separate ingestion from analytics.
- Keep reusable logic in src/ rather than notebooks.
- Make transformations deterministic and testable.
- Document units, coordinate systems, timestamps, and missing-value policies.
- Clearly distinguish measured, derived, inferred, and simulated signals.
