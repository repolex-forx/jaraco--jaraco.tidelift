# Repolex Knowledge Graph of jaraco/jaraco.tidelift

RDF knowledge graph data for [jaraco/jaraco.tidelift](https://github.com/jaraco/jaraco.tidelift), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.tidelift
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── d2e2e3ae85dae2cba50d25402ee86b9873381f58
│   │   │   └── chunk-001.nq.gz
│   │   └── e137e26ceefb98c23e48a2c08b6dd445e40d5516
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d2e2e3ae85dae2cba50d25402ee86b9873381f58.nq.gz
│   └── repolex
│       ├── d2e2e3ae85dae2cba50d25402ee86b9873381f58
│       │   └── chunk-001.nq.gz
│       └── e137e26ceefb98c23e48a2c08b6dd445e40d5516
│           └── chunk-001.nq.gz
├── blob
│   ├── 02879483d75ae9c6446e89efef6705158f817ae5.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2e1cc0472bc2f86d00889942680bbabd87781096.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 3111b4717f8c29173a15a1c5781d8a46c397fc15.nq.gz
│   ├── 353924be0e59b9ad7e6c22848c2189398481821d.nq.gz
│   ├── 48b2e246f1b40ddbe34618a616a51554d109c0e3.nq.gz
│   ├── 49fe83e45ebd944e7a6760b3bd154d7ce39b1730.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 59af0ebd0001126c7e93bb6c0847272bfc7301ae.nq.gz
│   ├── 5a6782119f8b120f493bb885f4bd016ca868d79b.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 60de24241dfa55a8d02559561eaece97ca10dc06.nq.gz
│   ├── 6bef34935b6f1a81d446f4a90f8a85c721bcc145.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7bc3cbdd764a0923537810b0fd682a28e37d1d82.nq.gz
│   ├── 89ff33961ba3d6f9cda89322a1fdbf1ac2e35513.nq.gz
│   ├── 8bf9f6aadeb1277acac5c0c37367151004a26d88.nq.gz
│   ├── 8e217503ba1a68826af8e1e9db4bd16ce7a21857.nq.gz
│   ├── 9629a26a9348902d22596508b8acbff21308b31f.nq.gz
│   ├── 989001f48ce7c0cd90486748d132fe7127db12d1.nq.gz
│   ├── 994224f0a87dcde4fdd90ee2b814d38245e07dfb.nq.gz
│   ├── 99a2519963170d3a4e9ff260c58afb28879fc332.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9e44a3028856b5ee1675d2358c9202c88fbad116.nq.gz
│   ├── af50201060a0071f6abbef8e994784252fbdd9aa.nq.gz
│   ├── b6f972769e61a5e65f9f45015b363cc362487e55.nq.gz
│   ├── c2043393cdaa905c6e03459a5f24a9cd8711f285.nq.gz
│   ├── dd928a336bd2d7bc499e25f12126081574b3702f.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e7b55fda63c459acbd90a8674035686757c2ffce.nq.gz
│   ├── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
│   └── fbc362cfac4e66c8a545cde271b5451bb7214455.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── d2e2e3ae85dae2cba50d25402ee86b9873381f58.nq.gz
│   └── e137e26ceefb98c23e48a2c08b6dd445e40d5516.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 51 files
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

[jaraco/jaraco.tidelift](https://github.com/jaraco/jaraco.tidelift)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
