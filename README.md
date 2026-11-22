# Repolex Knowledge Graph of hyperium/hyper-util

RDF knowledge graph data for [hyperium/hyper-util](https://github.com/hyperium/hyper-util), parsed by [repolex](https://repolex.ai).

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
rlex download hyperium/hyper-util
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b23a13e2b7ee73e15ba008cd9b19dcd2d3861957
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b23a13e2b7ee73e15ba008cd9b19dcd2d3861957.nq.gz
│   └── repolex
│       └── b23a13e2b7ee73e15ba008cd9b19dcd2d3861957
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d65664f89e0068117f060bd982695dd0b8447a.nq.gz
│   ├── 04defac08f9fbcbabc7f711ab63806e5e4af5fe4.nq.gz
│   ├── 0546663e65c7f03853b0fd36e9cfa17e99b34a39.nq.gz
│   ├── 06b1a9a81ac9e9656c62f349f35f6b6af265e8f2.nq.gz
│   ├── 088ba6ba7d345b76aa2b8dc021dd25e1323189b3.nq.gz
│   ├── 13beb5425892118389e662aff41a724c7b020e6e.nq.gz
│   ├── 156f0572dfde3396b45594426f5ebeef9df4ae0a.nq.gz
│   ├── 1649ae7ea0fe024162c2aefb53463df7b5111b92.nq.gz
│   ├── 223e0ed3e1e85e556fd591efd787afa87d704fb4.nq.gz
│   ├── 268cadf0fa8779203cf79fd8a8fb7651d228ece2.nq.gz
│   ├── 2755fd0519e73fdd0e1a3038e91f220af5ddf3ed.nq.gz
│   ├── 2b15e72fc061283cf35acb61d64ca2bd0d89cf97.nq.gz
│   ├── 34796431243791ae65ee8444785529338102fa6d.nq.gz
│   ├── 37dc7c194c471a6cd315f087051b60224fcd3bb2.nq.gz
│   ├── 40860ee1ea3294d14c5cf1017b47ede1cc2687c1.nq.gz
│   ├── 45f5336eced837d14c9b8ba3aee1aac01507f81a.nq.gz
│   ├── 48806d800d87a61d73df2b114bccbc98da7f217d.nq.gz
│   ├── 56ca32916082d05bf082d3adb318b6d0bb6393fa.nq.gz
│   ├── 59c8e46dfeb3707cfc0b8f9b3b1a2d365c410815.nq.gz
│   ├── 5b3fc94a41bff3818c59ca4e8a738b734e313821.nq.gz
│   ├── 5e334163bded20ff7322fef0d412ef663d077a33.nq.gz
│   ├── 5fdbd05ca76ccaabda42626e031a9c6c4eb33009.nq.gz
│   ├── 6586aabf75946f0a1365808c90f58a86a1e46bcd.nq.gz
│   ├── 65bbe46544fffa0bdfc1f7c46feee3414dff856b.nq.gz
│   ├── 71363ccde2b255beefc5443ad841fe7ac0fd0d12.nq.gz
│   ├── 760d7966b0b7564c99f791fddcac84ce061b3be6.nq.gz
│   ├── 79cb213252ebfe60bc12710c0ec55419cb379e0a.nq.gz
│   ├── 7ec09bbeb3a3a868319c9fb897f021634f268b03.nq.gz
│   ├── 83b56480d60679a56e4d4d4195e7bd01e8752a83.nq.gz
│   ├── 859881865c10a5077da8fa6e5c78753f150bd725.nq.gz
│   ├── 87f0109d1c6b34fbcd2475e231d95e839b913be3.nq.gz
│   ├── 8d94c409df0ebadc1b731b0a5b9705b86d34d7d8.nq.gz
│   ├── 90a976793743b7263e4bf6af81d2da5b5db5143d.nq.gz
│   ├── 90dfcf83cfc64a6ff703b46e2b621fb133112780.nq.gz
│   ├── 95959fe8b41d7623fa4accec028ba4de7c9692c0.nq.gz
│   ├── 95f4bc2f07018fb3c2aba471bd095b9f5e390d01.nq.gz
│   ├── 9c5072d4d0e6c3e0303f964571d0221ee5040a39.nq.gz
│   ├── a4838ac5d842d08a2717cc159beffbdb10848a55.nq.gz
│   ├── a6e43f49a221993b134422e134a7477e90fc17a4.nq.gz
│   ├── b23503a12c0a504c4673c42ed2176578598e9ea6.nq.gz
│   ├── b367fc8a905e85e1608a886d5a1f9f4b66bca4cd.nq.gz
│   ├── b39d494fa997398ba81d5227780072137a764e12.nq.gz
│   ├── bc488e10d7b75452bab64e8ca4e9041bcba1d09e.nq.gz
│   ├── bd5fd50fa5a5cd4e2e849d122b8942217ea05bb1.nq.gz
│   ├── bec8d0811c17c2adaa459b971e5efde981b19963.nq.gz
│   ├── bfb43a4be76f52e036f21c7e1c50c44ad57a4055.nq.gz
│   ├── c69589c6a8af8919caaf32f370932ea68e0695bd.nq.gz
│   ├── ceff86f570421088a56ce0b233e997d78806efeb.nq.gz
│   ├── d1140443ca082cbc9a6d824580a83143423212c2.nq.gz
│   ├── d18944952491c2bf178be33e2439eaf68fd03b7b.nq.gz
│   ├── d1f4a312575c56beffd9d2b5d9cb5133603ad025.nq.gz
│   ├── d23637f36bfa27d606e8f762dfff4dff11565cb8.nq.gz
│   ├── e290ba42c7be48560be9657276775b9844f9e75d.nq.gz
│   ├── ee062b3678d8a5418d8bd42ec5738038762948db.nq.gz
│   ├── f1a8cd7b30a922f17d09272d37279a9398be9e05.nq.gz
│   ├── fae30cb1fa23261817c5c6aba4f17ff1a4a12133.nq.gz
│   ├── fd505416df372f7044a4ed62548c0a681409514e.nq.gz
│   └── fe064b7ca9e5dedbc201f034b1319bfa5f358cfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b23a13e2b7ee73e15ba008cd9b19dcd2d3861957.nq.gz
├── filetree
│   └── b23a13e2b7ee73e15ba008cd9b19dcd2d3861957.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 67 files
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

[hyperium/hyper-util](https://github.com/hyperium/hyper-util)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
