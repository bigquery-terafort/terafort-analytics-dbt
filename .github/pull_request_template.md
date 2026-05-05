# Pull Request

## Summary
<!-- One-line description of what this PR does -->


## Changes
<!-- Bullet list of specific changes -->
-
-

## Type of change
- [ ] New staging model (raw → cleaned)
- [ ] New intermediate model (joins/dedup/lookup)
- [ ] New mart (final Looker table)
- [ ] Bug fix in existing model
- [ ] Schema test added
- [ ] Documentation update
- [ ] Refactor (no behavior change)
- [ ] Infrastructure (workflows, packages, configs)

## Testing
<!-- How did you validate this change? -->
- [ ] CI passed on dev environment
- [ ] Spot-checked output rows in BigQuery
- [ ] Compared against legacy scheduled query results
- [ ] Added tests for new models

## Migration impact
<!-- For changes that affect the dbt-vs-legacy migration -->
- [ ] No impact on existing scheduled queries
- [ ] Deprecates legacy scheduled query (specify which):
- [ ] Requires Looker dashboard update

## Checklist
- [ ] Model documented in `_models.yml`
- [ ] Source documented (if new source added)
- [ ] No hardcoded secrets / credentials
- [ ] No `SELECT *` in production models
- [ ] Incremental logic added if model is large
