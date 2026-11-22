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
│   │   ├── 2aea44eeae35b9c77dc2ff672634034a75c9bb16
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6d67c23ddb01f54c30aade3ac1bd11ae4cf90703
│   │   │   └── chunk-001.nq.gz
│   │   └── b54a49257c50e1a0fd9051f3e1ca7ce157aed4da
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b54a49257c50e1a0fd9051f3e1ca7ce157aed4da.nq.gz
│   └── repolex
│       ├── 6d67c23ddb01f54c30aade3ac1bd11ae4cf90703
│       │   └── chunk-001.nq.gz
│       └── b54a49257c50e1a0fd9051f3e1ca7ce157aed4da
│           └── chunk-001.nq.gz
└── blob
    ├── 01edee549614cc993408ab510c3f5dd7fb9c5d3e.nq.gz
    ├── 01ff823e147bd87252c1ae08c188c2e2fc5e31ce.nq.gz
    ├── 024e18dfa52f5d1681de86322b737a99bc5082e4.nq.gz
    ├── 02a059c72369e69e8c81607672baf1371da9864d.nq.gz
    ├── 02de2d9332760577664d30fe6a220c60d51c9460.nq.gz
    ├── 030db4b8e3880446ade6d4205c443f219dbe6e42.nq.gz
    ├── 0362b34347f21e9658acd56eb5a1350a4abfc464.nq.gz
    ├── 0439b26e70a73c75c2a5328666880fb9d2b8b740.nq.gz
    ├── 044e736ddfed1e4c4115c3a9084ec89afb96a371.nq.gz
    ├── 04efffded35f3989b7ca538f42762416077a2356.nq.gz
    ├── 052e478eb948e754eaf2d3fa879dbb5e8d98d77b.nq.gz
    ├── 0530ee150f67419fd7593e09a3625edc8cf756f7.nq.gz
    ├── 0561cd4a908d222b65e726947f98e7fa85a69033.nq.gz
    ├── 05ff25e22f3d0219a6c7952f9e9015eada5308c2.nq.gz
    ├── 0600bc4c76314a05a1441eaa3e601c1eec200171.nq.gz
    ├── 063be160269544c477655e64736aabe85143332a.nq.gz
    ├── 0703389bf31982a64e15e03a411d5e7cc70a8385.nq.gz
    ├── 0733a6d0ca444a746b7a8e2db6e2daa4fc5f79b7.nq.gz
    ├── 077a48a7934d27bc887d799b483365659dfb1bce.nq.gz
    ├── 07cba4e4b7aaad51b38cb33f2c9c53cda8cbaad1.nq.gz
    ├── 07dc5f70c13a6106fa0f602ccccd3cc959aa53d0.nq.gz
    ├── 08415f9236713d9a64a7582fc9480da353ac0db2.nq.gz
    ├── 08d6cabef4438cee2cdcc56ea218a1bac268ece2.nq.gz
    ├── 093829a81c0758b377db8d1634fcc056dc7c76c5.nq.gz
    ├── 094360ea6be2a281a002e07259cd3802340f8b2a.nq.gz
    ├── 099632dbbb77349ab2f2dd2e701b8d9d7794f8bd.nq.gz
    ├── 0a078167749d374cdae9298d375ce513f4e5e6a7.nq.gz
    ├── 0a65cdd6892d4d202b6a65b26f43ea33b500c782.nq.gz
    ├── 0a77192a465af8d0b833ef9557aabc0420d40383.nq.gz
    ├── 0b6925d97ad9107d0de96b6dc142ec7d0ccde935.nq.gz
    ├── 0b7852b31a0b5c2c24ab80d4db679ece187f4497.nq.gz
    ├── 0b9a10f12bb49564b7aee9608b9499f5266c387a.nq.gz
    ├── 0bcb2993845166d03dfabcf6136b4f37e43265d0.nq.gz
    ├── 0bf13cd1feb972bacc6a69ed7d2594dc405b69ed.nq.gz
    ├── 0c5ab31163161ab47b6d03e487566aa932397849.nq.gz
    ├── 0c63c1da05ddf325cc1937aaf84a128788ef32f3.nq.gz
    ├── 0c77dcf433cb6e76a2ae40f9752ed97221673ecf.nq.gz
    ├── 0d9e6122b5cbbea43fae1b59b09809d6058376aa.nq.gz
    ├── 0dfabafa70b53758ab102a149968f52ab1b6dfb7.nq.gz
    ├── 0ec984f393250b061e2988997ddc4adf68750775.nq.gz
    ├── 0ef9a24cf70efd8a8ff17c439c14d40765844d49.nq.gz
    ├── 0f09198981c989530c268d7e4bae5ce24a411a6e.nq.gz
    ├── 0f2f4d6f9e2d1c3c90df059b5966d0fa18050fbb.nq.gz
    ├── 0f381ca7e91d14409f3f797e2a33f72a8c89c45d.nq.gz
    ├── 0fd061bd3a5fa1998023e538b496a38bca0f10ab.nq.gz
    ├── 10011b76377eebf7bdab8d920b0a8963731f08df.nq.gz
    ├── 1025f48789dddfc0aa80d18a9ef4c582014ec11c.nq.gz
    ├── 10580d8e58c848a0428cd5bcb603b97f970013af.nq.gz
    ├── 114b81f304bd129523696406213206dfba4bd066.nq.gz
    ├── 1185e51d51d723bd83ce3b55cd95bebcec2815eb.nq.gz
    ├── 11bca339cb525217ee443b5f8f861b2f9892582a.nq.gz
    ├── 11cf5dc358182d730c20f8a14568a9d6103f270e.nq.gz
    ├── 11f37946adcbfb6e2027b2ed2a2177adbe5f5314.nq.gz
    ├── 1214203b2846505308e3e7854672014add981fb3.nq.gz
    ├── 124f2112f89b68398850f44053b261a46c3a499a.nq.gz
    ├── 127806bdafbf52a9c0f43c37920dc61b9e55152f.nq.gz
    ├── 127ebc54a2efce726389319dfffc538284e915eb.nq.gz
    ├── 12c853dd68fbc44f620b7844a1bfbe2e2ec7c36b.nq.gz
    ├── 13286de2d3c5fdfe512583ec55ba9ed771c4cebd.nq.gz
    ├── 1354888ab718777653ae06c7b0a9b4b9e2e3fe0e.nq.gz
    ├── 135eed4ba0d5b96f1a60632c21befdde71ec291b.nq.gz
    ├── 136c10c7e33115ae1d82074e459509b1b2ac59aa.nq.gz
    ├── 13cb7dce86824cee20f5313fbf64559f65029cc5.nq.gz
    ├── 143aa8dfd2ce7c1794db6bfaf22279de067f5d02.nq.gz
    ├── 14f4cb4d52385c8c226918ff747772d05bc77053.nq.gz
    ├── 161abed29f86aeca2ddd7e03505dd57d125eb68b.nq.gz
    ├── 165bdef2d5cf432e86876ed7e40c07f6b17996f0.nq.gz
    ├── 166fc21e742bb07241781660e81fcc98e4083e1d.nq.gz
    ├── 1677001ea3a6e35b203c1b5da2f4fa12dd403d87.nq.gz
    ├── 16771debe1184f73124f9a7647b43391785c21fc.nq.gz
    ├── 1739c283a187b01b2b5c9fc539522ae7415ea46c.nq.gz
    ├── 1752da17c930bb9cd002a6416aad5020f80beb94.nq.gz
    ├── 17a2254e3093cec3fa6ae208d2d974a1b193784c.nq.gz
    ├── 17b2b481778090492be0c9f3c2dfb1cad25615b5.nq.gz
    ├── 17b2e3c2ea5f2d7635b3d647fdd79005185fbe57.nq.gz
    ├── 17cec9e63183a5fcaea06f8aeebfcbd767ec38cd.nq.gz
    ├── 17f746fb6a49e526b2492466aa53a3546cb45ece.nq.gz
    ├── 1822b0b1efdaa963b75350c36dbe9bb45a09d300.nq.gz
    ├── 18f7b7e767222a9f474e908fc68d1e4919884f34.nq.gz
    ├── 19663281d94a0b070e07851e52d74d306d91933e.nq.gz
    ├── 196764e3c8600b62869e148fab4397d7f580e1cf.nq.gz
    ├── 1a21e42065493d765ab526a6a7b0535d6da35cfc.nq.gz
    ├── 1aeff2dcf14c0edef973b262f5646a2a05fbabca.nq.gz
    ├── 1b3a98ee4405f4607969fb25ca582e960638a81a.nq.gz
    ├── 1b85ecaa66504105b154cd6b0054674845fa13f4.nq.gz
    ├── 1bb132b473030eb65d4a10636b98000202da7d01.nq.gz
    ├── 1c52c262f7d9a0530ac5d0f89b1349e47ef54d6f.nq.gz
    ├── 1c89c3886b7c3586417bb3c1c76032f46bbbea6c.nq.gz
    ├── 1c89ebcaa7a53117fd8805660d51a030d4bf455d.nq.gz
    ├── 1d5e483c3384333aa20d71921bed7fc2f2020013.nq.gz
    ├── 1dcfc13cb2ed674340734a3b207326817e18cbfc.nq.gz
    ├── 1e5889a50c73e56d477b0498016c9ecd243d7396.nq.gz
    ├── 1f359bd42264f26993e831b5fbd6151c520fc2a2.nq.gz
    ├── 1f6fde3a7b60d896d0bab471dad63c3fba7c3382.nq.gz
    ├── 1ffd596c6d67fe7807d121e1748c70be659cc021.nq.gz
    ├── 205b30d9b4575819751951a97af18421097acf1f.nq.gz
    ├── 20d16d399eeae2a826f16f66829e91d44200c5f4.nq.gz
    ├── 2209fe1be2de3925164650f34745cedcae86213c.nq.gz
    ├── 222524a077c534488c4d6bf4e33554528cdc30d8.nq.gz
    ├── 22fc9e994d0ef02d216055b319c10a1a8b3ee009.nq.gz
    ├── 230cba611c34a8241ae6663fc776ba9cac5a09fa.nq.gz
    ├── 230d5d2afe26678b6e660620d6a4b0bdf98efe86.nq.gz
    ├── 233f9335fcdc51cc74c4362105097558418e3921.nq.gz
    ├── 2370ec13e832101307366da2962d7b080c1e57b3.nq.gz
    ├── 23a6f17133d718c2bae629dbceaa43f30bb872fc.nq.gz
    ├── 240a5f50f02025a96ff86aa598fe48a31b2ecbdc.nq.gz
    ├── 243779bec35a98ea7938bbca0381683a2b54bc25.nq.gz
    ├── 244d40a3b6d389327d4903d401e6368156d3ca79.nq.gz
    ├── 24833380577d53b77b2d50372586365f0abbdd68.nq.gz
    ├── 250df7add972947bd0335cebb2f04ad1b84f905b.nq.gz
    ├── 252634b1297055691305afb38d9ff05eac5130a0.nq.gz
    ├── 2555aaf886e4ad4c3ebc9c592dab50d4bc070095.nq.gz
    ├── 2576c75c780df0fb3fec60bd7d9c050b298284d0.nq.gz
    ├── 25f8c323d731d499fc4ab32fc241044084f784d8.nq.gz
    ├── 26e0394b08d2ccf3e60edfcb9e1721f5a860cfa3.nq.gz
    ├── 2719c9a23d2a37c1dfb7402e79f03bd615701e53.nq.gz
    ├── 2736b026604a629ccca3736dd601fd0e6b13cf95.nq.gz
    ├── 275c59aafcf8f5d9bd932803d3b33ff616af97b2.nq.gz
    ├── 27cee47e4e054547aa15dcc5843fe3067d02c809.nq.gz
    ├── 27f287c84f19a007d6e635dda4076887ed2fa981.nq.gz
    ├── 2831f85208e6b8d9e8f7c964a8b775e3ad09ff13.nq.gz
    ├── 28748d6ab1a530a552d8796d172c2a283cbe0b47.nq.gz
    ├── 28837e3e87319197cca606ae0ea207720481b496.nq.gz
    ├── 28a73a0db6b085e46820e117ec800eefe6aee453.nq.gz
    ├── 28d70516666077b93487690550d4cc7e356ce629.nq.gz
    ├── 29a6dc3f42bc7cd04cc23f5c64b02f84539a3a53.nq.gz
    ├── 29d95e64bf006efa68529df0970e37ef1306d726.nq.gz
    ├── 29ddf927b2da22f90eb2537c978616413e457064.nq.gz
    ├── 2ae23dac0ffe794068f26c163b7245b3509f31c5.nq.gz
    ├── 2af9e2199f9a82479dc4c3e3717349e9bf70518b.nq.gz
    ├── 2b2755fdaeb14774bc2f5332e66c5c94b0261be2.nq.gz
    ├── 2b28f416b73a1e5b05c0e65133e870e93f6b7371.nq.gz
    ├── 2b476ddd6266d88925d74ef7bc259f0caaa1556e.nq.gz
    ├── 2b50fc9c24ac03d02e8ac25890e87aaaad15b45f.nq.gz
    ├── 2bcfd94a48a17cc3d6771bd7f8fe5cbbd0b792bf.nq.gz
    ├── 2c2259cebf7cf7f108085ca692de93266a579813.nq.gz
    ├── 2c8dc9acb8845f0fc262a431d9e6238b866eebc2.nq.gz
    ├── 2cd096d75043372ab86cb4461fdc11dd1423dec6.nq.gz
    ├── 2cd2fac541c21a2310b08f09247ba6cf98c82c8d.nq.gz
    ├── 2d4be016ac9ebf394948cc256023224ee5d70dab.nq.gz
    ├── 2e15e38b50ff51314da36c681595a1bec8d2f096.nq.gz
    ├── 2e4e998ad11721a1bb80384010ef8f8d0826401a.nq.gz
    ├── 2f182650206d2a80695129b4f0f3e7a306689d57.nq.gz
    ├── 2f62ac0567a2c871860ffc357a6a4e1e50d8beaf.nq.gz
    ├── 2f6e36a53064b45ae9f5721f7fe404333c6fa0e4.nq.gz
    ├── 2f7bb4adc6026ea42c3a57a2e55f66b3d1cfd918.nq.gz
    ├── 2f92f09b8fcbcd2444d4fff34871348133c2c560.nq.gz
    ├── 2fb6c7699db793be3a7ebf7059d9acbeda16f65c.nq.gz
    ├── 2fc4119c64126f8def98bc0afa147106f3f5b624.nq.gz
    ├── 3015df5b99531cbd99b140a296fafd2fe644598e.nq.gz
    ├── 304b87958ede2333425239018281ad5d79b50972.nq.gz
    ├── 30aea04cf3558f2005f46136325d0d481c68a89d.nq.gz
    ├── 30b8a6d062f578f08060537e7a48118a28f3b0f7.nq.gz
    ├── 311153b2a9dd36e436e8e6ca26f74410fcf393e0.nq.gz
    ├── 320dffae9651ffa1b4a1188adaf4c1140c07e20b.nq.gz
    ├── 32beec2990b8b5f4f2018daaddcb34a6b908e636.nq.gz
    ├── 33ae208cada0d2f2591f241e3d676cc8de83d962.nq.gz
    ├── 33eb2f7e63cf83b5b39cb4039cbaa51e45e66061.nq.gz
    ├── 3400fc64b1f0b5f285581a246f2d4d15a1499948.nq.gz
    ├── 340dd8d378b5acdff61c6b2a799f55643b634628.nq.gz
    ├── 34b5f6ff27aa2fdf6d2a0209879cc03e9cc7027f.nq.gz
    ├── 350f7b28853f26da75070aa2b9271d4d8ff1665f.nq.gz
    ├── 351b59e812519d3ce2456228ef515c57d8972504.nq.gz
    ├── 3566c5e42325eac35f23568e147476d3ea871ea2.nq.gz
    ├── 356eccc36bd18f3f9b931e363c40a0ad782d1d26.nq.gz
    ├── 35768047e8276d2f669fbd7e4bcef3568f296fd4.nq.gz
    ├── 35d7c23942ff9c3f0c9b59a085ed3a149022386f.nq.gz
    ├── 35e33786fcc71b859c3440387a2e50d1ae9c02ec.nq.gz
    ├── 365610069b25f3bcf839e92631fe4380ba078b34.nq.gz
    ├── 36675ab70af056c31624c27515fb78b33da72797.nq.gz
    ├── 36d13a0645b3cc944b51dbe3bedb88eb970829b4.nq.gz
    ├── 3702831efd21dbe7aa2710cb8b30c0287b8e51ba.nq.gz
    ├── 3768ae20e0ebc2e5b16b923ce4ea843c419a011b.nq.gz
    ├── 377f86a0574bbef99f78fba65dd8242b150e103a.nq.gz
    ├── 37d33f207f367518f65843b8f0ad214c069cb87c.nq.gz
    ├── 389659be7ba4d4c13212630f11f935d9f55a2d74.nq.gz
    ├── 389866c565e2a08609a4f58bd60a404fe1437486.nq.gz
    ├── 38e29331cab5f6aa93ada37e697b7c14f74d402d.nq.gz
    ├── 39991aa8b7f0be37d967109d2ba7bc3f22289402.nq.gz
    ├── 39d1b3dc862bc65e5609c7a4f4e47e0a6a429417.nq.gz
    ├── 39db1bb8a7cad551a4b24e2ba8b39cc4da8fa8ce.nq.gz
    ├── 3a00212b0bdd672a4288965bfab77fb626885949.nq.gz
    ├── 3a0ee26c447a45d9e5eddb1251d7e24e6609ca66.nq.gz
    ├── 3a73d266a6b348fca5c16c160696ce47498e8c01.nq.gz
    ├── 3ae4dc98e3bd6f68bb4a39c941e48b169ffe25c2.nq.gz
    ├── 3aebb6309685aa31b5eb80ad8d81a30397134288.nq.gz
    ├── 3b4281d0846183e31fa18f3f68e9175a673dfe7b.nq.gz
    ├── 3bf46c10425fda2a19593904858636e3fd6cdc76.nq.gz
    ├── 3c1201cf2a119130af9387d5175f5a9867cd3790.nq.gz
    ├── 3c6b3cc81baa2cb970bc8b571b7f5dfc5f5ccb17.nq.gz
    ├── 3c8057ca8c8bf647c98a9a5c57500e8af6a60963.nq.gz
    ├── 3cf5031d57a80a6a1339a42e0dcf62478bd51e8b.nq.gz
    ├── 3d06b062a6d87ebe4705aa35b7cae54df14e2f2c.nq.gz
    └── 3d64ec517511c81df3391f9e0901d7c64d499551.nq.gz

11 directories, 200 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
