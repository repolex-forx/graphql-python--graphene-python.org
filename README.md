# Repolex Knowledge Graph of graphql-python/graphene-python.org

RDF knowledge graph data for [graphql-python/graphene-python.org](https://github.com/graphql-python/graphene-python.org), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-python.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6e6979976822a2d2b11283b4482a5e8bfa643849
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6e6979976822a2d2b11283b4482a5e8bfa643849
│           └── chunk-001.nq.gz
├── blob
│   ├── 06fb2d6ef346fe241c1a3e60937b75bd8b7ff1a6.nq.gz
│   ├── 09bb430d07c18584fffdae5a189a580cd4f17b87.nq.gz
│   ├── 0b5c29e95236df02821b1997c126c399f35abb00.nq.gz
│   ├── 11e684fb1acac59e12442d2ff43b1fe8948ddee2.nq.gz
│   ├── 1baf41cb2eb083ac5fa8d8ea2865064f0e7ce907.nq.gz
│   ├── 1e9fc886e9795df485dd339eb55114dc6b753034.nq.gz
│   ├── 248335d25151d963f11e623a1d635d597bf10d4c.nq.gz
│   ├── 2535b4413917cc7392e0922ef8f1784284b1fb67.nq.gz
│   ├── 287e00241ae477c3d219cf37029fef2ad8edfef6.nq.gz
│   ├── 2bdb11f64418db47e5e1d426017be6afb8dbad5c.nq.gz
│   ├── 2cdb6a1e518fab894c0a1898c2cfee87fef2de2e.nq.gz
│   ├── 35e458031c9c58e96f290c620f469e539463643c.nq.gz
│   ├── 38841c25a5bfe4a19286428a1d2b535bd1d1f76c.nq.gz
│   ├── 3b1a042ef2d9a82480e8d5a4507144a2a73a181f.nq.gz
│   ├── 3ed6a73a51b46465279ca8993d58c96a00ee92f6.nq.gz
│   ├── 47570421e8228a72b0e19343b49e4de336d1e710.nq.gz
│   ├── 4cf41534b9200d787426ed4cd810a393a9000db2.nq.gz
│   ├── 4d926255482eea22b09da5014c97d0f798395950.nq.gz
│   ├── 4d99a2b5a93575a5bf3ba8a738d18346174200c9.nq.gz
│   ├── 5169a5e4135e9f7e5ff7b2c835dfb34e48202ff7.nq.gz
│   ├── 5a57ad40146d60706d47738285a083fb936ec631.nq.gz
│   ├── 5cded4141067c309214f06312c840a55310dda3d.nq.gz
│   ├── 5e9f8d834d9e27aacaaa16899d2bdf6d5f7ec90e.nq.gz
│   ├── 5f741aeb78d272354184f959e91313ca1bdef1be.nq.gz
│   ├── 6b9e1ab95e32c5c15ad41400e574684925c7ce48.nq.gz
│   ├── 8aa43b0916eb399fc2db5ae265c02f7b530ba225.nq.gz
│   ├── 8ea9f1491663bf15a06a54c899d13aeaceaa4cc5.nq.gz
│   ├── a091a00883676b4dcbb7d2cc8b187d769bfc0dd6.nq.gz
│   ├── a34694c470e688ab12967d3443487324150499cb.nq.gz
│   ├── a43ec380f66b6376b361ca3e02adb6d96800fd28.nq.gz
│   ├── a8a721105319da2b2d9196a335f2c7198d631175.nq.gz
│   ├── a965d3b7d1d709ba95f7507ccebf2a97c99723e2.nq.gz
│   ├── aa7213b77862304d42b761ea63f47c2ea85090c2.nq.gz
│   ├── ab886d8fd8765543cd5fe7382c66eb65e62afbcc.nq.gz
│   ├── ad2e7cb5e771795047dd06181bef70340aea92ff.nq.gz
│   ├── b0674ea00bdba47a6ac452bf78ed79f7d7dad1cc.nq.gz
│   ├── bca49af6918cde9d8a53ebc7d4d83223412e0fd4.nq.gz
│   ├── cc99fae226622c6b6761ba92e90005cf1d93006c.nq.gz
│   ├── d15b65f3cad81fb82909de0a60a9abd437cee0d3.nq.gz
│   ├── df5f8b6af4cd3598abe82158b2485a8880933a8f.nq.gz
│   ├── e399f3a99a7be48cca5fb719fc4f5ce999504a88.nq.gz
│   ├── e903a9fa1d2a3b9506df2f6d235242316b5ddc60.nq.gz
│   ├── ea2603d246395d91049edd455c84b724fe47e225.nq.gz
│   ├── fdd30cc14f7fffcf889d208776041c71f890b08f.nq.gz
│   └── ffa6371e309d0b702d1b76ceb4130c4b0e4454e7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6e6979976822a2d2b11283b4482a5e8bfa643849.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[graphql-python/graphene-python.org](https://github.com/graphql-python/graphene-python.org)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
