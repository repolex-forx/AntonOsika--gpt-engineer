# Repolex Knowledge Graph of AntonOsika/gpt-engineer

RDF knowledge graph data for [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer), parsed by [repolex](https://repolex.ai).

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
rlex download AntonOsika/gpt-engineer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a90fcd543eedcc0ff2c34561bc0785d2ba83c47e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a90fcd543eedcc0ff2c34561bc0785d2ba83c47e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0188cd1aad5f5467b33d4608d5ace9caeeee83df.nq.gz
│   ├── 05a7c2c269ba683bb6054b0533d0141a70ea5073.nq.gz
│   ├── 05d30db8ba37bdacdba5de8a417fa59d5e198603.nq.gz
│   ├── 088b114a25144cd3c599dd0a895fb2c8c7ed8f98.nq.gz
│   ├── 09b47815ef2c8e2baa6ebc20a2acadd294845f5d.nq.gz
│   ├── 0f443925fabeb307602bfbce7b2610baa4281beb.nq.gz
│   ├── 0f7d3d29ee4337d60f4c91c56017e6e2e831546a.nq.gz
│   ├── 100c87842912dc06997eaf62a0141cf8b274478d.nq.gz
│   ├── 11a428de13faab383646ff9f81077024784bb61f.nq.gz
│   ├── 137a5558c869dabad04a01e5c1c00c9609672133.nq.gz
│   ├── 138ab50255824c599dd1acb60e270b95ced628dc.nq.gz
│   ├── 1553d542dd235f32278c4bc9b92c7b3ab96d6027.nq.gz
│   ├── 161a84052dfb733a63adf7431f0dccf5210b4b8d.nq.gz
│   ├── 172210af7f9b558f627fc5ded267133317879f27.nq.gz
│   ├── 177bfdb5a8499267fd7bf6408cc659945ce170d2.nq.gz
│   ├── 17fd588fb692369a24f6c3d185b555a88eb731ca.nq.gz
│   ├── 1887d241193679cf4f626d62e89a34db6ae5c28f.nq.gz
│   ├── 18f1591ec8fa80548e18bc7078128b6325728cb7.nq.gz
│   ├── 1ef45cc277bf929c66820673a2dc1f38cd5e7d34.nq.gz
│   ├── 1f0912e09d35602d4d9cbe7874fdb32ebbb93056.nq.gz
│   ├── 1f232730d0bf7f31d802a1e162f4cd4de2cc3c7f.nq.gz
│   ├── 21650b77c1fba2ebaf98980940b99fda12cb7d2c.nq.gz
│   ├── 218ace422c163537a085afe10d133ad4a5c4b4b3.nq.gz
│   ├── 223197b069c37a076fb50aba9ed69b1cee447662.nq.gz
│   ├── 235b36c8cf27849d9367726034714ac303cff264.nq.gz
│   ├── 2c3b41de8aea0bfb4a17f609037550c024d2e117.nq.gz
│   ├── 2c8aa2ba37d6754fa8ea74dc1ac6039282745abc.nq.gz
│   ├── 2f02774419ac9ec776ac9bca64277070444e7455.nq.gz
│   ├── 31e6ea2776a7f0e905945a1af5bdf5eac550ebf8.nq.gz
│   ├── 35eec6100e0f870c7cd1ade12a60b2d732281422.nq.gz
│   ├── 3700941b257915470acecdad20b2acd9ad57b469.nq.gz
│   ├── 37e4784b1e0aea41c7907a6e445a7f4cb40134c1.nq.gz
│   ├── 37eb91c4de3cbf45b0af291585e1736c42db3d5f.nq.gz
│   ├── 3b1d5bf58b432ba8e0a673d86e457f1b7c78af41.nq.gz
│   ├── 3de503f84ecd7f899cb8fd875d8fbac5c253de65.nq.gz
│   ├── 3f26a3ff200326be4499c8fcbaa0761b9638266c.nq.gz
│   ├── 3fe0daa264ea673f44dd0e2dbb5ce270281ec9a3.nq.gz
│   ├── 44eaeb6321f519059a2ff38d9c32cec7814068a3.nq.gz
│   ├── 45a611855a98e117e058c602d3c2ea976efa98e5.nq.gz
│   ├── 486e76a2e95427c91b20cb5a5a481a1bfd34f4ed.nq.gz
│   ├── 4b8ac84be6b1c28a863690791b225276c4a77b79.nq.gz
│   ├── 4cfdcf86a2190334e8875697ae750c6cbb377dfc.nq.gz
│   ├── 4d0d99729a4d53f10549417c3a27f29beffbed4b.nq.gz
│   ├── 4d4c123bdfdf4bcd211f9034994fca7201f6f9fb.nq.gz
│   ├── 4d8286343c52041ddc6a5c001169400a167f04fb.nq.gz
│   ├── 4f1a2cb73000745f6eafb2158d73b88da4fcbf55.nq.gz
│   ├── 4fb6f8ebafd2cf611cbe9d61e508637116d80a10.nq.gz
│   ├── 50205dc70568cc0079b0d842be6d1a8ef58819f5.nq.gz
│   ├── 5044c1f4da82bc1a48ec4ad83e553a97fdd5bc7b.nq.gz
│   ├── 50e3fe1811634cc18ea53e858f0191fa09426b0b.nq.gz
│   ├── 518f9f8cc0a779f1db5fa5baa6446561b39aff39.nq.gz
│   ├── 526e997bb6661b582b7d51175c29cb3707477098.nq.gz
│   ├── 52fc35a73ce1254d8d83bf5f11f0d3da6c10f004.nq.gz
│   ├── 541a5bb3199aca10e951fa93e749cf30fee90c8d.nq.gz
│   ├── 55dfea91d989f15755ad0e7aecd0dbd890760a89.nq.gz
│   ├── 577ae6c2e1cf78b9de13ce4ccf4190dc5ed99743.nq.gz
│   ├── 58b0fc0985950fcdca36d06fdef8a6cad200d344.nq.gz
│   ├── 58cb2e4fdaa68ea16e545d7a36b949ec382d303e.nq.gz
│   ├── 58fbf74fe265bb80221168fead0e47b43f5e067b.nq.gz
│   ├── 5a0c4135b7f3fb7f88c04b5259d698af0be906ce.nq.gz
│   ├── 5a952043af3bd842e2d9234055c66b664526d6f5.nq.gz
│   ├── 5c2d66c7a401b002f4f98c81be59957294d4c48f.nq.gz
│   ├── 5ee951ceee41a1777ae57c6178ed07e61c28a355.nq.gz
│   ├── 5fae0da39b8d010f5b29bc0e0401ef7c57d82dbc.nq.gz
│   ├── 604c2f5f6106266aac0d3dad9103ccf19e8ec677.nq.gz
│   ├── 60b7eba9a64805f7328241c561b985e8561152ee.nq.gz
│   ├── 62c7daf32bb142cb1cdb1216d7985394c77aac93.nq.gz
│   ├── 62dd0edafd02d65c2c3e000a167b09d8e839406d.nq.gz
│   ├── 636cc70e8b77f36e9c2070e69af65ad4a3334f9a.nq.gz
│   ├── 6459aed070c5da801db531710e3c39c8b91be22d.nq.gz
│   ├── 66de382e5df2d9ec2a1882aaad322e5522e071ec.nq.gz
│   ├── 69dade9182ab95b6a1c2c1e60ebd767029bc957e.nq.gz
│   ├── 6b443c484aa8680ec289cdf000a7f71e4b73ef83.nq.gz
│   ├── 6b46263424550f75f2faca0ca58e03c9c897e3d3.nq.gz
│   ├── 6e9725879ac99ae4e925af20c89484406122bdfd.nq.gz
│   ├── 715f96cb0e6b1fb358e136f0c581f5641ee6bf3f.nq.gz
│   ├── 72812bf1fc5b321c92c94443e8d8edf732d20fc3.nq.gz
│   ├── 74231021cc75aec9478f401f4910b7e8d2f5cb83.nq.gz
│   ├── 75d32313feb38866cb08cc229b9ed3b1448497a6.nq.gz
│   ├── 7644540ca2c4ef0914ae4e6c300294afc5d851f3.nq.gz
│   ├── 7713a6b3df86b57a46987b4350ffd0a0831155ba.nq.gz
│   ├── 78421e51241af8cdc0099a2d56724dd968a1e134.nq.gz
│   ├── 78e9447720b021a18b68eae654efc9c79faac32b.nq.gz
│   ├── 79dafd47f3542b61bb9f292b00b7cbb980e791a0.nq.gz
│   ├── 7c75210de25e0aa839c85f80f806edd13938eb35.nq.gz
│   ├── 7d2f8af002eda2b24914239fdee01adf2d961a0f.nq.gz
│   ├── 7dfb368b492a74f25cf0ea643f60ec4868205660.nq.gz
│   ├── 7ee8cb01ad866976e2debb90c368525433497933.nq.gz
│   ├── 82be330fb7eb1763951ccc4ac0e9352ce5c43172.nq.gz
│   ├── 8343ddb0d409247e321e8be7f357b5d4a2322593.nq.gz
│   ├── 8394de10a06de16ca2c40854f580bfb782ee4791.nq.gz
│   ├── 839fb87f4100e20f63a65c122297852534dce3f1.nq.gz
│   ├── 8776494b15e52bc1221bab3a06480d9b7a043b7e.nq.gz
│   ├── 89d3f646d584c2e82c76dec8cbc6af240eb79b4d.nq.gz
│   ├── 89d53b5e8c53c43bdabacd2c83050ed6e553a04d.nq.gz
│   ├── 8a2190089a89b2d5bceef5a6792fb7c8e0915291.nq.gz
│   ├── 8a8f1040737430c36b056c883ee29fd666fc3c32.nq.gz
│   ├── 8aab8a2e7e8aff5e8a760d217441c5ba8a4a07a1.nq.gz
│   ├── 8bc6e93875c3428b6a2e520005e31f5e57f4b841.nq.gz
│   ├── 8e4f7cb930235bda04f0c12f469db70657eaa416.nq.gz
│   ├── 90647760eb8cf85b9849420f8254d67c3a4add48.nq.gz
│   ├── 91e97b86a28860f110da84a152a3b1ac749c96dd.nq.gz
│   ├── 93e8f3300fd21ff6148970008dcfb4ed61d48a76.nq.gz
│   ├── 9469f8873df8bd220d9ec361abe39607cbda4a97.nq.gz
│   ├── 94fae70786f6f27dfff651a2cb3c33d2a67e8d58.nq.gz
│   ├── 957195238d9f6809d66112f913c73f75a8a760a7.nq.gz
│   ├── 963570f79136ea19b6eaf5468d746187a3150906.nq.gz
│   ├── 9738880560a33391acfc582b3a7d2f5bb7af95ab.nq.gz
│   ├── 97ff66cdeee1eda1f6e10db13097ad21aec47a4e.nq.gz
│   ├── 995eb517ecfdf443149b03e2cbbb46d7b6e44297.nq.gz
│   ├── 99d451c3a7debe1e63ccf3c0508e1b37c1785b52.nq.gz
│   ├── 9d70d0b2a3fc926935dfe902fa5111e539c13d39.nq.gz
│   ├── a006ca6788e12b5938bd0a289d7dd05836028ba4.nq.gz
│   ├── a4481104c6d4b5f1624dc574e461f7d829065750.nq.gz
│   ├── a491ae0aafa847553a95a3d4e08cf4574ee7637b.nq.gz
│   ├── a4aac759378e6923dfe7f5ac7cf70e809a11ac07.nq.gz
│   ├── a56867b9bdba937f0a9cb2656cc999d86aab2eaf.nq.gz
│   ├── a5de0a6f38e1ef73e8a399357e3498c480c7e3cb.nq.gz
│   ├── a611ebb531c7501ae358b18a23f0c2fb12d9f04f.nq.gz
│   ├── a6b50ccde752357267a109b73dbf8e5984dd7b4c.nq.gz
│   ├── a810b426669190795c1af5e470816f3dc675b1b2.nq.gz
│   ├── ae86f6336471f93666059295325bdd634eb9a129.nq.gz
│   ├── b01f5ab0d30e3d56e426bcf16cf15ba3ab3c92c5.nq.gz
│   ├── b0427e4d185a88fee7545ff2d92f2d23ff310cc2.nq.gz
│   ├── b10fec9033e70e405882f0b72a57a31cab3d0a03.nq.gz
│   ├── b154bcd8af9269ba369f5f7f7f9199f731c226ce.nq.gz
│   ├── b3ab8a65bc28f212cc811ab96f1e23d9e488d50a.nq.gz
│   ├── b44567a42608f3f38f6a8c3f8547b1eeb9f1dd5d.nq.gz
│   ├── b7e237fa0362ca1fa39c4b2333b4c0700d307c6a.nq.gz
│   ├── bb229c8c09efb4709f99de6516b3227279b998c9.nq.gz
│   ├── bdd6bbd10f50128c87dc9692387d31039f62ce56.nq.gz
│   ├── c0c793b88ea93b29b224b33379830d3fe6fbfd87.nq.gz
│   ├── c66a67e63ad8c350d9b84fb20b24aaf99b926f1f.nq.gz
│   ├── c8b012bf0c9c0c67ab2119364e801c2563f57108.nq.gz
│   ├── c9dffd97a6fba8d83f11ed485c48a811d106dd6d.nq.gz
│   ├── ca3cd0ad4fdaea752bb1ccc11e9beed29231aee5.nq.gz
│   ├── cc07bb0f3493643dc1db0fddb663b2c03b6a364d.nq.gz
│   ├── cc3b5de55c06b283bf699d9adef79f9c9de46971.nq.gz
│   ├── cc8f255c0d905bd6cd70a179336c3c920f80be0a.nq.gz
│   ├── cdbfc32e38d2842d25ad211bc43e750a3d5f3094.nq.gz
│   ├── d0ed67e71dd2033b02e13197893c451447db0050.nq.gz
│   ├── d172000568e1e51226ac647fe6e80b36ffdbd7fa.nq.gz
│   ├── d575b3d2438e549e45a37362920cd79551bffb23.nq.gz
│   ├── d6e0b51d91eae942a7d5c5544f9a80c6ab894c56.nq.gz
│   ├── d9a7cbc8aa37175e387bcb5a4965da90c21438d9.nq.gz
│   ├── daae9addaf35082ba7b9d31a0de8b2220c182553.nq.gz
│   ├── dbc4b4dec11ea15852d1587a246b8c3ccd88964c.nq.gz
│   ├── dc96935b66575fcad157920e2f51bcbe3a877a86.nq.gz
│   ├── dd54b6553d562a7969e151bc308f2bdc43f36011.nq.gz
│   ├── de5b979d4b14192b58e3315066c0302a52f4594e.nq.gz
│   ├── df5e867de19e1dfe9513f3a0d37ad289fde891ef.nq.gz
│   ├── dfbf7ba1c644da975c5058b78bc4bd1e4954ed43.nq.gz
│   ├── e1cc5a5294d29f2fd013ae2b34633733d7f79adb.nq.gz
│   ├── e5d0b72433e332a768ad40a1e9ea206ed1cff5d8.nq.gz
│   ├── e64764059e60df01569a009a49ffd112250fe56f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e743f7831f51e6cf15ce8e45558b317236961f13.nq.gz
│   ├── e7deadaff83f467525342d47e4f53d05139d7265.nq.gz
│   ├── e9959594b824cc2528b11cd9e767bd40b61b5bf6.nq.gz
│   ├── ee264031927202e419cdcda20a033fb15ee75706.nq.gz
│   ├── f0ed7282e45dbb1e5e43b5842448ad0cb7380e3f.nq.gz
│   ├── f2d330dc9eb7a98e596fe669d7c47acd126b1fd9.nq.gz
│   ├── f3759edbf3ebe7919a5abf70782b5548d9271cea.nq.gz
│   ├── f444b0efd6c4c742563633c96c44cf0d04582dc1.nq.gz
│   ├── f621698a9520857f9378dd2bb99ccdcb9d1067bd.nq.gz
│   ├── f71d1ae8a3de09fc44e43cdcba897b0954e90453.nq.gz
│   ├── f8bfac51fa5510e5f0c6929ce27a25fd2161d1d3.nq.gz
│   ├── f9071142eeca92beb20df7fe34d48199b38796d6.nq.gz
│   └── ffdc5bb6e270c24e6b8dee8b720f6b6ace3ccedd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a90fcd543eedcc0ff2c34561bc0785d2ba83c47e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 177 files
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

[AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
