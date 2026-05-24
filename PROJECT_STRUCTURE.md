# TopVenues — Project Structure

The repository is organised around two purposes: the runnable tool and the
curated research artifact.

## Runtime Artifact

| Path | Purpose |
|------|---------|
| `src/` | collection, enrichment, persistence, export, CLI |
| `web/` | Streamlit interface |
| `tests/` | pytest coverage for core behavior (250 tests) |
| `data/dataset/papers.db.gz` | committed compressed SQLite snapshot |
| `config.yaml` | venue and pipeline configuration |
| `scripts/` | reproducibility, claim verification, ad-hoc maintenance |
| `Dockerfile`, `docker-compose.yml` | reproducible execution environment |
| `reproduce.sh` | single-command end-to-end verification |

## Evaluation Documents

| Path | Purpose |
|------|---------|
| `README.md` | primary entry point for users |
| `ARTIFACT_README.md` | artifact overview for evaluation |
| `REVIEWER_GUIDE.md` | how to verify each headline claim |

The public package contains the artifact code, committed snapshots,
documentation, and verification scripts needed by reviewers.
