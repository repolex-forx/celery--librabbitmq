# Repolex Knowledge Graph of celery/librabbitmq

RDF knowledge graph data for [celery/librabbitmq](https://github.com/celery/librabbitmq), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download celery/librabbitmq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7f318055f4600fc15df17475d6f52c654c6abb4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7f318055f4600fc15df17475d6f52c654c6abb4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f57c434d802dc139818dc130b2a2d1a4bb356bd.nq.gz
│   ├── 0f6fe5b3b007f780ae5d9e96ecb02b3ba1a0b389.nq.gz
│   ├── 152e29d4800237054f55117c48043e86389fabae.nq.gz
│   ├── 16a23a28a0c1e8bf98451bb4dd024ef89a51d7ee.nq.gz
│   ├── 197215be106a51f7248949b326fc5c69386f2f68.nq.gz
│   ├── 1b9542300f622985f7ad7c732d0c5dde94509042.nq.gz
│   ├── 1bea48807d99ad616c1e48b3fc42a4a4b6260e95.nq.gz
│   ├── 2d40d7df967029de43a407ce191a14be800ba958.nq.gz
│   ├── 321d1e496603908ee71400914952ac4503df206e.nq.gz
│   ├── 3acf580b801d14dd625e0f2e44236ecc1de66576.nq.gz
│   ├── 41cbef6791f2cca953d8797815c94981da1699f6.nq.gz
│   ├── 43c1ff56155cc7783366fdcc514f4b93ff12035c.nq.gz
│   ├── 53784baff6195065c48a56033a69f91eeff3348f.nq.gz
│   ├── 56c9f1243d900321f99c66c3aa4eb5925f4df4d8.nq.gz
│   ├── 608e49e8b3c2d00776294071f326715b8fe3db9f.nq.gz
│   ├── 62149e69d89ccd4e80efe28769f1ac1d212786bc.nq.gz
│   ├── 63b6bbc89eef0cffc39d0aea06af1c1c8bdefffa.nq.gz
│   ├── 63bc498841826d0d4e4785499f4b4afbf5e07da9.nq.gz
│   ├── 6a738d77318e13c512d6621048ff3ea459cf49e1.nq.gz
│   ├── 6fa7e254ffcda8aee6754fbbf61496f49f8f4f44.nq.gz
│   ├── 6fddd9c4ab23444243a8f3da57824c688eacf001.nq.gz
│   ├── 6fe1f1fc2abe4478e7d0ab22426dd21787f70b98.nq.gz
│   ├── 7d618a0d9bac38ef053b95c1a7e2d89efc172420.nq.gz
│   ├── 815c1826ffb6166fc5ecd9356ba5305bea6a2c37.nq.gz
│   ├── 89e727155f5bee5e97ec9fcab8712c43608b574a.nq.gz
│   ├── 8dc7d9208df77be870d3098b5557b53b149f6b9c.nq.gz
│   ├── 8f0ae2280a07c919d7d0d6a732662ff5d45c908d.nq.gz
│   ├── 9233ed7e1e47a1b65d757821bc2f203aee65e620.nq.gz
│   ├── 9aaf3658ccc0be20bd551043fb171aa015ac2e7d.nq.gz
│   ├── 9b188c5d8303de175da9fa65bcdc2cbc6a02d3a2.nq.gz
│   ├── a33344dd2af915f7baad08641554e8b8fd599155.nq.gz
│   ├── acb25e9fcb7262ec1626619e025142f39d291cad.nq.gz
│   ├── af52bffce41366d04eac4591ce95b50cafd07618.nq.gz
│   ├── b76cc6512529021cf8c79d7e5f5abe6df6d15c5a.nq.gz
│   ├── b92c9da7aa243b5770b17f640b81bff6865e5cc5.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c43eef3772bf0cc29effd7a2e31aa78bff601b58.nq.gz
│   ├── c6ba417f75128529ab3a680f9beb4a6e8f2a3624.nq.gz
│   ├── c7489c12c2c036b65bea8ebdddc7cfea2fe4e95a.nq.gz
│   ├── d2210e7d6b82d9ca04060c76945562a4627f81ee.nq.gz
│   ├── d511905c1647a1e311e8b20d5930a37a9c2531cd.nq.gz
│   ├── d5adc506b5decfc9e8f4274fee54c6ddff0ebfb2.nq.gz
│   ├── d6981d4f3461501e2677021034a34cc0caa1f32a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cb0c2875655d0d0e38213fa275321cba0b47d0.nq.gz
│   └── ffe49f4798d060d410da2750d659b4574fafc9f9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a7f318055f4600fc15df17475d6f52c654c6abb4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[celery/librabbitmq](https://github.com/celery/librabbitmq)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
