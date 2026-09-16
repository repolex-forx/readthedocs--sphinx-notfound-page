# Repolex Knowledge Graph of readthedocs/sphinx-notfound-page

RDF knowledge graph data for [readthedocs/sphinx-notfound-page](https://github.com/readthedocs/sphinx-notfound-page), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download readthedocs/sphinx-notfound-page
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 97515fa3a23ed287889eb172721e9504063d4309
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 97515fa3a23ed287889eb172721e9504063d4309.nq.gz
│   └── repolex
│       └── 97515fa3a23ed287889eb172721e9504063d4309
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a1b81f4f8dcdaae8f80df0029c3e3cc1d63e7a.nq.gz
│   ├── 02644d98b501ff0b9e8db7f0b33a7cd9636bd0be.nq.gz
│   ├── 031e626ac32c4f39667eeee8177f6971ad4efc5f.nq.gz
│   ├── 06b61c803d390876e82f6d9d5545170f250974a6.nq.gz
│   ├── 1b758cf999c7041798825a535c6e1285a56a81aa.nq.gz
│   ├── 1e4126d548c249a3c71e8b35215afc3252585cb5.nq.gz
│   ├── 1ece6b447c618dc34e0df9a9515d7c50bba11fd8.nq.gz
│   ├── 21ffb537d20c548f7286170afccc5b0d283d0c5a.nq.gz
│   ├── 2407d3f0702c9f1242bcf370b7ed4744a9fa8a2c.nq.gz
│   ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
│   ├── 2e2b5eefd7bdf20cbfd8c130670209c9c6334528.nq.gz
│   ├── 32f496453f141bf2b030f55161ae1e97b5feccfb.nq.gz
│   ├── 3485726be21fc640b7ab4515ca5612560911dae4.nq.gz
│   ├── 3f86ab68f4a912e3d142635b14698ae8d254165e.nq.gz
│   ├── 4207f36f3bd0538479c4413e43c4e975a8d87271.nq.gz
│   ├── 4fca895ae1faacea92fd21160022bee314899048.nq.gz
│   ├── 5364314bbd338b1e6595093a9a30b6b9bdb5978c.nq.gz
│   ├── 5c7cafc74b1fc5ffc86a1dfd0172e90d0e9227bf.nq.gz
│   ├── 6088d6ec3da144de7faf74f4ba59491e115d23ab.nq.gz
│   ├── 677c1e5ca025ec4ad62fa90aa14d1052a0dbf251.nq.gz
│   ├── 6849410aae0a8010e76d5f0a44ced13d750b0989.nq.gz
│   ├── 684c8f71197a71804f221b5b40cbcc3dea01d248.nq.gz
│   ├── 6944b92d49412103e830351e01a9d63f7dda87ba.nq.gz
│   ├── 77ef51787d5b11de643e01f3b75eeb4474a31cdd.nq.gz
│   ├── 7af088f0a2bb441eeddd43ade90d10c64fa3cbb4.nq.gz
│   ├── 7d7a17281269e3a7b7affcc9a0fe9c9a756631e5.nq.gz
│   ├── 851df9278bc82f29298eee8a45e8e394f6220413.nq.gz
│   ├── 899c7a6c9c42ad6a329e03592bf615a3f329c9de.nq.gz
│   ├── 8ff63a8d0da72930adedf05fad1ec5aa04fd1176.nq.gz
│   ├── 96223828b70a6c1e7b3a358ca2ea44c4a54b3d87.nq.gz
│   ├── 99956a682b9ce6d1352416fe7f3a117d2bb55d00.nq.gz
│   ├── a27e749e09c76cc72428f894ea9cc3dccce6ac56.nq.gz
│   ├── a5525d2d14d8c37f10c3ea4dd3859d63edd43951.nq.gz
│   ├── a7ad3bffa1f48a0d81c8f8fc31ac091bff2c6114.nq.gz
│   ├── acd3766bb368830ba82a5ef3d7b799554cda9ace.nq.gz
│   ├── af61df786bd34b93f61625e084c6bedb0bd88462.nq.gz
│   ├── b03139ab40644b0428e901ec8fb910127ef3bee8.nq.gz
│   ├── b3d9076a56cd840eca6d5577e04efccfe9420364.nq.gz
│   ├── ba9ef722278b06b0655b98d94cd4a7fea1331c1c.nq.gz
│   ├── c52d8155b06d730d170ab3f2ec66399f8a861f9e.nq.gz
│   ├── c904c41b0100b85013ad3cb8b116d9bdbbd03e29.nq.gz
│   ├── ca1073f4bf496f9f4b8f2919606d83e057276260.nq.gz
│   ├── cd25e3d042b741f7f6d302b2beda2baffb531da4.nq.gz
│   ├── cfc67677667768f8b23e98e9854a5efc36727fc8.nq.gz
│   ├── d0cbb66a1f376d8a4608010d834020796cf539b2.nq.gz
│   ├── d15883fa5ff36c295bb03d517f3c678adf33c1c8.nq.gz
│   ├── d6761a54ce404c513b5ba37a80662ab2b16f42cd.nq.gz
│   ├── df4b6fb3c040f09e54d5af3dc06b9d081df2b7d0.nq.gz
│   ├── e5e38bc8c90a8696220a618a000f092314bc57ff.nq.gz
│   ├── e6ed1be8acbe4c68153cb92337e56ff673347b01.nq.gz
│   ├── e87240f3c875bab0d47c4d3e6a7b9ca76a35fdaa.nq.gz
│   ├── e9e8ce0a474c6c6281703f395f2188ea1f02e6b4.nq.gz
│   ├── ef421c3042d32b3dd2074973e6ce6304b2f7318c.nq.gz
│   ├── efa1f9b90fd25e31979eccfe2de9b446b772de51.nq.gz
│   ├── f4011e462f669bb53b8a315389cb316dce39996d.nq.gz
│   ├── f5010df7ac92860d4525d55ee8097d9e08347e61.nq.gz
│   ├── f84708100107340ee1e10c8f2b71efb35e3a6115.nq.gz
│   ├── f912e34cf3a7dd27d93042070e0514c3f3385aa0.nq.gz
│   └── ff1cabd745a814af1241961e67da3150452f321f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 97515fa3a23ed287889eb172721e9504063d4309.nq.gz
├── filetree
│   └── 97515fa3a23ed287889eb172721e9504063d4309.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 69 files
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

## Source repository

[readthedocs/sphinx-notfound-page](https://github.com/readthedocs/sphinx-notfound-page)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
