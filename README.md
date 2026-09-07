# Repolex Knowledge Graph of rust-lang/flate2-rs

RDF knowledge graph data for [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs), parsed by [repolex](https://repolex.ai).

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
lexq download rust-lang/flate2-rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 19ddb18bf11199858fbc6504d079448fafd1606e
│   │   │   └── chunk-001.nq.gz
│   │   └── 93c81772305a102f1ec846bd12713dd7bf1e3f04
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 93c81772305a102f1ec846bd12713dd7bf1e3f04.nq.gz
│   └── repolex
│       └── 93c81772305a102f1ec846bd12713dd7bf1e3f04
│           └── chunk-001.nq.gz
├── blob
│   ├── 0466bda3ceff61aa059015464d09feaab5e29f78.nq.gz
│   ├── 06d0448dad5f1f3fa7ba39acf0ac07e5947ced74.nq.gz
│   ├── 08033ded7401f48c80dc3af4a8a378e73743c014.nq.gz
│   ├── 0972555a1379d6b7908e6cccbf8d153f78f79770.nq.gz
│   ├── 0c3e4e8e4c2152c63e00c1a4548f3a5d824b919f.nq.gz
│   ├── 0e541861ac820aefc69d9bb756afc95992794ce3.nq.gz
│   ├── 159333b032751969263eeb152e7e94782ab2cd39.nq.gz
│   ├── 16f560196be1cf9fedc8d0d9a9c5b0d6ad1d12c2.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1a293ba08c46941254b5d354bc83c7f11c21403d.nq.gz
│   ├── 1b7f62d0650dad52e58ae3ee286738e1c2c0d027.nq.gz
│   ├── 1bc83bc3c1fce22bb50c72093dd867831d368e42.nq.gz
│   ├── 1d629b3ce35ab608603a74c1118b329efd3301f9.nq.gz
│   ├── 20b3cae6f5eebe5331ddc3fcc064ed3f47e39d36.nq.gz
│   ├── 2214e2dcd8e55b1fa40f1a91e2ca603cf3d7840d.nq.gz
│   ├── 221a75ed1fb7ff3b8bf8fb8a7b1a2aa05f260b08.nq.gz
│   ├── 22be8eec223fe569a2585eee46c86df0ca12e24d.nq.gz
│   ├── 23ce043d476e7345d3da1fa739924804cce8dcbc.nq.gz
│   ├── 248f3d7b30812c1485e1a208ca13a724b7d5d44f.nq.gz
│   ├── 2570f6133a1f0ab43654ba03b2a08c5e4f9c13ff.nq.gz
│   ├── 25c35f40c8ee0854e29a2918b54b20f5a32a9145.nq.gz
│   ├── 2c09fb782837c4ee6ebb917cd6be242f6547f57a.nq.gz
│   ├── 31a696116b7a469b22415dfbcb179e13bd45a7b9.nq.gz
│   ├── 351d0e7731535fdff20f9da81fe861b3bababc89.nq.gz
│   ├── 366c60c99dc759a4faeff5e6ea3929b0bf8cf475.nq.gz
│   ├── 3724c23d798d9816e922ca5dc2fe6267367232aa.nq.gz
│   ├── 39e0ed6602151f235148e6c08413aa7eda5b9038.nq.gz
│   ├── 3a4ef731c59936799a7e14343040c8c6fe210c18.nq.gz
│   ├── 3d4cda7d9490ce668eb596cb5a12b96439793767.nq.gz
│   ├── 3e3548f01dc1e8b2ef35984111400f2346d47803.nq.gz
│   ├── 3e6b9eb3dd0feabdea000a41bdcf6798bb95b24b.nq.gz
│   ├── 402899a9c1c1ae68e6040d2fdf2ae34eb04ab08d.nq.gz
│   ├── 4c89b1d414961cf0a3e5a7ed3952c0d57fddcfed.nq.gz
│   ├── 4dc7c4780d44dab49b16de3b32b7d791a5e0645e.nq.gz
│   ├── 557db03de997c86a4a028e1ebd3a1ceb225be238.nq.gz
│   ├── 572e03bdf321b6cc3a99488183436905cefd086d.nq.gz
│   ├── 5a70bbec0e1f967270e13a8c9ae5ec19140971c9.nq.gz
│   ├── 5a7d1d8ef6be2f685a3328ce9b9e4e0dd4cc9519.nq.gz
│   ├── 5a99b0eb78a7caade6e10baebf5a8a99a58869e1.nq.gz
│   ├── 5d6844c068cf2c93694bb715d701334074bfa243.nq.gz
│   ├── 66a52ee7a1d803dc57859c3e95ac9dcdc87c0164.nq.gz
│   ├── 692b6f53215f2a8c75c813ac13af872e594a0b86.nq.gz
│   ├── 6b2ede95cc2ed30e5caf21d0ca68f72d84a95c24.nq.gz
│   ├── 6b8e7fea1d051b8a88249b5811d50637e0072220.nq.gz
│   ├── 6cee8f8d7dcb33aae34f92a405180b52ce02dd3a.nq.gz
│   ├── 72cddae219e4ea80524045349062ba290fb6f544.nq.gz
│   ├── 74d6c5acfe95fe33199499ea8de070d32abeaa6b.nq.gz
│   ├── 76e02b44d9e6fb9ecc7f19ab7ad0fe361af21310.nq.gz
│   ├── 7e6af06faddd522474c9a8ca714d0488bead730b.nq.gz
│   ├── 7e6f89d6881003f7e224a12503470f450edade2a.nq.gz
│   ├── 7f3bf70fd44d6f45b9d6dea3bbc2ff0114876296.nq.gz
│   ├── 7f5afbea1940d840ac0993363450a288014ea22c.nq.gz
│   ├── 82620c54ba2ccd4a99bbb9e8b4b68968d19565f0.nq.gz
│   ├── 8466681ce8faec1ea4017580fa5feff576b431a7.nq.gz
│   ├── 86fa8d3b89a5bdc7ce39ea5e3f57f82413784fc4.nq.gz
│   ├── 8defdd261d1257ff5a54a5ada3fbb2228d1cf60a.nq.gz
│   ├── 9f5b3021cd2afb648b452c9f922f41602a5cf87c.nq.gz
│   ├── a60a5402a46268e42f64b17f968b64c908fc07e3.nq.gz
│   ├── aa205d42b1ba79a39281dd37dced4619b232b761.nq.gz
│   ├── b4114c90d944ae39eda63d3a10c28a57db543fb4.nq.gz
│   ├── b43f47450cd48566d9e37f76a99445707c6164f8.nq.gz
│   ├── b4eb490f026862bee3c9859d08e35ac06feff32e.nq.gz
│   ├── b52838fcbf02012c8308ecd45565c057233d79fe.nq.gz
│   ├── b5c5b6ca9f85d54ddc18c2203a4171e12ea040f6.nq.gz
│   ├── b9ba7a31924ea6e3023f6efcfa3a3890d0bd9187.nq.gz
│   ├── bab97996086968f67078539bffba6ff3ba3e3b59.nq.gz
│   ├── bc03fdc89d98d67df8ae3cefc57f23e758a06751.nq.gz
│   ├── be4b81e6997d1bbc9fe4cb66d691e46c6bbbaa6d.nq.gz
│   ├── bed6629a2b97fe0eb7a78bd6b7aab9790995fce3.nq.gz
│   ├── bff1848c364ecf592aaa2be17fad473fb7c640d3.nq.gz
│   ├── c032c254185d1d4ff6e8897e47471be37a4657e8.nq.gz
│   ├── c07250851fe9f6b8e8e6ffeb9e6b2ebfe6cf3523.nq.gz
│   ├── c59561dde36fa65cc051acce9f9f560d61fd870c.nq.gz
│   ├── cabc89630fe00d6a611e16fdad958ecfd479cd8d.nq.gz
│   ├── cee01d14aaee154bcba7acdccb419fc285a94d4c.nq.gz
│   ├── d286ba2e965f670fa72f54da3a70f335e7fb5305.nq.gz
│   ├── d2f2a93e4fcc7a8d1c6144622c701f122c794596.nq.gz
│   ├── ddf8a12846328d3c97d6ae1f1f55a67736f8a93e.nq.gz
│   ├── df3bc7b103b145f3be68ba41854df7629067e5d5.nq.gz
│   ├── e01e528418b241c267d154961e0c963630b67f7f.nq.gz
│   ├── e5e17f52e2297e86cd416c3317a48ef31d8b23ce.nq.gz
│   ├── e864580817c28e345b8911b3541c99d701176593.nq.gz
│   ├── ea25922ab211fdd54f6fb4c755c4f92606cf5255.nq.gz
│   ├── ea8cae604c318c08839310b2ca96fe6bbe434b1c.nq.gz
│   ├── ee138483314d2c2d7d1b12073f5f9140ed387dce.nq.gz
│   ├── ee39ac53dbd26ef84694462b8b91df03b18b0c0f.nq.gz
│   ├── f5524bbe85a06cbcb6e727a3d36c255396f7d846.nq.gz
│   ├── f7d413213a40bba3164364f053d227fa79dd15bf.nq.gz
│   ├── f833a50bd211fb5c9c334b91bbe8701b6c36b91a.nq.gz
│   ├── f968689cce01efba445a1d33eb4a21aabf551981.nq.gz
│   ├── f998e1aec08121e0e5137f399ae9b68368a7d52a.nq.gz
│   ├── fb539e588c854addf359800d4a2aa70b3bdf6597.nq.gz
│   ├── fbd05be7245bfe6aaca96dbfbc6c238b7384faaa.nq.gz
│   └── fe3fbbca8f969b2918a00dfa24a080c5a84ce9d4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 93c81772305a102f1ec846bd12713dd7bf1e3f04.nq.gz
├── filetree
│   ├── 19ddb18bf11199858fbc6504d079448fafd1606e.nq.gz
│   └── 93c81772305a102f1ec846bd12713dd7bf1e3f04.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 106 files
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

[rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
