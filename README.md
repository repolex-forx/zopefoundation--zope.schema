# Repolex Knowledge Graph of zopefoundation/zope.schema

RDF knowledge graph data for [zopefoundation/zope.schema](https://github.com/zopefoundation/zope.schema), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.schema
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bc283a143a2438a92006c17ca3443f18d6650462
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bc283a143a2438a92006c17ca3443f18d6650462
│           └── chunk-001.nq.gz
├── blob
│   ├── 00782555410e63019afec4aef7a45712bec0a6a6.nq.gz
│   ├── 02e53dcd843f6ad124df1cecd4112c4ba52be285.nq.gz
│   ├── 034043e1628b277e8c3805e50acd2ac1e6e85255.nq.gz
│   ├── 06ae7485e53a5c9beba70bcfc016b5c50f61a100.nq.gz
│   ├── 0771b070133591aaafcfb24f0b6b6662472b065f.nq.gz
│   ├── 08221df25aca93381cfca988e195b45162bfd6ca.nq.gz
│   ├── 09838614112c9c7cf9917deaa0e29216cdd25cf9.nq.gz
│   ├── 0ab12fe1e0c8eb6cb0d68fce1b14a2209cdb0def.nq.gz
│   ├── 184e401149f029b960baca563a022d250578d80b.nq.gz
│   ├── 1b67e2dcd97a005ab98280e348493a2acd48fe56.nq.gz
│   ├── 1d6dc428806f712d8aa8d772e50dbe78ba18a323.nq.gz
│   ├── 1f321f52abb7db6f79c285bab56e2852dc575699.nq.gz
│   ├── 23b62fe12a88187ba665dabe116e2de68b6ea055.nq.gz
│   ├── 2566c96b424a4c2e175b39d0c6014c0dc21def5d.nq.gz
│   ├── 30a09f4ae5db63f7e29475ed3e9774cdd83ffe2e.nq.gz
│   ├── 3494e54472ce1c8df4ac3961b5dc8bc107540871.nq.gz
│   ├── 3878ef63f081199174da1c5ed524e6c7b742c479.nq.gz
│   ├── 3a077e992a97dd732032375b61ab405af0e27701.nq.gz
│   ├── 44c3cfcc83cd1174b0620c7420ebfe2ee08523b0.nq.gz
│   ├── 4b06907c7c804a200115f7666e29eabdd6dcf451.nq.gz
│   ├── 537f775573ad1165ec6dd452555c7253478a5dc9.nq.gz
│   ├── 5cccb93811dbcfc69ddda1a1e6205efa8ff0e92e.nq.gz
│   ├── 60f270aa94ed1a46f8e93211863b525274fe09b7.nq.gz
│   ├── 62eca88bcf0a4980893bfe458c1ac0ef102ac804.nq.gz
│   ├── 6366c0b66d8e0d7b33f982887f777e22f4d955e6.nq.gz
│   ├── 66819013c67a9db2e850af4540157feb295441da.nq.gz
│   ├── 77c70d9568da36573cd4043b1c1d34748f99bc47.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 8330f5c5fccb513541d6e14d2c5860063a395717.nq.gz
│   ├── 8c3066b2e68f1883e46f696491daad967ba606bf.nq.gz
│   ├── 91940f19521805915d59eb96acfd78380beeafe2.nq.gz
│   ├── a0ab98f785f19344ebf9669e64943b5b90a6f00a.nq.gz
│   ├── a5b3881200ec9e9aee855f70429b9b35a3538333.nq.gz
│   ├── a8b9c1476bc2bca0b2f0a190e637e349feaf7bb6.nq.gz
│   ├── ae9de397f8c9dbb6d83c76b33bfc695b790fbc30.nq.gz
│   ├── be590828a96918b64721200ef7c3fd80df8a6921.nq.gz
│   ├── c3895a4a9dd33c8aafbbf1339681d8d6c1e0200d.nq.gz
│   ├── c5508b9f083362a81185d598327e7801d837cb18.nq.gz
│   ├── c6bc734c94a1c6975bb32cb6bc76f040aa0368ef.nq.gz
│   ├── caccad7a90e8c45de96f1ad9d6fc8c837d298ccf.nq.gz
│   ├── d6566c1777cb7b1d52c3a6bec9be165e0626dd15.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dbf1ac1aba2d66b1dcca6c6505cb3ff70ce7aa8d.nq.gz
│   ├── defc43243675f1ee48010acfcac67ac01bacc7f5.nq.gz
│   ├── e05d64746baf916274fc38eb1fcf2fa3175950f0.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e3579011e1a5792ed2adb52fe79f1ac001b9c3bf.nq.gz
│   ├── e554f376c3daf92a9251254eb8a3feb7768acf6a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb2661242ba588b71c5b419ed815489a2a9c9847.nq.gz
│   ├── ecf3b156484e97f44a993e991088d6ad5372b224.nq.gz
│   ├── f7496ed18b41f615feb7642f9e016c947079486e.nq.gz
│   ├── f7bdc5668239e7916a138f1e2e61df7012f19359.nq.gz
│   ├── fb8e5102a2b01f1be90b8438a4a6d065ada4ef67.nq.gz
│   └── fbf660edacf3528796def7e050decde63b903886.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bc283a143a2438a92006c17ca3443f18d6650462.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[zopefoundation/zope.schema](https://github.com/zopefoundation/zope.schema)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
