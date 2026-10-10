# Repolex Knowledge Graph of aio-libs/aiohttp-client-middlewares

RDF knowledge graph data for [aio-libs/aiohttp-client-middlewares](https://github.com/aio-libs/aiohttp-client-middlewares), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-client-middlewares
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 33cb914393c2fbab90c29d2b19d6238d933e0616
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 33cb914393c2fbab90c29d2b19d6238d933e0616
│           └── chunk-001.nq.gz
├── blob
│   ├── 03f4083d83a31ca67e221754b6cdefde9d29767d.nq.gz
│   ├── 09df38cfa26e07f3011268c25f689a3e0629b009.nq.gz
│   ├── 111213aaaab29440a40c7313097bc6176fc4caa4.nq.gz
│   ├── 13b45ee2007693e0fc19d042de30d6bcf3eed06d.nq.gz
│   ├── 1db0b0fc202f4712790a920d630f9c446e77f44c.nq.gz
│   ├── 1fcd45965063c683f75ff32569c0e66b4577b7c4.nq.gz
│   ├── 21c5fa1d24389cd418678c9d16e99503968c6bfd.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2781f67b0e40549dd090719fdce6baad5b76a294.nq.gz
│   ├── 2d7783d068b77deafe7ddef6dd9408a484f2e21d.nq.gz
│   ├── 32be882ad6d9a4857d631ad7bb6afe97f1ca138e.nq.gz
│   ├── 360c2ef1c05c022f12433d6bc785ab6918f69973.nq.gz
│   ├── 3b0f55360688c976b2b573df8c8f1afb6fa6bb28.nq.gz
│   ├── 3f4825dbecb1df5290c482a1d733eb1ffc25954f.nq.gz
│   ├── 40d1a72b0b2e47b5df2529d0cc7428e32ce4e2b5.nq.gz
│   ├── 42c4245e548a51790e7e123ea0f65d86303aba47.nq.gz
│   ├── 4f091d64aefb02780fcbceebd4d1285aab0bb6a5.nq.gz
│   ├── 58ab2a8663c4e37b1448de7789d3e7136cbfc108.nq.gz
│   ├── 6ad3a5f4e02dd72750084d0a335fdc5050acdbaf.nq.gz
│   ├── 84439de17c497945d41d851bd19c3137a991364d.nq.gz
│   ├── 85308da643e44ef10bc2df8c14a5187ff20d9abe.nq.gz
│   ├── 85e1e440bb51b476a7fadd6f243fa8d6d94a61dd.nq.gz
│   ├── 8aaac42731dc826975c718bf5c586ab06ef4881a.nq.gz
│   ├── 8b05c23a11e4f17776b043766b462faea8154b4d.nq.gz
│   ├── 9334cefd84fc26c26ea9f1a9fc8d76abb0eba769.nq.gz
│   ├── 959da11b6719b36e8caa76f3dd170a93578e7b7c.nq.gz
│   ├── 9fca6952f429955224c3abbd84ac7a228daafb45.nq.gz
│   ├── aa1b7c6890ce12f157c74a9114afc87e6cdae9ef.nq.gz
│   ├── bd61fb39e10ec52c8de4b9a8f7c6dbbfc4c5c623.nq.gz
│   ├── be2119758925a67200c4390e370aed25d892f9dc.nq.gz
│   ├── c20a90127f6aa568509c9ccf2a14c864a14e0fc8.nq.gz
│   ├── c39943deb784e8a9019b304bf2c1f783e32a3216.nq.gz
│   ├── cb73091a3d79808f5a9979fb038f99bd969aecec.nq.gz
│   ├── d6c0aaf17ca16ab98a2b6d32ca0007c8362531fe.nq.gz
│   ├── dbd793f391a7d3d35d601271b69a51433c2acae0.nq.gz
│   ├── ddaf56d6cf917d158e80aacb3df9a9aa247e37fb.nq.gz
│   ├── ddc772297d158ddfe974ddae41fbfb036e9e9efa.nq.gz
│   ├── e2359caad9479ace1ed63d984d103d8039ce045f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb737e86ce0407c549f22a1a6ac2132b8f1a352e.nq.gz
│   ├── ebdac361c609a4af02005a80156407b8e3f29185.nq.gz
│   ├── eceeb3b33c10b184175838bb6aec7eaee1797df9.nq.gz
│   ├── f33aa8ba9cc02368952c95e60c84de671b809c85.nq.gz
│   └── f412c54fb01080bea5184730558e68a08528a38b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 33cb914393c2fbab90c29d2b19d6238d933e0616.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[aio-libs/aiohttp-client-middlewares](https://github.com/aio-libs/aiohttp-client-middlewares)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
