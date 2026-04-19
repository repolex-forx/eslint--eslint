# Repolex Knowledge Graph of eslint/eslint

RDF knowledge graph data for [eslint/eslint](https://github.com/eslint/eslint), parsed by [repolex](https://repolex.ai).

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
lexq download eslint/eslint
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── aggregate
    └── ast
        ├── 000128c29235c5a8c35c7ef817dbccc4e42130ca
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 05ab812df9af044143dc25b19ba2dee39f6b80ce
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 07b2ffd3c597780eba6297d7735114beb5d0af4a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 0bcd2255c40b5c115a95181864776b0dd456c2dc
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 0bd54976080936ce080ee2552d504180105593b4
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 0dd38631b8dd60f93807e9cee1df3e752b86ab51
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 0e869b37ed7a4e62d1ee1e3878a344353a6d9b30
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 10c4f85dca978b42d37619f50565a06b9a28c9ac
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 13552c4e8d98c3b38b7dbff9c74dc82ca2aad385
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 14053edc64bd378ab920575f2488fbfcbb5a4ea0
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 150a74b29fae11af344ebbd29f24b5c1110f5848
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 17cfb684194df48d0a5dc566af9c28fe80ea6d42
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 198e5fca2327583bde284acd39e8107accbdcfad
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 1a7cdbfad8d3355132aab3201c7dd3f2e879b19d
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 1c87b415313b4aacda496b3b26efc4e0b93dc13a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 1d1ca45370c1ed3bab3d93e480fe9c22af0bb196
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 208e0b199f5d5f9dd173e58e3f5db19c1f0c38ed
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 2364031090daafe34e80904c32065bfe4692d7a2
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 26baf4056dfb92b3018339c3802db87d28ad8a66
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 271e7ab1adc45a7b2f66cfea55a54e6048d9749a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 299bfae1254f22bd4b3bccd897d6355f63e0d3b6
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 2aaadceec13e6df89a0c56e2b6ce4a145c1ac3aa
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 331cf62024b6c7ad4067c14c593f116576c3c861
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 41a871cf43874e2f27ad08554c7900daf0e94b06
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 428dbdbef367e17edef7ba648fba0d37c860be9c
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 473d1bb7c3dfcf629ac048ca811f4b5eef04a692
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 491a1d16a8dbcbe2f0cc82ce7bef580229d09b86
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 4a88a54aeb456abe94da9f5b3d5472d14b3116f1
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 4c46fb3d861ca12e86f868af19778ce988238da7
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 4e6c4ac042e321da8fc29ce53ed03c86dcaa44a7
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 535235701fb029db6f656bd4e58acdfdeb8c02de
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 536cc343083ffd64172d4da13c7e043b140f1078
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 55122d6f971119607c85b0df8e62942171c939f7
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 55c1685aab0fa75074ac1033abfa6e34cb7baaf6
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 560e812d85d1805a59989f295c3a417609033f11
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 568af4e90b458c4c30dd666a864ba5ad14844a3c
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 5b9414c501c58bfa85f41f96f821973c41e8ae74
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 5c2a1986bfc8a01952ed3db617973769fa060494
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 60a78e7964fbb79c0e55e86845a87e0eb22d4de3
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 6151d9e9ffcbbc0efab9a5f61ea2526a1cf1a00b
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 63881dc11299aba1d0960747c199a4cf48d6b9c8
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 6448f3280f85137b429c1c320da6fb4b48169bd5
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 648fe1adfc02900ee3b96e50043a768a32771fc3
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 6769b5fa11ecfb2c2cf78472d3d90564a1e01d3c
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 69a19c83e44ec7e75d17886529c6dee151d2c960
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 69e94597caa92c9b9f4071f8c9ed4a03772fa6de
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 6f37b0747a14dfa9a9e3bdebc5caed1f39b6b0e2
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 73a841a7dff809e6cf7bb9a37f073d168eabd45f
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 75df535681d15d7d685468d637945a200301f9ee
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 76a235a31718312c2ed202fdde030d329ca62486
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 7a2a0bed1bcded9461e8432aa09d754431d8725b
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 7e78b50dacc3faeacfb8c8dc6ad3359971395d1d
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 823b018b1c4e3e7979c06d7628d769ed9efc926a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8351ec7aaa0f7d4753ff39bb9d6260f2ac9e1f1a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8401101d1e3e3e4e1edc2a9e59cafc9956bf2610
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 85405a3aed9cd17f9de9d6c2c24d7729e3fd73c6
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8781e6f063e56438dc22346504ff637df3f84daf
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8824e44d8cfa683ef68d9da12dbe95a4e03011cc
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8bb527660ffddc122204fb5bf59076687aaa78b8
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8c1ec65fa3d355d072f2c9c66e91aeada8e7ba14
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8e8e9f8476d701e4e981b9b4d9957e5d4855e530
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8f360ad6a7a743d33a83eed8973ee4a50731e55b
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 8fe511b4c0fb74df3290271b29c672c3fbf3be1f
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 901ce0f1e32ea1e9e10ce4d8b37c0d750007a3c5
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 90c1db9a9676a7e2163158b37aef0b61a37a9820
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 9278324aa0023d223874825b0d4b6ac75783096a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 938dbdd6c310784cc8a7329efaeb0e34321b9e1f
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 94ba68d76a6940f68ff82eea7332c6505f93df76
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 96ad0dbc5e0072e40004ee7d938b576ffcb8af8d
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 98b155fb9d8ae5afa8c544453133d0c5a12c12ba
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── 9b17d6fac6983d2fed4cd005acba17be0a183970
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── a57878014bb6af3b29cf3ebab9b55e0eea1855d9
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── a5f7e589eca05a8a30bd2532380c304759cc8225
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── a7d5fe64f402eefdc2bbb73992d3a4ac49f426a5
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── a90d7c4fe5ef83054e29d21d7ffb442103429d03
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── abea3b6f399fde9e28cf6dc5d6c013938f163cdc
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── ac3a60dffc29d8d4d5031621bc062e77f891532a
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── ad1d63951773acc7828bcc1eafbb731567447298
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b185eb97ec60319cc39023e8615959dd598919ae
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b4857e54e54b5dba96d156cd8d8b4d42dc5a3bf4
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b4d2512809a1b28466ad1ce5af9d01c181b9bf9e
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b78d831e244171c939279b03be519b5c13836fce
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b8769f192be940fea3aa5e6477b148efcaae2277
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── b8875f67a7bc99824f19147f4a669be7e98f3eee
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── ba89c73261f7fd1b6cdd50cfaeb8f4ce36101757
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── bbf2b214473606329a5dbcbe022079f4048923a8
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── bfce7eaa0ec5d6591fd247b7ff57b51e45fb88a1
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── c87db63f597287b22d40c4ab1dd9d07e5760d7c9
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── cb9393dd9f160d3dbff27a39b9ce8e24303e3b6f
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── cbf7db0ddfa3b789f7ebc27a66993c08a83e72cd
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d3e4b59f63e53436080b8da827521d6b41a72cea
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d5d1bdf5fdfad75197aadd3e894182135158c3b1
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d6ed1f846f6250d8d776f379380a71e304f4f9e5
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d75d3c68ad8c98828aaa522b87ec267ab2dcb002
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d8c8ede088e1f4a82c9b6b5c2772af268b9161aa
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── d9a39c7685496999b95b11486881d411089ab34e
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── db0b844a66ee25483f9619d04346de1a2a0d79fa
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── db40376637554d10d7b648588338fd796407885e
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        ├── dcf178e3c41e7777ee76ae9582387be85118118b
        │   ├── chunk-001.nq.gz
        │   └── chunk-002.nq.gz
        └── e0cb960e45961a36845b075a2986a1fa6cd6b8aa
            ├── chunk-001.nq.gz
            └── chunk-002.nq.gz

103 directories, 200 files
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

[eslint/eslint](https://github.com/eslint/eslint)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
