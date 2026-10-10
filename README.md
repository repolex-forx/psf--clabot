# Repolex Knowledge Graph of psf/clabot

RDF knowledge graph data for [psf/clabot](https://github.com/psf/clabot), parsed by [repolex](https://repolex.ai).

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
rlex download psf/clabot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6b1b3a33a3886b40a54f2c75cd134326fe05bfa3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6b1b3a33a3886b40a54f2c75cd134326fe05bfa3
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f503a9c009761f77ef76fb6f7d1681b3570a5b.nq.gz
│   ├── 080fd01345333de0ac6963a45daa2f7fb3442651.nq.gz
│   ├── 08bf2b979dc010912de15d7a265dcfb888fa93bb.nq.gz
│   ├── 0b4974ddfc6cb97e7abf511263d33b8b843e822a.nq.gz
│   ├── 148a1e8631f95810da10e06a783f95e2703d8af2.nq.gz
│   ├── 159e392b60efa1b4c7c564ba040e24053474686a.nq.gz
│   ├── 20184c1e029543b3c05e998aed3053cdb4ad3157.nq.gz
│   ├── 21637a52b8c070c32e85b82d6fbfe894aa240e4e.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26f5c15f860df8ca00825a3b1bc6d7d61515079b.nq.gz
│   ├── 303aa8740c488273dbed62d8fcb581ab26310400.nq.gz
│   ├── 323504bcadbfc722338a7bdc4d3d6d5f921b960e.nq.gz
│   ├── 345ca274d05363f97093bacd31d57ec28ef93788.nq.gz
│   ├── 3774666c7fad71dbd401b728c70d14d42c78a73c.nq.gz
│   ├── 3c76dd7af00ba350897933e3a6190891ff77d05f.nq.gz
│   ├── 3f94ad7e73a99d4bfd26d3a1b491e2c6fb06fda7.nq.gz
│   ├── 44de7d697ba9a7f93d164eface3912886d43e685.nq.gz
│   ├── 47390bb9e506210fde60efed19f4e1c615e4de99.nq.gz
│   ├── 4ab804f5c98335c50e4dd0ff88979eb77a75fc66.nq.gz
│   ├── 5300bc3804a6fa9b42be67d2dc16efbf35b9ded5.nq.gz
│   ├── 5b690f9ec5d98319016376d74fe24b5dc1a384b2.nq.gz
│   ├── 5c5c5886643c66d6678173c2f8dada8039813620.nq.gz
│   ├── 61d908155588a7968dd25c90cff349377305a789.nq.gz
│   ├── 67425118462b0c32d73324b41822d37ac1d930ba.nq.gz
│   ├── 6a41d372034ab883fc789b2b870d58068c6dea34.nq.gz
│   ├── 6ae1ba17e5bb10b6d6ee05556f764750d1749dfd.nq.gz
│   ├── 6cb9a39fd970320a0d2f748677bd66cf61938da4.nq.gz
│   ├── 6f530660df95703a646f30d44a654cd5be8034ea.nq.gz
│   ├── 6f810a0755726d7f0d7738c5c3a5bfc62b3b57f0.nq.gz
│   ├── 6f994b66b6ec98f9c7f12a6ed0c1a7e3c6321cd6.nq.gz
│   ├── 72fcabddba3a33d50b24cba5b7e6eb8baa9692fe.nq.gz
│   ├── 941b32cf8b0b3875d5068f69ea427ff4c38d70ac.nq.gz
│   ├── 9608e9f0e32929244a55dcdf7bbca7ccb38592c1.nq.gz
│   ├── 9ca2587970f68e2243848542f322470349b03709.nq.gz
│   ├── 9ca7da97a9557ec8820610c3700a35a602607de8.nq.gz
│   ├── aad5ddf3cd5d8a28549823da0153a5b22046a525.nq.gz
│   ├── aadefd61b09bf2b8d3798b7abd7f9c40b970881a.nq.gz
│   ├── af18583531b4008013698c6e4c4ef09c3dac52ff.nq.gz
│   ├── b25ca4498fc1e00fd610ef1c07dc975e78ab05c2.nq.gz
│   ├── b3ac7f5c74921c7785868ec95c4d9a1e91ec3a92.nq.gz
│   ├── d1dfec083c7f03e6ae605a416040c41120f0ea82.nq.gz
│   ├── d8c3aab308437aa2cd01ad777eea9503762b843b.nq.gz
│   ├── dbf5551c2ebc4f9d39ef5090d82705875d18b77f.nq.gz
│   ├── e1e6bf0b1c00ac912d545f413720e23bd1b5c16f.nq.gz
│   ├── e60df5b92bed5d047500476c24307ec61421b791.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f83eadfedf27d0cfa5db983ff2e46e0033118853.nq.gz
│   ├── fe7f2fa4697acc660259bbcba5d1afec4a54f06d.nq.gz
│   └── ff3e4994cec5d399a9c58ea14b6ddb12aaa771b1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6b1b3a33a3886b40a54f2c75cd134326fe05bfa3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[psf/clabot](https://github.com/psf/clabot)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
