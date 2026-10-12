# Repolex Knowledge Graph of datasette/datasette-apps

RDF knowledge graph data for [datasette/datasette-apps](https://github.com/datasette/datasette-apps), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-apps
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f39519bfa89f84e0d5a0f72661f66b5b20232120
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f39519bfa89f84e0d5a0f72661f66b5b20232120
│           └── chunk-001.nq.gz
├── blob
│   ├── 038f6fa71ce477e68bab3996fd3b6a4b2cdce85c.nq.gz
│   ├── 03a18dad7d0580b534ad3f3246aea15fad05fc59.nq.gz
│   ├── 0a66a2d0e5fa746d892b97b2697573d7bc547ba2.nq.gz
│   ├── 0cea3e68f270e146655c99f3e434407b48e2cf51.nq.gz
│   ├── 1b0c54e6177c4d7172b25a34ba6d3309678c6e6a.nq.gz
│   ├── 232563433aa6d8035a0950a73659d007d894713c.nq.gz
│   ├── 23d9651c585da1149472c71deca2415fb3df79f2.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2b0e0bee1c9dc768192e5cd131231c43bd2fd412.nq.gz
│   ├── 338e14174e7f4b1bdc33ba70e67e28ccec85f406.nq.gz
│   ├── 387b06a70f242a25e8d876433300d36a2730dbba.nq.gz
│   ├── 3c8d9be1de5f291376400f4a82b42080cf0414d6.nq.gz
│   ├── 405554acc737978fca0f3f69b7afcfcb62ce2dd4.nq.gz
│   ├── 462bd913041b5f9bbcab00745d92163c8ff34f24.nq.gz
│   ├── 587dbd643482aa0848476ea947bb9f0fe0320b6d.nq.gz
│   ├── 64698d79e1a5018a07fdc856623d3ecdf15cebe0.nq.gz
│   ├── 6f9ce757a44885504fdd320b2cba95cb4151e3a3.nq.gz
│   ├── 79c64380c5c5c62f5900ae7f15f2579fa3c6a466.nq.gz
│   ├── 7cbfc1523763bc01f57038fdfac40ec50c5a6922.nq.gz
│   ├── 823c1e849f86faa10ace8ba7b18cf59bf8e1daa0.nq.gz
│   ├── 87fa7777ebd1b7ad6a18c7d97f55e7b229e4a6e9.nq.gz
│   ├── 8c5af0104d17158ce6c5ea56bb047e79bcc94ed2.nq.gz
│   ├── 8e29835eb9bc1a5a1a851c80eeac0b116b133db9.nq.gz
│   ├── a3ddd13ab3806ea6c822c21b92253aebc81047e8.nq.gz
│   ├── af8747c22a227a46f406c4bdb82b79b26b830062.nq.gz
│   ├── b560d47223da65544478edc65048db17d1677121.nq.gz
│   ├── bf053a7f5d393f6b73e1fbc31ca4fd029d80b414.nq.gz
│   ├── c7dcaf95df90c485aa0b37b8ef3b95fbab8eb061.nq.gz
│   ├── cdbe527407a04bb14c6bfbe091913d0e313e41ae.nq.gz
│   ├── ce15d5ba0fd536aa047861574373ee0c0af2f19b.nq.gz
│   ├── cf6b6a92857b7d6e260dcfbc98be38531d7efa13.nq.gz
│   ├── d230d4681920a024b5e7d0cad057596c9bf9763f.nq.gz
│   ├── d7054c61a369f262508c63bc9c2640f6c6f9dd05.nq.gz
│   ├── d773c93bc5718983535cc748b66fd8e2f4a88797.nq.gz
│   ├── d9dea23141f2cda4ffef12b171843f8b5c8bf790.nq.gz
│   ├── dff76522693527583dff61becabd1d3a2f7985d5.nq.gz
│   ├── e1edb88e00a1dc2cd256ad115f3572701feaede3.nq.gz
│   ├── e2df988b9283a50c4516c2d242992845f9aa2b4b.nq.gz
│   ├── e718fc7ecc423214b6cbd46463d5448448bb0fd2.nq.gz
│   ├── f20489e1dc1c6b9f5aa2122aec3da37a2cbf72b9.nq.gz
│   ├── f4b9ad0b68edea18ecd166e4293a8e321d11cab4.nq.gz
│   └── fc101548c8d908f067c450f9be5786e4f664628d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f39519bfa89f84e0d5a0f72661f66b5b20232120.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[datasette/datasette-apps](https://github.com/datasette/datasette-apps)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
