# Repolex Knowledge Graph of goccy/go-json

RDF knowledge graph data for [goccy/go-json](https://github.com/goccy/go-json), parsed by [repolex](https://repolex.ai).

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
lexq download goccy/go-json
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4877d51d546f8c67b1cd9b49ab002ba3af37785
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e4877d51d546f8c67b1cd9b49ab002ba3af37785.nq.gz
│   └── repolex
│       └── e4877d51d546f8c67b1cd9b49ab002ba3af37785
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c3a2b705af2ead8bd31269fe13540e3f16f5df.nq.gz
│   ├── 0119ecc6ed47ef0be7e71f9b51824965809a75f1.nq.gz
│   ├── 023b817c3681ba85481cb4ea1a4bcf185c324058.nq.gz
│   ├── 025ca85b5e22be704b13108cf89556f679a3282b.nq.gz
│   ├── 07a9caea6513b5b93539bf2160c0a98be000b9f2.nq.gz
│   ├── 07ec760d8501ec25ee83a3a1afb3dcb2b158a12e.nq.gz
│   ├── 090cd6328231f139d5f2f797a9c43c7ecbbbc801.nq.gz
│   ├── 0b9a5fe98bf9a5fa5c61e8c93e0e33761d2e34a4.nq.gz
│   ├── 0c4e2e6eacfcf7dec71d3fc73246ba6b8e4a971a.nq.gz
│   ├── 10e5435e6ce269fa7ea8f52ba18c7226712651f4.nq.gz
│   ├── 12c58e46c01a9c123125279c051facc34034297e.nq.gz
│   ├── 12ec56c5bbd296472341c7e9f0f03189e6b1ec37.nq.gz
│   ├── 1572a92bfbdfe99c28195104740d1f4b1e560f66.nq.gz
│   ├── 16140786d1dd764f48eec7749c4201bf0ea37f66.nq.gz
│   ├── 195301b918fb350088b8dd2da3e7bee55c6eb9d8.nq.gz
│   ├── 1a7f081994c0590f07f694117178446727029068.nq.gz
│   ├── 1e1850cc153d0505c2cb3478d5b7050633accbb4.nq.gz
│   ├── 1e8938c8cd545de8b8e3c8ec84a1c9341c5dfcf9.nq.gz
│   ├── 237a29b4a1a0150cea4590190067d7052278793d.nq.gz
│   ├── 2395abec975b897f0ccf056bba618f2b4c541eb5.nq.gz
│   ├── 28ab9db8e2783c06aad4845d2f457bcbb6aac973.nq.gz
│   ├── 30a23e4b51ec049d8035c09b1d3187d33f1855a7.nq.gz
│   ├── 313da153b36eecbd2992bcf4ee8e3f74827abf6c.nq.gz
│   ├── 3224b6570f63879b957e786450fa20aa49f4a624.nq.gz
│   ├── 32602c908ae4ab5eea960b4612a934db017d6a36.nq.gz
│   ├── 326f527315e203c45685cbeb9c9b2f5dc50a364c.nq.gz
│   ├── 33f29aee4481541074a0aa5d451540f774a73852.nq.gz
│   ├── 34c9114434d855c7141c95a6afad28bac9f8a626.nq.gz
│   ├── 35c959d481857375ba4a9cd57c3d45393966a952.nq.gz
│   ├── 378031a080dc88d177505b3f569bdb83bdd4b67a.nq.gz
│   ├── 378283829cfae2edd2835e6b675e44405acc7a76.nq.gz
│   ├── 37cfe35a1fd380e70ae67cf20bd346a2475ce753.nq.gz
│   ├── 3833d0c86db5f57190fa35465e92abc747d730df.nq.gz
│   ├── 38abce78f38ec45e1f7cb8180bad69ff83ae86fd.nq.gz
│   ├── 3b4e22e5d421218bee275f6196c4374f03a960fb.nq.gz
│   ├── 4131731b8e4d922ed87ba6cc89ba5ced0f638f52.nq.gz
│   ├── 41904e491cd1bbdde87ce824a168aef93f4a3241.nq.gz
│   ├── 42d862148fa09f32a6745b4c360ed119357bf9f9.nq.gz
│   ├── 44fecdfda4defe91f02e7077447771e19f5c7f28.nq.gz
│   ├── 4514bb0bab07866b81679c0cd6ea9ae28d02d8b3.nq.gz
│   ├── 45c69ab8c7090713ea3bcb419c018ba16bf3c364.nq.gz
│   ├── 47b482f7fb6649d75e09e0f6bc16d871b93de44a.nq.gz
│   ├── 4891eb8f139da2cf89577e7b2649ddd06e55cf00.nq.gz
│   ├── 4abb84165e9cb10bbf924eeb478e6d5f5a656749.nq.gz
│   ├── 4b11cf20dfbb8caaccd1c6535b022d7953517afc.nq.gz
│   ├── 4b23ed43fe20f8e2ac8d5d2fc947bedba26f0d89.nq.gz
│   ├── 4b693cb0bbedc91bde3de7a1295d55621935a5d3.nq.gz
│   ├── 4c5e3ef5d2be7aad86a05754c029324a32de754b.nq.gz
│   ├── 4c9721b09892842734de91d87081b807183f74cc.nq.gz
│   ├── 4cc12ca81f14251db8d075ecf7e60451c8a8ad90.nq.gz
│   ├── 4cd6dbd573ffccf8a43aac60da7583f71e53cecb.nq.gz
│   ├── 502f772eba0b403f07f9177283a924fdb188789a.nq.gz
│   ├── 526f9b21992d4584034c5c318b68914cc7ac50ec.nq.gz
│   ├── 53157ce93e2b4fe9cfdff99ced607621d950ab48.nq.gz
│   ├── 55f05811e0ab44bd5fd3e63b026c7be68038e889.nq.gz
│   ├── 5b2dcee50ecf493f45b2374d44ab9f14d79722e4.nq.gz
│   ├── 5b98a08d8d119486dd88dccc567baeb4b3b4dc4e.nq.gz
│   ├── 5c1241b47d00bfce655a54da99e089caf8e4c793.nq.gz
│   ├── 5f2a4c23f0234be06817b29296ee9768af9472f1.nq.gz
│   ├── 612fa8e6515b71fdaa2c77bc5465fb8b0ee6acbf.nq.gz
│   ├── 6449c8bff65e3b5d07b44d1db239de6fbf3c9b1d.nq.gz
│   ├── 645d20f9fbe97795fe86756ab37e8c3ab66154ac.nq.gz
│   ├── 65252b4a5cd76a05d14ae76a476742a30614cd21.nq.gz
│   ├── 6cb745e3939b36a4b126b38f90a7681a6ff771cc.nq.gz
│   ├── 6fd858ef1029c5c205deda97ed64078ce97734dc.nq.gz
│   ├── 70a03063df61c2d7595870f297c94251a0512252.nq.gz
│   ├── 74c6ac3bcad7581e2b7e7e8bf7a6f37026fb70c3.nq.gz
│   ├── 7b32df8659e8cad3e47d5cd4e184361dd2451176.nq.gz
│   ├── 7bacc54f9cd077eea14eae2138aea5d34308588f.nq.gz
│   ├── 82b6dd47f864c3e15c106d189dfcf4b46682f959.nq.gz
│   ├── 836c5c8a85ac13d7b206b1d2e68551e9fe4f3e69.nq.gz
│   ├── 86291d7bb3779dfc40b395847cf9d78621076869.nq.gz
│   ├── 869b78356bec8283b7e5798efabd0e7ffd4f1eae.nq.gz
│   ├── 86dad2b0db0017b3f12bed52ea17552df56c6408.nq.gz
│   ├── 8ad50936c0c44b78ab8d2a59f11f9aef43c5299c.nq.gz
│   ├── 8b5febeaa63b93f9f7c394f9cf3a6695fb1c675b.nq.gz
│   ├── 8d852b98af5ae778ea8d752fcfdd572781fece31.nq.gz
│   ├── 8dd9f977b4ea44572ad5026e03e705205da98575.nq.gz
│   ├── 8dea1749017780fef0dd62b1cf230fd03773d073.nq.gz
│   ├── 8f32cedb5d1e9001c565aad219c51a2df005e713.nq.gz
│   ├── 9207d0ff25e358a1031975e22018873afc7c86ff.nq.gz
│   ├── 925f61ed8e690bbb099b259b65cd1985e904d926.nq.gz
│   ├── 939bf4327411c39b41f56686598ab8aeda5d097c.nq.gz
│   ├── 95d92b89ef7762b0b35dc259cbcba1f91f5f6404.nq.gz
│   ├── 977accaa9f4fe7913f69865f8376bbc9c1d7d1ca.nq.gz
│   ├── 99395388c1e3039795e40025807f5a75ae930254.nq.gz
│   ├── 9b2eb8b35a4db6143fee191b6867ac5f2e8fea5a.nq.gz
│   ├── 9b69dcc360dcc56c6d51d4b659563e424afea297.nq.gz
│   ├── 9c5f8ff4378613efc4f238bedee3c47fdf08e17f.nq.gz
│   ├── 9cee6d449f46b8937d92ae9a028a1629b0988666.nq.gz
│   ├── 9e245bfe57d3dda3095306da6056b1ac1d420f51.nq.gz
│   ├── a15ff69e3cd80f152a4f426a28cf72763cd770f9.nq.gz
│   ├── a383f72596946a30fda88178e12d9cc79629756f.nq.gz
│   ├── a63e83e5505ac2a57fe79092aa237938ab5178cf.nq.gz
│   ├── ab4b632ce51c15fad3b99b5f4ae18ba68e9bbddf.nq.gz
│   ├── ae2299466af5bf931d3e4c2c9b91ed180f9fc189.nq.gz
│   ├── b107636890af4d730e4f519a2bc07ee34d6f7ecb.nq.gz
│   ├── b436f5b21ffede8914d7bba04430506a76010ff8.nq.gz
│   ├── b609e981c0def73136082e0678cae68fd4d65838.nq.gz
│   ├── b6876cf0d049c47196983413863d1723ba473e28.nq.gz
│   ├── b6f45a49b0e78489881fd25990f9734a9342f7bb.nq.gz
│   ├── ba6cf5bc496f2f91489bf4bb074603fc3b5173f9.nq.gz
│   ├── baab0c5978d330531100ef99d8c0fff168292016.nq.gz
│   ├── bc074ce8f06b3e051d4849d894339582d4617505.nq.gz
│   ├── bd9623c731e11d72abc2d004326eb69f68ade097.nq.gz
│   ├── beaf3ab866be1fef7e9c46c65b5f9b1303c03e28.nq.gz
│   ├── c030577dcf9d57ba2f03eccb10d9d095547867e7.nq.gz
│   ├── c21819dcaaf3497f118487f903bed7ad20cceaad.nq.gz
│   ├── c2377d432055f69f75ca762ebcedfa6077631265.nq.gz
│   ├── c5173825a95aac5b749da8d77bf445dd751a4adb.nq.gz
│   ├── c53e6ad9fc57b81346e6b39cb87927f72a59a3f3.nq.gz
│   ├── c94644ec911fc2c3feafb7bc43b3ff0255eb16ee.nq.gz
│   ├── ca5be89f265953cf9531bb6564c67463e1b9f98e.nq.gz
│   ├── cb2ffdafd037fa70cc9d78ef7f845cdb730a7ecd.nq.gz
│   ├── cc7867db924938ce20cadf329d1ce3383f7e48dd.nq.gz
│   ├── cca22ba3ee916fc6e0e35b96a1f28fc6193a913f.nq.gz
│   ├── d09bb89c318ae463c3c5fce57e7ec38f48104b11.nq.gz
│   ├── d45331be77777525e1d51d799ee638dbe9b8d55c.nq.gz
│   ├── d6aacc406d3002785f49a896a34be483864e024e.nq.gz
│   ├── d711d0f85f065348b0dcc60bd5cabd8a1c05617c.nq.gz
│   ├── d8cac61db1f00d03b85f451b645f9d6170ba0795.nq.gz
│   ├── da65764ade2a92b8b08b4313cca484af97c2698d.nq.gz
│   ├── db40c79ad5da3dd055a5e2922ca7b8b131c1256c.nq.gz
│   ├── dd4cd489e06d1ee62725b572caef57a7a82cc17e.nq.gz
│   ├── df22f55423d0209f9983e074d29705b9d3ba170f.nq.gz
│   ├── dfe04b5e3c43fee3442e3f0da1d5acce85650335.nq.gz
│   ├── e287a6c03f43c0af14d81ee82b35817ef9e50876.nq.gz
│   ├── e33064a14b5ef1502788e97c6ccd11338d373efa.nq.gz
│   ├── e5893d39cd043391dd3d9c52d6d35ab7d8b17381.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71a99920cf8183decded8939abb071a7030d6cd.nq.gz
│   ├── e80b22b4869a189c93bfe367986cea3eb00241cf.nq.gz
│   ├── e96ffadf7abf0ebeb8cb4cead5b984fd35194bbc.nq.gz
│   ├── e98134570c4f3289b238525b67b4fd561a692636.nq.gz
│   ├── ebe42c92dfd873b77c72aa6ff38dc9059c142156.nq.gz
│   ├── f032176299c47066274eb763900d2fde371256c0.nq.gz
│   ├── f5b57ff7ee8c0f90e176fc92e07847088bbf9a65.nq.gz
│   ├── fab94031f83378aa3bcf1a13cd61d7ba7b17c73c.nq.gz
│   ├── fb18065a23129834c9663a9d0d15005275ad2175.nq.gz
│   └── fec45a4b89899454493182864a80def2e425dad9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e4877d51d546f8c67b1cd9b49ab002ba3af37785.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 149 files
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

[goccy/go-json](https://github.com/goccy/go-json)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
