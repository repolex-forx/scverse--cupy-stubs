# Repolex Knowledge Graph of scverse/cupy-stubs

RDF knowledge graph data for [scverse/cupy-stubs](https://github.com/scverse/cupy-stubs), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/cupy-stubs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08f2b8ab6bb23bdef1bbfd3bde9b799533a9b5b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08f2b8ab6bb23bdef1bbfd3bde9b799533a9b5b7
│           └── chunk-001.nq.gz
├── blob
│   ├── 085a68217235103e41310567ebf03cd07d534d98.nq.gz
│   ├── 17b7c619c888fcf01b4026cbe888a3f6f52d318b.nq.gz
│   ├── 2609f7e00e7f9299c91bb89f24f29890c5ac6ddb.nq.gz
│   ├── 29e2b1780d829d0b0b35f293d2bdd01e540df1de.nq.gz
│   ├── 2e618643c2ef620ada3c9eee526d8832e971b5eb.nq.gz
│   ├── 2fe65be5bc245ac10b7026ac6b4e0789271d624e.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 33c64e03a65c8c50d839c1085f497b8ccc60b4dd.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 433609251879b18ea1b3df70c44a85b4a11c8bed.nq.gz
│   ├── 4f16a5200d5e615cacf3a9349d562cd16280623b.nq.gz
│   ├── 56db75a1589a492141152e1f41976bb7a8695b07.nq.gz
│   ├── 595d4991e83bda132e12e69cc5d49906c35757e9.nq.gz
│   ├── 59d16fcf2ddebeccf708027c52b2221fa5ad2229.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 6987fe459102c56ddb18367f3c2aa296bcb6b2de.nq.gz
│   ├── 6d707269d85b2c078f6058db7423e98b98d44905.nq.gz
│   ├── 70ac7a97d7b1b9063470b7e82d33f40cc7a768d2.nq.gz
│   ├── 7f0a46adb9e5367751f24fac656658bb1275a844.nq.gz
│   ├── 85d2589e0e92c81809ecd1e46b9eece51dac337d.nq.gz
│   ├── 86504c9e32b7445098a6c97e23866656220e4570.nq.gz
│   ├── 8a572b9683fea91bb37577658b7df9c512bc3f73.nq.gz
│   ├── 9b970a2f886f444973fead2c90c14fa7d1e889e0.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a0fab82fd7ea68d4935583c94966d0b327cad3e2.nq.gz
│   ├── a5b460d6d881ccddf78c8a24df85ef2c021d022e.nq.gz
│   ├── a612ad9813b006ce81d1ee438dd784da99a54007.nq.gz
│   ├── a830806d8d2fbeb2ad78ba80fd126d07772ce927.nq.gz
│   ├── b0205e86857d84963e59f5440ff46d57146e2d5e.nq.gz
│   ├── b648ac92333301658c4f49b315f21130c689c819.nq.gz
│   ├── bb3332d2277f5b392be89811a00f828d6674f8ff.nq.gz
│   ├── bf8add3951bf2bccfdb8ac958e3cd256453639eb.nq.gz
│   ├── c53b5aa7e1abffb8ce4f2780913101026dc526c3.nq.gz
│   ├── c7314fd7cd8150c6de4227ffd453909ebc4596e2.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── d1a7c89a25d631f6d0e5819ef3e916efe49ec159.nq.gz
│   ├── e792cdc3bd8b74e3d762a0c97bf3a3fb6a4cf2d5.nq.gz
│   ├── eb2cf64c17e8ccea051af55882d53c2d63cc69de.nq.gz
│   ├── f15b3d344b8ef5eedba4976cb41df9b8f515b3ca.nq.gz
│   ├── f80f8e2fae5de221b306e9c117ab7a8d468383e0.nq.gz
│   └── f8d3576639790f2c2b6e6fa1d20e2345fc28c982.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 08f2b8ab6bb23bdef1bbfd3bde9b799533a9b5b7.nq.gz
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

[scverse/cupy-stubs](https://github.com/scverse/cupy-stubs)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
