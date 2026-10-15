# LMCache PRT results

Results of the LMCache performance regression tests (PRT), published by the
Buildkite nightly and weekly suites: https://bojiang03.github.io/prt-results/

- `data/runs.jsonl`: one line per run (host, suite, deployment, summary,
  check against its own history). CI appends to it; nothing else changes it.
- `index.html`: static page that renders `data/runs.jsonl`.
