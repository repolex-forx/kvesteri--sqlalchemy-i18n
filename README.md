# Repolex Knowledge Graph of kvesteri/sqlalchemy-i18n

RDF knowledge graph data for [kvesteri/sqlalchemy-i18n](https://github.com/kvesteri/sqlalchemy-i18n), parsed by [repolex](https://repolex.ai).

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
rlex download kvesteri/sqlalchemy-i18n
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9cf515be75be6e319416579b32528e1a096c03cf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9cf515be75be6e319416579b32528e1a096c03cf
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a4192cd0478f746e4ad4c50dca439a52800e53.nq.gz
│   ├── 0e2af6dcd1b07204d34f5a15b6b754610f54ccca.nq.gz
│   ├── 13fa2328938a4089b841ab89a098d9e410353f99.nq.gz
│   ├── 152432c7417d91281d582df04238ee92a6f41155.nq.gz
│   ├── 166b4ebc4097b6bd88835b44fa6773402a460ea3.nq.gz
│   ├── 168c154a77d1107f88414437eaad71a49a57c074.nq.gz
│   ├── 19910132247c7e139218d66cab2f3d3ad1416be9.nq.gz
│   ├── 1b865e98d15778eb1be407b42117da40b2353caf.nq.gz
│   ├── 1b9027d86033d4a0e3b86ffbef9d895bab05252d.nq.gz
│   ├── 1ea9db90db0e89606dcf985fef6c0184a8f8812b.nq.gz
│   ├── 226c01a5afc9e07e88812b1cfcaf287252d7930d.nq.gz
│   ├── 27215bb0f6aaed396eba1eaf5e53ac4196d548cc.nq.gz
│   ├── 31effa4eb8e884eb7c4ee5d90c953d4434cc9793.nq.gz
│   ├── 361d26198e56c68db4d5666f909471d6b8adaf1a.nq.gz
│   ├── 3d51251373173b2a5855685996fe3d4b103a6e5b.nq.gz
│   ├── 3e443e5cf915c4df25281bd367da130a6be0acbd.nq.gz
│   ├── 46b4e316534a33332436904e44d952f79fbe2b03.nq.gz
│   ├── 483b5402f72d0200d2b78d7c2c5e81ac7c1886c4.nq.gz
│   ├── 58a4504f1cfad485e851e724700304e29ccdb65d.nq.gz
│   ├── 597c6e003149f538bec98d06e32bcacb7e61335b.nq.gz
│   ├── 5c00e90909b9dd8f565b4dec2f0dc772ecf3c726.nq.gz
│   ├── 68c3b11d1cf2824e26085cada8f564d4aaa63cc1.nq.gz
│   ├── 7bc42878148ee6d6e1686b42eeafba484af8ae26.nq.gz
│   ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
│   ├── 82f12faa9bada5bb9035eb60419e9a147b57ad46.nq.gz
│   ├── 83a24ff90e684142677b0da795b8be93d1ec2f8d.nq.gz
│   ├── 8f1381cfa129a404594b0f21db33fe3e3d2f8b81.nq.gz
│   ├── 99224f61f0a41835756e91ec190b3960f1d7679e.nq.gz
│   ├── 9971cc06efd0dd2576f641f1aecade1b650c80a9.nq.gz
│   ├── 9a78f55171ec886acc90c244c019ce882e13b435.nq.gz
│   ├── 9ed9e44dd0ca52c2163691be2d14398e374fbd14.nq.gz
│   ├── a0012a5a6dc02588c7bdbcde04609df795a7dc4b.nq.gz
│   ├── a51470890da3ffc5e3dca706b0ab8ee29b20dc6c.nq.gz
│   ├── a5f29eaf88394cd5b49f0dfad22427d8e4654b7c.nq.gz
│   ├── a896a1b20a320e97a20c05afa95b7d003bf59849.nq.gz
│   ├── ac77f112299fa5027ea3605d577e9d61be6f48fc.nq.gz
│   ├── b4c826e8b1de1469cd84b832ebabac1c7ef944af.nq.gz
│   ├── cd079497270795dad8429c61cb463c64f3a425ec.nq.gz
│   ├── cf124e836d9e5fb8d0b85e19e97fefb2446272d8.nq.gz
│   ├── d05f47ad3bd3e9828572b3748d4f592099cd5c00.nq.gz
│   ├── d4f25a499ec1d1e5e34ca876310e6f327f987d6c.nq.gz
│   ├── d604ce842e5f36785bebdf279b73cce044923b6e.nq.gz
│   ├── d67092d9cdb8a9728d8a7e488066b7049618ce80.nq.gz
│   ├── d82ffb70585f070da775de62490ccf83e34ef5a3.nq.gz
│   ├── d90367099a526bffbc02ae04de57834589296897.nq.gz
│   ├── da3fca52a5b757bff1a5d2b95f3626924b1e2abc.nq.gz
│   ├── e0fa1ef4f8c7daf18151c6394a6ccc6fb7cff0eb.nq.gz
│   ├── f3cef9bc303eadb0bb7dbf5cdbe621f100c5f94f.nq.gz
│   ├── f7537517d78a6c28357300099e8a75bc6a60342b.nq.gz
│   ├── fb5dce98bdcc388f42c3071e442234ba15847f36.nq.gz
│   └── fba80332c53cd837166632817b265259dcb3cd72.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9cf515be75be6e319416579b32528e1a096c03cf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[kvesteri/sqlalchemy-i18n](https://github.com/kvesteri/sqlalchemy-i18n)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
