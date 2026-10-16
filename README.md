# Repolex Knowledge Graph of sunpy/mpl-animators

RDF knowledge graph data for [sunpy/mpl-animators](https://github.com/sunpy/mpl-animators), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/mpl-animators
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1d4fe4cd4d9a10971b417b93bbd1aedb0c4b5cd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c1d4fe4cd4d9a10971b417b93bbd1aedb0c4b5cd
│           └── chunk-001.nq.gz
├── blob
│   ├── 042a14edc8b181b004853f273371c3576c37ff22.nq.gz
│   ├── 1135ec0d0970ebde541c3db4a8ed7a8789eaa6b7.nq.gz
│   ├── 12c7241c148656b7eb966a326d9f829a210f9cd9.nq.gz
│   ├── 1ce0bf356f87c9b4157ea3c0950f792282fd485a.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 27499d4779d3745bbe462efaa1261fdf04be973d.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 311afc7367f9a32f157f06030204746ef13545d1.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 43c5f5d5fc6ad71143140a19473c6ff4dcdecfd1.nq.gz
│   ├── 46d8180cb1d930795bec84e259699985de9b096e.nq.gz
│   ├── 46f0a0db73b508e257c23bb3dd67b69b67792247.nq.gz
│   ├── 4987a27c001e4d385b93021e8edb887c5684b9fb.nq.gz
│   ├── 4bb8346d95834ce0d7955e7b941879873e870cce.nq.gz
│   ├── 4cf1b3473526c6c00150df0e46f968217863cd3d.nq.gz
│   ├── 4eb95faacf17f374d30580f0cf293c3f3d805ba3.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 5ae6fef6d81540d7b9ea012d8a994b5c07b6f4ed.nq.gz
│   ├── 5df695ec7016c0ca73273b3c13ee9569552fdf1b.nq.gz
│   ├── 61adc668af960d55196077a92c3c60de0feae194.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6890bc29b654e742c8ef0455cc88b9b0fc379c00.nq.gz
│   ├── 6929f9ac87c3927e439f4321431d0198cfa6de25.nq.gz
│   ├── 6c19dd5e47203ca35608de41d7a9ff54e2b95378.nq.gz
│   ├── 6c2fa238c6a7ef08f9a601c34d94db133581ec9f.nq.gz
│   ├── 6e6dceb0e577e22ff8a8e713106615fb62856a48.nq.gz
│   ├── 72e3ce7e69c2f10826869b3f025609e20823ae67.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7c4358db135387054f2fad7c8ee02d2583a9081c.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 81c72fad90f5099552fc15dc466a41a40094a0af.nq.gz
│   ├── 82b4b37390cb704dba6272f0d595465f7375a238.nq.gz
│   ├── 891b7616777a4f9103886dd1a3dac2af07cc214e.nq.gz
│   ├── 89d4dd8a3ba6313e95500048da00594ac66f05c2.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92a9bf02807aa3f15ed0a3ca93f903760afc7637.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 952a4728cbc4001dc7c93b1e210d20ae31a4b88f.nq.gz
│   ├── 9aa4bc45d7a01e480b2a9ca7369333dcdd40ec42.nq.gz
│   ├── a2ae0dba396a2c8d58f35fe6e5a9fabde97d61e8.nq.gz
│   ├── a2aeec062a29e84d59f3bf31605039666320a1d8.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── a5f0b11148e756272d2656cba7c7b1cd99b06518.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── b7607aa3c4329a3ec2219be2e3f1bbcedcad2ea7.nq.gz
│   ├── ba4fe9bef5849b0544c5e40cb7b311beea31f20c.nq.gz
│   ├── bc7146df551f2f0b32144756ad54b1e9a06c2e4c.nq.gz
│   ├── c55d14781c8397913044474b4d9b034b4fb1e3de.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c8661ee449c930969137e0df9360b8d10795823a.nq.gz
│   ├── c8d7e11a4afb03b0f6bba22e190a51366732fe0c.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d99f7ad9ca98c7495921707496a87483911d9715.nq.gz
│   ├── dc328ad2f518f3ce7b0876cacece30279102db70.nq.gz
│   ├── dd2ee53e95417ab5438404aec4a19d3452cc63f9.nq.gz
│   ├── de2a39975ebe87d46f9180b54a91c94bf0f0c73a.nq.gz
│   ├── e2b2aa2dbe1ad0e9c2155b1b821489643ede77b1.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f4d555b4323f0e2800aebc1b478330d897679a3c.nq.gz
│   └── f81e2825e296d771b4fbfdea8570b2e9bfa0a830.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c1d4fe4cd4d9a10971b417b93bbd1aedb0c4b5cd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[sunpy/mpl-animators](https://github.com/sunpy/mpl-animators)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
