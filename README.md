# Repolex Knowledge Graph of confluentinc/confluent-kafka-python

RDF knowledge graph data for [confluentinc/confluent-kafka-python](https://github.com/confluentinc/confluent-kafka-python), parsed by [repolex](https://repolex.ai).

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
rlex download confluentinc/confluent-kafka-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47d124053c0cbe96537ecc77ce834b920ba5c689
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47d124053c0cbe96537ecc77ce834b920ba5c689
│           └── chunk-001.nq.gz
└── blob
    ├── 01a74d027ce61b26bf89076ab21009d5c79468aa.nq.gz
    ├── 01aab8930edffea84ebb5066932d8564fd7c8ad6.nq.gz
    ├── 02f2aa00406c193c6fa9d64d30db915c8827beb4.nq.gz
    ├── 030e9e939c3808f468766365d953616caa4e0012.nq.gz
    ├── 03976574fd8112de6a7d48a554ffae0fa96a4300.nq.gz
    ├── 04feb9121d6625eeed5188133db15a0ce385e5b6.nq.gz
    ├── 0519ecba6ea913e21689ec692e81e9e4973fbf73.nq.gz
    ├── 0522a2da549aa0d38c200771a47fba370f13d430.nq.gz
    ├── 0542bba5dc2521b6fcefecf4a632e50da5fc132f.nq.gz
    ├── 05a003122dce178755c4fe3fd1de8794ab55a2dd.nq.gz
    ├── 062092e069969fc72277f25ff017eaf348e00a3f.nq.gz
    ├── 06c23eeeb0bae6d6f7ad5ca8bcdd586b03e8a298.nq.gz
    ├── 0703c1c2091c854a8935d1e19e0349fb242a9dca.nq.gz
    ├── 076b3843bdcf1933f2b1f9744a8eb18f45129b79.nq.gz
    ├── 07d2c168a535103bdab2ad1b2ec1250ab3cc7af0.nq.gz
    ├── 083f3811449f68b094fd9c843f27ac4c4f9403d6.nq.gz
    ├── 0847124bb5e5b50ab79e11c919e71deb8ee8cd00.nq.gz
    ├── 088da078fe8d13ff2a73cf07ee811bf75cbfd0fe.nq.gz
    ├── 08a4063b19a5f8d0baf9161864b8d2a4ae91347d.nq.gz
    ├── 08b635a8fb66b770dc2ba41b03ba641a5724da82.nq.gz
    ├── 091c5dfdb0b2d90c99ea7515ef0bf752c6f445a7.nq.gz
    ├── 0998ecea14a040dd370f8a54f931b89ab14cc001.nq.gz
    ├── 09b77b4264dd9bfbc1a4562dd19dade1c4ed8965.nq.gz
    ├── 0a0588d2c73a66b4709ba5c079312a877c01e1d9.nq.gz
    ├── 0a062d69cb1014f733c7fb17be4f2885abc30182.nq.gz
    ├── 0a9a6a8f89e41a56001171d39bcb281a11dd84a5.nq.gz
    ├── 0aa59564cb90ab34f407ed18ea3b510c00d3a61a.nq.gz
    ├── 0acf81a06451f0acf44e123b64d116d3f9b30f32.nq.gz
    ├── 0afb2fb6e86cd9f2a54ff5f0d85f32eb4a3abd8f.nq.gz
    ├── 0b3160ac92104f4d95964a2ccb038c0c3912a4f0.nq.gz
    ├── 0b50887dd95a90250eee31db21734ecb88968198.nq.gz
    ├── 0b7b8c351e0551f7bcd667e8bff9932928e67de0.nq.gz
    ├── 0cdd243233c0d817349b1a825793750df8d3e271.nq.gz
    ├── 0d89df45484b4bbd0aeb105d88eb7dcc86036b84.nq.gz
    ├── 0db882288ee3f1913cd2918a85d5c69bb5da43f2.nq.gz
    ├── 0e2284a2de81d2b1eb3385630e130c32c5b1ff95.nq.gz
    ├── 0ea88465bd3c6768a4815de775f63e68654166e1.nq.gz
    ├── 0f0d4e0d3594e83ac9e46e24e793192fb6297b18.nq.gz
    ├── 0f1f0e9ba77166a71b8e0a380092066c86cf8fbe.nq.gz
    ├── 0f87be53104d482fa01fe737a68d83c507223a9a.nq.gz
    ├── 100c0dd141e79f15e68e1a7aed202a80c1110c88.nq.gz
    ├── 109270f87b685841c147a55f442b1a33418c19b6.nq.gz
    ├── 10b073bdd217b84349c7f2d0e61ca514a6726c6f.nq.gz
    ├── 1187ff65607a3d08db9aeff3adf1c6a8f287adbf.nq.gz
    ├── 11bca1dc4b44f52883226db2581fb77f9cd0ac54.nq.gz
    ├── 12021b3dead99e74423d954ab7a52470dbfbc2a4.nq.gz
    ├── 131c29c5d2794e770c820df401120ee4cc29d0ba.nq.gz
    ├── 135ddd27ae566791421dace9256104ba624b7976.nq.gz
    ├── 13a575aca9f925b9d1311c8f8f10a0bccfcaa2b3.nq.gz
    ├── 15b9ca37555c74b6378bf3408bbc9b30cd48232b.nq.gz
    ├── 16a407449f80f52298a0d5c2c93fbed3fa881712.nq.gz
    ├── 171954915ba60f08c2f000b4e0f634081374bdee.nq.gz
    ├── 1768c854787bf35bba705cf0aaab5ba6250739bd.nq.gz
    ├── 17ba2603d99823be1458ac2a87671eb229dc69e1.nq.gz
    ├── 18caeda1bd6f47156ee80531e88cae07b63fcb29.nq.gz
    ├── 1984374327314252b9285019b00ce425a35667db.nq.gz
    ├── 1a49424c4682f9feae6fdf3fe20bf621f78a1ff5.nq.gz
    ├── 1a731f2795b66effb71aee35ba5b85fe161ab3f2.nq.gz
    ├── 1af5afbb94414a3468ea4b4455af3cfc86d1dd25.nq.gz
    ├── 1b6960d92ad968beb7e9da61bdc5ada27f169480.nq.gz
    ├── 1ba276234cfe2c1baae6428abfe28d1a51bd72ec.nq.gz
    ├── 1c45e5251e6d14231b5c2313686e86480dffeb97.nq.gz
    ├── 1cd75db6b810deddcc1112d59614b98c521f4745.nq.gz
    ├── 1db21dc53bef9809f32f0919eff2ecf0903ad86d.nq.gz
    ├── 1e2effcfc7f7b22029585472c143bc2de3e9c6ba.nq.gz
    ├── 1e4ac33df7185d3ceeeb863800f1a8c4515f7f7b.nq.gz
    ├── 1e6ff56f651de2abe8d638c934c1b8e9a1dad846.nq.gz
    ├── 1f1c8da18683b4bbb4730d13569948f4b050804c.nq.gz
    ├── 1f5de7404ef8cac48ac59f4bcbc81dfbb3c86255.nq.gz
    ├── 1f68200e366d4985d82a1ba91fcddeacd4eea1a2.nq.gz
    ├── 2015acdcd579f150ec494d5f773c62032508fb8a.nq.gz
    ├── 2023d8c27ca003fabedc94c6f1572ff76e680d8a.nq.gz
    ├── 20396d295e8d08a0b53eadb3ef4ceb0d6cd0c923.nq.gz
    ├── 207427f3b5a0220e1cfad1e8de953b1f4f4462cb.nq.gz
    ├── 20d7c5b27e5a1cb4cf43664a2a8819fe8865a377.nq.gz
    ├── 2246c4bc2911004a684df77bbf221ec55fb1545a.nq.gz
    ├── 241db0baecc3b9ce40dcacb2fcc30186ea211459.nq.gz
    ├── 2485b33246480696093d486ee9e8595411dc0e34.nq.gz
    ├── 2560107a40fa0684a5515df9e12986b60a1c9e04.nq.gz
    ├── 2568a50787567b0736df7350bba8a57db7244e3f.nq.gz
    ├── 2694c74004466a4256b70d40851a634b47814beb.nq.gz
    ├── 2732ad5d3770ad8dbcbfd7c0847d69f46ae28193.nq.gz
    ├── 28358333797e2250631836eaaf037c09e9924a59.nq.gz
    ├── 28afb444d31d6820525394c04222b9400a759bc1.nq.gz
    ├── 298a8aae98440ec7c52109f4f7a18ccad73903d1.nq.gz
    ├── 2a849a489a06c2129e557a7b9cb7bd024c2ab2be.nq.gz
    ├── 2b4389a06120a47b71b24ba04358e803091b616c.nq.gz
    ├── 2b886948fe00943e8b213fb4d0ebfd376474d831.nq.gz
    ├── 2d6dd51eb34ccd603c7cfda1c0436223f6547a2a.nq.gz
    ├── 2de225e3383568720239c41dcb176a097066ea4f.nq.gz
    ├── 2e3d5a8fb557d7675e1e4d98a794b922b29add84.nq.gz
    ├── 2edd95dd397992f471dafea5414754547cacc196.nq.gz
    ├── 2f194709b461825689cbe81b82f01553ebb3419a.nq.gz
    ├── 2f78a4ad799cd93e557cb3a656cb50b26c3aeb7b.nq.gz
    ├── 2fed58f90ecd94fa754a54f55f376d0f80e1020f.nq.gz
    ├── 30e6cba1e7b19cc4ffb009d2d936f82c283498a9.nq.gz
    ├── 30f1b8aadde77b40e779e9557e02ac366cfe74fb.nq.gz
    ├── 31c79472eb7b08d78c9454cea032820788b94a1c.nq.gz
    ├── 31cf903758c0f49d2050f811c98acf0a5a9184a1.nq.gz
    ├── 34791ff2174b36919fe9622d9bd927a6e87bb8ce.nq.gz
    ├── 34c8375137a0717543f828cbc36c4d3dc2b23f91.nq.gz
    ├── 37297b9becdc86b08cfa08c1f8df8a0352b41d68.nq.gz
    ├── 3737a9a0aef3eb6b8605df47637f67d6debce30a.nq.gz
    ├── 3844b0899805ffa5192e0e23f4647bcca8bc3690.nq.gz
    ├── 399bd6c22aa9eba654398d0ca5ea6accd2df1c41.nq.gz
    ├── 3a40c9542c48f47da81e12129a29e77d4dd2d8a3.nq.gz
    ├── 3b03af3cc8152ddea8094cfee3f769e2c6f948ea.nq.gz
    ├── 3c203200544be42223a6e66005b6fc29bf0da7d4.nq.gz
    ├── 3c332eafca70949f3c56e71dfe8de85c76feff8f.nq.gz
    ├── 3d4d28a17b9047390bb0c2371459f96af4c2c342.nq.gz
    ├── 3d928ea5f4a997603bf0f48fb30b345d627f25ab.nq.gz
    ├── 3e3dd992d51754a31f61ad613c080a55fe80becf.nq.gz
    ├── 3e7ec97a7ad221c1e0c3e842f465ff05d1def3f7.nq.gz
    ├── 3efc0f4c4d0692ed06bbc059433b4cba33d713a5.nq.gz
    ├── 3ffd090647f7d23d1b942cffcbe55f2b0d980b2c.nq.gz
    ├── 404255bbe16458bc7c378612ee1b44e7af633bca.nq.gz
    ├── 41570bb7f77157b12c89aa80d7542eea48500f2d.nq.gz
    ├── 4157c9176b93e63c5410fccfe136249b68987d7a.nq.gz
    ├── 41e23a41ef3e1775f0067240bdcfc2488d9eec0c.nq.gz
    ├── 4243c0eb9aa7d1148146de48c23267c59db6419c.nq.gz
    ├── 42f00dddad229c1665379cd75adac546e1395be9.nq.gz
    ├── 4335a622926ce3905af5f2779e64f34a2655508b.nq.gz
    ├── 4364d9b527c649d0db83da80c7f4a77989096759.nq.gz
    ├── 43a3d87754742e62ddf50b3a0736d3e6a4ad25d4.nq.gz
    ├── 43beb640471d9b7f880f34bfd5b308667dd54b66.nq.gz
    ├── 43df355216f95273e10912c15c611b179d1c43c0.nq.gz
    ├── 444a6993a1c01c2906e4096ed0bf27df350f25dd.nq.gz
    ├── 452be43640cc7a4e6b84b4b5ace6a01751906ff4.nq.gz
    ├── 455e5f0d80d9ba3592de7151304e93c686a47ff1.nq.gz
    ├── 457083f6ce193f0dd145b08454d8cd5bc42a27b3.nq.gz
    ├── 457dc1978e48e08ebc04c96ce97ba75167f6b975.nq.gz
    ├── 458d59973c501b4e7c369df9e2723bfcbb757a05.nq.gz
    ├── 45c2efbd3d585ff099d64bc6512ea24b57e8849e.nq.gz
    ├── 480acea69587e70b89a95dc0496939ca4e276521.nq.gz
    ├── 48b3274f2f5778c84a0b9cc2101e38c9708faf1c.nq.gz
    ├── 491c909b819c328083307ca8c05580d1b4656004.nq.gz
    ├── 4a7d3797670b8e600290f88e254037e1160ad168.nq.gz
    ├── 4bb43856c30ea979caf51e474275b485cbd36de6.nq.gz
    ├── 4c6551b3ab97e3780584c53c33462069d9ef0fc1.nq.gz
    ├── 4c6fc60f0a1cee2ff192dbacfe204309512b51a5.nq.gz
    ├── 4dc07b5b061be2aa955f62335ec502f80bb323c4.nq.gz
    ├── 4e70cdd14206390955b7591493a8b3fb42bc6044.nq.gz
    ├── 4ebe4207aa3efac5c48dd6c8955468a9c0292b39.nq.gz
    ├── 4f4a4e3a17a4ef53a076d7d58e3a07dab7109b2c.nq.gz
    ├── 4fba6ef568d832e3507a0fb6d048a64b8b1e3ac4.nq.gz
    ├── 50582affa371d358d43245927cda4dbe82641055.nq.gz
    ├── 50620929159066b3016eb61602ec725d059eae96.nq.gz
    ├── 509c90e384b10f6c6704c0ee0454b9c5bfaf1b8b.nq.gz
    ├── 50a6f2e0bb3c791f6a0cf7df8d54376b5aee2848.nq.gz
    ├── 50ed99bd2c6c6c3421fcd269f1de6152ae2f8782.nq.gz
    ├── 51743ecade5e0a56396559c312ef6d29c19d8f0d.nq.gz
    ├── 53828e46d5f2f7e29767e83f268418b38cab919a.nq.gz
    ├── 54d0ee9826e20c3b209ac4e0e94ed7b28e955682.nq.gz
    ├── 550d5aa27595052ce748764f18a2b3710bd0abef.nq.gz
    ├── 559dde662cd8dea75f2ae208e5655f8be74279e1.nq.gz
    ├── 55df32397223900a0b578ddcf481cd4f532ce571.nq.gz
    ├── 5800e1448f9bb3675768c47a4c6885cceac15116.nq.gz
    ├── 5803fcfb13636b5250a6770df527a52f95ed3b75.nq.gz
    ├── 589650b14c604377f48c1582e68818ee0970f51c.nq.gz
    ├── 58bbb13788ff82a1624adc4fb078b17319c59111.nq.gz
    ├── 58d8a63696bda4d63fef5c4e544818abd8cc36d6.nq.gz
    ├── 59735dc290f2a4edb83c3c023d08884b52cc40ea.nq.gz
    ├── 5a6b12738e2d8404b6fcbd0dbc68692c035702a0.nq.gz
    ├── 5a7b410064e1b038d7a58b9b3a4090e566d67688.nq.gz
    ├── 5ac328be998bb8facf684504b62400e49fd6aa04.nq.gz
    ├── 5b318f25a3e60a877fff39150173473bceaea7b9.nq.gz
    ├── 5b6c8d32840f2fa41204d5462770c0ddfa447e9f.nq.gz
    ├── 5ba94c9323500461caa9fcb26d58a38e86e4b02c.nq.gz
    ├── 5bb6f803a239513a1d09f01c628e09098947307c.nq.gz
    ├── 5bcdded66b7edc7258645f5833ed67cc76a43706.nq.gz
    ├── 5bf6031553a0191c47ca26d035e855a0be7f26ed.nq.gz
    ├── 5cbab9a7f974499989a43ab74733bc50cb2bfe69.nq.gz
    ├── 5d573046440355a64a4df4c20587bdd173c2bb0a.nq.gz
    ├── 5d6a76bc2518829c3a02fc8153c2888427a99366.nq.gz
    ├── 5d7ff61247cfab5048f302602d75751adbf0a92b.nq.gz
    ├── 5d9c1b91d723f897027833d4acfe8ad86597b1e7.nq.gz
    ├── 5e32c661aab551bf15095baf5e4f6de65a7e706b.nq.gz
    ├── 5f1cad234f15932c74929fc5f06d1ae01cc6aa1c.nq.gz
    ├── 5f414a7551a99e04254ff6a924d6106236f1db7a.nq.gz
    ├── 5fa933d7101e6a8f84651508adac8822f1e9e624.nq.gz
    ├── 600940c18b00b3e1e435b217750978b75cb4559d.nq.gz
    ├── 60a4689cf86e7bb41336c151e558cf8ac4937d6e.nq.gz
    ├── 61ac2c7790ffa0cc170c234ce313c03c21cdfab0.nq.gz
    ├── 623be3ca359fc80d6e9a4effee2517966d161474.nq.gz
    ├── 6352e0684bdf4b2ece04bba2c2de44180a2b83f9.nq.gz
    ├── 635b3245fbfc69281481a9f84c0834342c10afb7.nq.gz
    ├── 64ab2cae768fb06b940177f1897f28cac315b2a8.nq.gz
    ├── 65bd5468ca8597444d1e80d5200c0d8acae1a47d.nq.gz
    ├── 663eba360e2601c87a1617682e6dc419dc4acab5.nq.gz
    ├── 66641df48353150b6ec02c9a636ccf60ebe8fe35.nq.gz
    ├── 667ff1da789f70074fd5de73db2b2f5c69b42cb2.nq.gz
    ├── 6713aa11f9640e2ceca63ab35abce2d216feadd5.nq.gz
    ├── 681e470adb9b45a5c6b25a601e7b15584b7f8a5c.nq.gz
    ├── 68872e00e388fe8c2813e39381c579c687fb6e11.nq.gz
    ├── 68d33ef04d3f808b98e9f31a33c5d5a3e0645d00.nq.gz
    ├── 693ba03596c1e4854919868ca472f48eebc897aa.nq.gz
    ├── 69851530dd001db25b8c95ea84a0da25157760f8.nq.gz
    └── 6a7023826cff364275c2145feceec87b76c28863.nq.gz

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

[confluentinc/confluent-kafka-python](https://github.com/confluentinc/confluent-kafka-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
