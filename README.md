# Repolex Knowledge Graph of mkdocstrings/griffe-runtime-objects

RDF knowledge graph data for [mkdocstrings/griffe-runtime-objects](https://github.com/mkdocstrings/griffe-runtime-objects), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-runtime-objects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a417c8520c96e04f36ea2f81aa22282ecdf99b8d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a417c8520c96e04f36ea2f81aa22282ecdf99b8d
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 00ce543b9436fe191db15dadc58706d4d4daea8e.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 05751f7adece8fb0a21efb42c438ab69ef734676.nq.gz
│   ├── 0b399b2ad8b4b26b5241a1412d7cf68597ec71c2.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 147eb2a049b5f4f3a39164dca2cfb1a975b3074e.nq.gz
│   ├── 1a90f2d0a017c53592764b48676efe184ae2f447.nq.gz
│   ├── 20fca4f5bae86ac12be1c0641f9fbf45b634f9c4.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 37c489e02f42fa72841d4789c5ea932f0209a9b4.nq.gz
│   ├── 39aa7df091728a87304b4146f9ced4b591ddb55f.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 62f895146e1f46105391813fb65927bb5ffac0a9.nq.gz
│   ├── 640c03d38d9ae465d8b89310ce816ec1c13b6a61.nq.gz
│   ├── 6ea01c04e879bb5f9dbd1f9bc1bd91ce182092d6.nq.gz
│   ├── 6ec48d5821210cae0f7ce914b88fa04b4b7cde8a.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 767bbe280e6ddf497104f316fca52259955da077.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 915c1c84641ff07e70e9d727d58665ea854c91c4.nq.gz
│   ├── 91ead872ec554d056600fb646496cfd24545f781.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 97121b7bebc4ff88a79ca7e312988178ec55d487.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a870a24f9f15eb47b00bd3c3feef3c82d97687cf.nq.gz
│   ├── aa514fa2d5ef4461b4d1b73b70346a4825ea135a.nq.gz
│   ├── b20168ea923e36194aa31ff8403c296d4c6ad0c0.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c84685c5fd97ad467ff8f98754d8edf4a01ab383.nq.gz
│   ├── c936455ec4b0c32fe610b2eaa7f477ae85b06dc0.nq.gz
│   ├── cd61c2802a5f41d4d09e9848662a44c4d08b06fc.nq.gz
│   ├── d0a0a828c34f3b5d002d6f6b734cdaf8f1ac695e.nq.gz
│   ├── db0b5af17cf5bacd7af76093a4121bf22d315cf7.nq.gz
│   ├── dbef8f04c212058140b622b20123164a5580a6cd.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── ed367b7a734912b62c9b889d7a40c70ad741e64e.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   └── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a417c8520c96e04f36ea2f81aa22282ecdf99b8d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 64 files
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

[mkdocstrings/griffe-runtime-objects](https://github.com/mkdocstrings/griffe-runtime-objects)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
