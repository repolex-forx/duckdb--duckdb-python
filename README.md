# Repolex Knowledge Graph of duckdb/duckdb-python

RDF knowledge graph data for [duckdb/duckdb-python](https://github.com/duckdb/duckdb-python), parsed by [repolex](https://repolex.ai).

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
rlex download duckdb/duckdb-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6d67c23ddb01f54c30aade3ac1bd11ae4cf90703
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6d67c23ddb01f54c30aade3ac1bd11ae4cf90703
│           └── chunk-001.nq.gz
└── blob
    ├── 01edee549614cc993408ab510c3f5dd7fb9c5d3e.nq.gz
    ├── 01ff823e147bd87252c1ae08c188c2e2fc5e31ce.nq.gz
    ├── 024e18dfa52f5d1681de86322b737a99bc5082e4.nq.gz
    ├── 02de2d9332760577664d30fe6a220c60d51c9460.nq.gz
    ├── 030db4b8e3880446ade6d4205c443f219dbe6e42.nq.gz
    ├── 0362b34347f21e9658acd56eb5a1350a4abfc464.nq.gz
    ├── 0439b26e70a73c75c2a5328666880fb9d2b8b740.nq.gz
    ├── 044e736ddfed1e4c4115c3a9084ec89afb96a371.nq.gz
    ├── 04efffded35f3989b7ca538f42762416077a2356.nq.gz
    ├── 052e478eb948e754eaf2d3fa879dbb5e8d98d77b.nq.gz
    ├── 0561cd4a908d222b65e726947f98e7fa85a69033.nq.gz
    ├── 0600bc4c76314a05a1441eaa3e601c1eec200171.nq.gz
    ├── 077a48a7934d27bc887d799b483365659dfb1bce.nq.gz
    ├── 07cba4e4b7aaad51b38cb33f2c9c53cda8cbaad1.nq.gz
    ├── 08d6cabef4438cee2cdcc56ea218a1bac268ece2.nq.gz
    ├── 094360ea6be2a281a002e07259cd3802340f8b2a.nq.gz
    ├── 0a078167749d374cdae9298d375ce513f4e5e6a7.nq.gz
    ├── 0a65cdd6892d4d202b6a65b26f43ea33b500c782.nq.gz
    ├── 0b6925d97ad9107d0de96b6dc142ec7d0ccde935.nq.gz
    ├── 0b9a10f12bb49564b7aee9608b9499f5266c387a.nq.gz
    ├── 0bcb2993845166d03dfabcf6136b4f37e43265d0.nq.gz
    ├── 0bf13cd1feb972bacc6a69ed7d2594dc405b69ed.nq.gz
    ├── 0c63c1da05ddf325cc1937aaf84a128788ef32f3.nq.gz
    ├── 0c77dcf433cb6e76a2ae40f9752ed97221673ecf.nq.gz
    ├── 0dfabafa70b53758ab102a149968f52ab1b6dfb7.nq.gz
    ├── 0f09198981c989530c268d7e4bae5ce24a411a6e.nq.gz
    ├── 0f2f4d6f9e2d1c3c90df059b5966d0fa18050fbb.nq.gz
    ├── 0f381ca7e91d14409f3f797e2a33f72a8c89c45d.nq.gz
    ├── 0fd061bd3a5fa1998023e538b496a38bca0f10ab.nq.gz
    ├── 10011b76377eebf7bdab8d920b0a8963731f08df.nq.gz
    ├── 1025f48789dddfc0aa80d18a9ef4c582014ec11c.nq.gz
    ├── 1185e51d51d723bd83ce3b55cd95bebcec2815eb.nq.gz
    ├── 11bca339cb525217ee443b5f8f861b2f9892582a.nq.gz
    ├── 127806bdafbf52a9c0f43c37920dc61b9e55152f.nq.gz
    ├── 127ebc54a2efce726389319dfffc538284e915eb.nq.gz
    ├── 135eed4ba0d5b96f1a60632c21befdde71ec291b.nq.gz
    ├── 136c10c7e33115ae1d82074e459509b1b2ac59aa.nq.gz
    ├── 143aa8dfd2ce7c1794db6bfaf22279de067f5d02.nq.gz
    ├── 14f4cb4d52385c8c226918ff747772d05bc77053.nq.gz
    ├── 161abed29f86aeca2ddd7e03505dd57d125eb68b.nq.gz
    ├── 1739c283a187b01b2b5c9fc539522ae7415ea46c.nq.gz
    ├── 1752da17c930bb9cd002a6416aad5020f80beb94.nq.gz
    ├── 17a2254e3093cec3fa6ae208d2d974a1b193784c.nq.gz
    ├── 17cec9e63183a5fcaea06f8aeebfcbd767ec38cd.nq.gz
    ├── 1822b0b1efdaa963b75350c36dbe9bb45a09d300.nq.gz
    ├── 19663281d94a0b070e07851e52d74d306d91933e.nq.gz
    ├── 1a21e42065493d765ab526a6a7b0535d6da35cfc.nq.gz
    ├── 1aeff2dcf14c0edef973b262f5646a2a05fbabca.nq.gz
    ├── 1b85ecaa66504105b154cd6b0054674845fa13f4.nq.gz
    ├── 1bb132b473030eb65d4a10636b98000202da7d01.nq.gz
    ├── 1c52c262f7d9a0530ac5d0f89b1349e47ef54d6f.nq.gz
    ├── 1c89c3886b7c3586417bb3c1c76032f46bbbea6c.nq.gz
    ├── 1c89ebcaa7a53117fd8805660d51a030d4bf455d.nq.gz
    ├── 1dcfc13cb2ed674340734a3b207326817e18cbfc.nq.gz
    ├── 1e5889a50c73e56d477b0498016c9ecd243d7396.nq.gz
    ├── 1f359bd42264f26993e831b5fbd6151c520fc2a2.nq.gz
    ├── 1f6fde3a7b60d896d0bab471dad63c3fba7c3382.nq.gz
    ├── 1ffd596c6d67fe7807d121e1748c70be659cc021.nq.gz
    ├── 205b30d9b4575819751951a97af18421097acf1f.nq.gz
    ├── 20d16d399eeae2a826f16f66829e91d44200c5f4.nq.gz
    ├── 22fc9e994d0ef02d216055b319c10a1a8b3ee009.nq.gz
    ├── 230cba611c34a8241ae6663fc776ba9cac5a09fa.nq.gz
    ├── 230d5d2afe26678b6e660620d6a4b0bdf98efe86.nq.gz
    ├── 233f9335fcdc51cc74c4362105097558418e3921.nq.gz
    ├── 23a6f17133d718c2bae629dbceaa43f30bb872fc.nq.gz
    ├── 240a5f50f02025a96ff86aa598fe48a31b2ecbdc.nq.gz
    ├── 244d40a3b6d389327d4903d401e6368156d3ca79.nq.gz
    ├── 24833380577d53b77b2d50372586365f0abbdd68.nq.gz
    ├── 250df7add972947bd0335cebb2f04ad1b84f905b.nq.gz
    ├── 2555aaf886e4ad4c3ebc9c592dab50d4bc070095.nq.gz
    ├── 2576c75c780df0fb3fec60bd7d9c050b298284d0.nq.gz
    ├── 2736b026604a629ccca3736dd601fd0e6b13cf95.nq.gz
    ├── 27cee47e4e054547aa15dcc5843fe3067d02c809.nq.gz
    ├── 27f287c84f19a007d6e635dda4076887ed2fa981.nq.gz
    ├── 2831f85208e6b8d9e8f7c964a8b775e3ad09ff13.nq.gz
    ├── 28748d6ab1a530a552d8796d172c2a283cbe0b47.nq.gz
    ├── 28a73a0db6b085e46820e117ec800eefe6aee453.nq.gz
    ├── 28d70516666077b93487690550d4cc7e356ce629.nq.gz
    ├── 29a6dc3f42bc7cd04cc23f5c64b02f84539a3a53.nq.gz
    ├── 29ddf927b2da22f90eb2537c978616413e457064.nq.gz
    ├── 2ae23dac0ffe794068f26c163b7245b3509f31c5.nq.gz
    ├── 2b2755fdaeb14774bc2f5332e66c5c94b0261be2.nq.gz
    ├── 2b476ddd6266d88925d74ef7bc259f0caaa1556e.nq.gz
    ├── 2b50fc9c24ac03d02e8ac25890e87aaaad15b45f.nq.gz
    ├── 2cd096d75043372ab86cb4461fdc11dd1423dec6.nq.gz
    ├── 2d4be016ac9ebf394948cc256023224ee5d70dab.nq.gz
    ├── 2f182650206d2a80695129b4f0f3e7a306689d57.nq.gz
    ├── 2f62ac0567a2c871860ffc357a6a4e1e50d8beaf.nq.gz
    ├── 2f6e36a53064b45ae9f5721f7fe404333c6fa0e4.nq.gz
    ├── 2f7bb4adc6026ea42c3a57a2e55f66b3d1cfd918.nq.gz
    ├── 3015df5b99531cbd99b140a296fafd2fe644598e.nq.gz
    ├── 304b87958ede2333425239018281ad5d79b50972.nq.gz
    ├── 30aea04cf3558f2005f46136325d0d481c68a89d.nq.gz
    ├── 30b8a6d062f578f08060537e7a48118a28f3b0f7.nq.gz
    ├── 311153b2a9dd36e436e8e6ca26f74410fcf393e0.nq.gz
    ├── 33ae208cada0d2f2591f241e3d676cc8de83d962.nq.gz
    ├── 33eb2f7e63cf83b5b39cb4039cbaa51e45e66061.nq.gz
    ├── 3400fc64b1f0b5f285581a246f2d4d15a1499948.nq.gz
    ├── 340dd8d378b5acdff61c6b2a799f55643b634628.nq.gz
    ├── 350f7b28853f26da75070aa2b9271d4d8ff1665f.nq.gz
    ├── 351b59e812519d3ce2456228ef515c57d8972504.nq.gz
    ├── 356eccc36bd18f3f9b931e363c40a0ad782d1d26.nq.gz
    ├── 35768047e8276d2f669fbd7e4bcef3568f296fd4.nq.gz
    ├── 35d7c23942ff9c3f0c9b59a085ed3a149022386f.nq.gz
    ├── 365610069b25f3bcf839e92631fe4380ba078b34.nq.gz
    ├── 36675ab70af056c31624c27515fb78b33da72797.nq.gz
    ├── 36d13a0645b3cc944b51dbe3bedb88eb970829b4.nq.gz
    ├── 3702831efd21dbe7aa2710cb8b30c0287b8e51ba.nq.gz
    ├── 377f86a0574bbef99f78fba65dd8242b150e103a.nq.gz
    ├── 37d33f207f367518f65843b8f0ad214c069cb87c.nq.gz
    ├── 389659be7ba4d4c13212630f11f935d9f55a2d74.nq.gz
    ├── 389866c565e2a08609a4f58bd60a404fe1437486.nq.gz
    ├── 38e29331cab5f6aa93ada37e697b7c14f74d402d.nq.gz
    ├── 39991aa8b7f0be37d967109d2ba7bc3f22289402.nq.gz
    ├── 3a00212b0bdd672a4288965bfab77fb626885949.nq.gz
    ├── 3a0ee26c447a45d9e5eddb1251d7e24e6609ca66.nq.gz
    ├── 3aebb6309685aa31b5eb80ad8d81a30397134288.nq.gz
    ├── 3c1201cf2a119130af9387d5175f5a9867cd3790.nq.gz
    ├── 3c8057ca8c8bf647c98a9a5c57500e8af6a60963.nq.gz
    ├── 3cf5031d57a80a6a1339a42e0dcf62478bd51e8b.nq.gz
    ├── 3d7340275fa43b54d4ad5ee64c82a89e04256ca8.nq.gz
    ├── 3dba9d1498c15024d199568599c3db3d56a97453.nq.gz
    ├── 3eb834ce99909f913cb355c187556518a08d67d8.nq.gz
    ├── 3f7da5111c426341c0005c3139f074747fe0cacc.nq.gz
    ├── 3f82e7cf2adc8218f3e6288a5a0860a651125454.nq.gz
    ├── 3f9873985d2f27d47c1404b83d06c5d5028eb87f.nq.gz
    ├── 401a263981941529a114681ac9e91ccdc94436f2.nq.gz
    ├── 40971577176d5a3319ebf475f1d00f0d47399af4.nq.gz
    ├── 40c5290bfa947682b0cd6d1c477aece90285bd01.nq.gz
    ├── 417fae0d168a21271c6136b0d33a9f7407fe0aa2.nq.gz
    ├── 418273f0ab22c43845a1eb5e647bd97de2d30641.nq.gz
    ├── 41ee3d6928dd0eb34ceaa0e4adfd00f092f64e8d.nq.gz
    ├── 422338fd0946e5a6a9efd9690555c97d9e29a4a7.nq.gz
    ├── 440b78196c4fbc86744a82e675a91d45143f8e2d.nq.gz
    ├── 44e4a7cd7e1ad7aa9dbbd1a055ccb3db58cae8ed.nq.gz
    ├── 452849098db71ab2138f09b51ad83335f0afba3d.nq.gz
    ├── 45997eaf4d1d0d3186c6cf1a415a2024ebff146f.nq.gz
    ├── 45ef08459d8279cfbfe26825f9c79ab12043441e.nq.gz
    ├── 464dd79fb5e74ef452e73c427b332dbd55ec1131.nq.gz
    ├── 46566458c8ac515f8b392c49e53440dfe05b8f66.nq.gz
    ├── 46d52c5df0b4b31af976de9a868be7fe231b2182.nq.gz
    ├── 4739f459b142ce5db5aaa5958c16c16434bea9fa.nq.gz
    ├── 4881a9726683556f514626310b7ad350bdca2df8.nq.gz
    ├── 489601e3661125397d63e9ce33b0232338082093.nq.gz
    ├── 48b50eb86f01bb66fe97b2e8a38436324d2096e3.nq.gz
    ├── 49c697aef30855a418aee91a3ef6db5c75a03cb4.nq.gz
    ├── 4a742e740b03264db6a190dbe7c8b58ce6c84ca9.nq.gz
    ├── 4bcaaa07586c91fd4ae4f939f7d3f31a7eae463f.nq.gz
    ├── 4c585b7553933c7e9b1d1bc4b76a22db636c8f39.nq.gz
    ├── 4c765e965e5d6da35ab8c6d24ee6b16f6c5754d3.nq.gz
    ├── 4c93470507c831ce5d0a37e3128a37430170548d.nq.gz
    ├── 4cb3df586c0a29ce0bec52b3b65106f3105b7ad7.nq.gz
    ├── 4cc81e12541e35cd24d95ae84d37f9459c36b408.nq.gz
    ├── 4dcf5f93a92ea199c8883071c0527ab70eb9025f.nq.gz
    ├── 4e468d291eb9b9793aa1b76b102834423fc83c59.nq.gz
    ├── 4ea63176fb1680b7f3148a4b87a0adad3055a640.nq.gz
    ├── 4f7179e93dead451c42dac51e88ed55c06d75f4e.nq.gz
    ├── 4fba64ea99729d1191bbccc64e11d85792a73b09.nq.gz
    ├── 4fddac7cd56e8f05429e12e3940a28fd25ea634b.nq.gz
    ├── 5070fa1d9936e0176cd9c79fc10d0d8cd9ea00cf.nq.gz
    ├── 51d08709bd68574ea5d1eded6b6f981703955f39.nq.gz
    ├── 51e4b418e199fb861bea90c82a180b6943e5aa89.nq.gz
    ├── 52264769935cee9635a3ec0d5b14147d794d95d1.nq.gz
    ├── 5311b6850b486595fb2d5d3f7e236a42398cb77b.nq.gz
    ├── 53751402916a34268557a14f92e909f0b027c698.nq.gz
    ├── 53a8fdfb5c25d984f0a0942953e8cbf9e688b711.nq.gz
    ├── 53c24b4e5b079c94168c73d0563baf612322ea1b.nq.gz
    ├── 5400c888a9557f2883c12a4ac5284fea5857ac6e.nq.gz
    ├── 54caaf28045afb3a08b17753f11015b14738bff8.nq.gz
    ├── 54df7087fb123d783cdee01051b8d830bb78a09b.nq.gz
    ├── 5506cc0ed569ca6c7a66197787cebecfa36b7116.nq.gz
    ├── 55ef48e773841bbf24f64c5b1c27dbc2497e99a2.nq.gz
    ├── 5639d33b44d08f1de2f5db4883428c046844c3f9.nq.gz
    ├── 5641c18b5378c894a562ccc43313c5ec26cf2db5.nq.gz
    ├── 56cfd0226d6dcfd18593c676d6126a92052e5c22.nq.gz
    ├── 578a50d1575364d7a7a49df1ca84334c7da49fca.nq.gz
    ├── 58553cefb3903fa1e03ad9e6db7840c81f9ef86e.nq.gz
    ├── 5857a4fc1846311c8ae2940f45f74b5559a868f3.nq.gz
    ├── 588c7ecd67d543e76b4a9eb2da7f8cce6967dcb4.nq.gz
    ├── 58d7b296e3aa7b0cb3fc6e052aca8794c0c956fc.nq.gz
    ├── 58db60fd40388bc7ee11afc6b232d6e1cb82b918.nq.gz
    ├── 5901722b266804806850aff84dee1f3ea9722cac.nq.gz
    ├── 5a718d8f6840056690946d3e1d4e0ea7512eadd2.nq.gz
    ├── 5be16f7c66c4960583fee3c9a4e8caeffbe43d8c.nq.gz
    ├── 5c891e51a2b662a4bbcdc6f73a9a4b0a515c827e.nq.gz
    ├── 5ca8ca638f4a31051d83de9dcc10c618b300baf4.nq.gz
    ├── 5d73f49047a6b17ae7b1c0f98ed642d1a929ada5.nq.gz
    ├── 5dc88402c203f63e1f5b967d14a215f7d2849aa2.nq.gz
    ├── 5e533a30105fe803fe1d47a01c62bf2d9c86a126.nq.gz
    ├── 5efd284ba2cf3f63153dca36e9a5fade2c5bf9b2.nq.gz
    ├── 5f0d0442d39ea9033101f30c2475e080032b1a28.nq.gz
    ├── 5f384939354d2e44f80a8fa534a2c6f6dfd3275f.nq.gz
    ├── 5f61b3bb5b5bc9ae7046e70ecbe1cb8f7ec8ef90.nq.gz
    ├── 5f784453af3a102ff9abd1c013fced148376d5f8.nq.gz
    ├── 5f8a832a7f282696ffd06dfdaf37fa72a3e47666.nq.gz
    ├── 5fb37ca7e2ab8d16f688438f2c8919de00677ab0.nq.gz
    ├── 6008eba5adf7ea52a8f44c55c51240d458f02988.nq.gz
    └── 6042ef31251c7b7c4e712c659b58ddac25f83f32.nq.gz

7 directories, 200 files
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

[duckdb/duckdb-python](https://github.com/duckdb/duckdb-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
