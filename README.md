# Signature Spec Catalog — Shard 28 (frozen storage)

JAH-SPEC-523051 – JAH-SPEC-539550 (16,500 draft specifications, chunks c03488–c03597).

Frozen storage for the [Signature Spec Catalog](https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html).
New records always land in the main repo; shard repos never change.

- `data/volumes/specs-cNNNNN.jsonl.gz` — 150-spec gzipped chunks
- `data/volumes/manifest.json` — chunk list
- `data/index/specs.idx.json.gz` — `[spec_id, title, chunk, ...]` rows (16,500)
- `sitemap-specs.xml` — per-record deep links (16,500 URLs)
