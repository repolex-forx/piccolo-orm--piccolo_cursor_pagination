# Repolex Knowledge Graph of piccolo-orm/piccolo_cursor_pagination

RDF knowledge graph data for [piccolo-orm/piccolo_cursor_pagination](https://github.com/piccolo-orm/piccolo_cursor_pagination), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo_cursor_pagination
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 253210d76fb72ce0bf4a82b5eabc07349d869eb0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 253210d76fb72ce0bf4a82b5eabc07349d869eb0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d45d3a357e7dcecfbb9f3019448976b1edd7ef2.nq.gz
│   ├── 1b7340b80bf93851197567074298350540581f73.nq.gz
│   ├── 246b8f32f0d72b04af3ed145e6669d9e2a77dd39.nq.gz
│   ├── 2c310349d145c87f25af1be68f7e9f449220a39d.nq.gz
│   ├── 447b07cad465bc1d49884698f7c04138de8bae81.nq.gz
│   ├── 46edc8fd6ba3144643eba555b925099191107e0b.nq.gz
│   ├── 47d9a97ecbdbd40f145f801073fedd5bfdb5e523.nq.gz
│   ├── 4bfeb95e816541bf7d217132cc452cb3054858eb.nq.gz
│   ├── 4f987308dc72e60abbe5b108948bdf674935e078.nq.gz
│   ├── 5566f37388c3234aa2f5515b6686e0dd4c3c4f6d.nq.gz
│   ├── 5d9c5bc9cbf658260f6012c7aa820a6b8b10c237.nq.gz
│   ├── 614f75ba668008624f879cb1ab01f178294522d1.nq.gz
│   ├── 70e2d55843f00ffe53b3ad9c6697577aaa4802c5.nq.gz
│   ├── 71232926864573359c2948402b7f0180d823c9db.nq.gz
│   ├── 7aff46dbc2f5282dae385aacfbfe334394a5fcc6.nq.gz
│   ├── 810ed5ad05f2ebb1140b49d8912758bda08b9be6.nq.gz
│   ├── 885bf023de1dfa5c32f095ae6955fed6511af570.nq.gz
│   ├── 9a61d5df2ac8eddebbb163be07076179ad21ce28.nq.gz
│   ├── b489446a7cf1f39a59ecf6aee0c8e14d1d91c208.nq.gz
│   ├── b6e47617de110dea7ca47e087ff1347cc2646eda.nq.gz
│   ├── b7f7708c63c932ad33fec5107cb04c8641323e6e.nq.gz
│   ├── c4bfb8a1df56a907b334b19b19a6d4e59fe45e59.nq.gz
│   ├── c8511a0918851ee84015b0adb1d434972fec3102.nq.gz
│   ├── ce908d47dc6521cae04c90d805bcf4da98357a61.nq.gz
│   ├── d47c5b007fa7362cb3ec0d4d08498fb58e00a531.nq.gz
│   ├── dc3e3e0ac604cd9a374fad5cd4909e19cc37f070.nq.gz
│   ├── dd640d030a727ee827d3e2f0a68e59b50fe63a8e.nq.gz
│   ├── e2ff2d803e3e7d9c536057ded2c3db813da9b900.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f5dc1f972fbf14db4f8e291caef89cc8ddfc00ae.nq.gz
│   ├── fd4319a602fd66a9fac1f13d6cb9cc459615835c.nq.gz
│   └── fe2fd244f356abb4b0bbd516271c8733e919ad10.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 253210d76fb72ce0bf4a82b5eabc07349d869eb0.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 39 files
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

[piccolo-orm/piccolo_cursor_pagination](https://github.com/piccolo-orm/piccolo_cursor_pagination)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
