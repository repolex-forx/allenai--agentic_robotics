# Repolex Knowledge Graph of allenai/agentic_robotics

RDF knowledge graph data for [allenai/agentic_robotics](https://github.com/allenai/agentic_robotics), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/agentic_robotics
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 340731d9d39ca4a4f5fef23d2fe7cc9f1050fe12
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 340731d9d39ca4a4f5fef23d2fe7cc9f1050fe12
│           └── chunk-001.nq.gz
└── blob
    ├── 02b0d71ea45105a1fe5ca81eca083dbd26ed0169.nq.gz
    ├── 02b277bd4dfb981ae17fe3e41e2eba7086b05e81.nq.gz
    ├── 02f542fff09b554800f406862a23827abbc4e953.nq.gz
    ├── 03417c3256c522ccc8505b0503a27d61bbdc701e.nq.gz
    ├── 0381af6b25a646cb5a5c1a734267b3d3733c95c9.nq.gz
    ├── 04ed28110e27031a95f39c1ca9f393dd8d124b8e.nq.gz
    ├── 0524e6b17f7042de797c9e07ef70bad55cc7223d.nq.gz
    ├── 0613ed6ca18317c53a2b58212a35c41409a3e705.nq.gz
    ├── 06f5bc9a9e26bffb52edcf93b8c1ba88b8ffc46e.nq.gz
    ├── 0702eb697d271fcbddb5cfaf23052009044c21f4.nq.gz
    ├── 072f781111af09fb678bd634d72317daff7dacbd.nq.gz
    ├── 08393758b2cc8db3f09eca1ec8e11afe9c569863.nq.gz
    ├── 0969046485335c2d057efd15769ca6506715b7b3.nq.gz
    ├── 0a0d02b0a74616cc02d7e528b85be09f32fb3814.nq.gz
    ├── 0a26eb500a04be5a5f95be1d0311e780dddbe850.nq.gz
    ├── 0a5f8aa460306193f24772981377590dc070e9f2.nq.gz
    ├── 0ab5ea284b1ee534e0166ae2044a8cb611630112.nq.gz
    ├── 0ae22df28ff75735c2303da85af04dce9ad61baa.nq.gz
    ├── 0b51ba1356536ba718265d6a4ae432a7de2f2fc2.nq.gz
    ├── 0bccc29a7f33e5228f6c4fb97bc1db382cc6ab3e.nq.gz
    ├── 0c12ae3a3ca3df88fe6ed745fbddf189cd1aa6cb.nq.gz
    ├── 0e15fc592d71ab684861596534e11e48d13d64c0.nq.gz
    ├── 0e58286d0114d3303eb375d4f8f48569b1e4528c.nq.gz
    ├── 0f9adbab96cbc897900a5e3f9e4ddd2a77d53b87.nq.gz
    ├── 1062d1e81003abd4d455ba01632d176ab853371e.nq.gz
    ├── 10651ad6c32279119aa65c1945fc921309303c01.nq.gz
    ├── 1119bd68ff8b69ba15180dfa4aa06f6edde326f3.nq.gz
    ├── 113bee67bfed7a893266016ceaac3a0108a54474.nq.gz
    ├── 115ea8ce3090735baa53a20177523b6f1ac237d7.nq.gz
    ├── 12c0077774f00b48c505e54cb486019fb1118f4c.nq.gz
    ├── 12d5cb085db5a3bf2f6b24e6a4d5594d5b03af23.nq.gz
    ├── 12e38279bbc9c3217f1dec1b35f7f82bb9314366.nq.gz
    ├── 1388596534a1054f976cb69ecdd712031edbc8e0.nq.gz
    ├── 14e71e6d9304760bd552c1d057e08c42ac6aa205.nq.gz
    ├── 16143463e3147218df2f57d7ee2bf83cc43a99c5.nq.gz
    ├── 16f75c37d333be701e3e9068e89dfaac502996bb.nq.gz
    ├── 1704e2809e1fef6b8fbf6a859ae330f43ec9b034.nq.gz
    ├── 170f829b72991ca2516d858b2625a320750f2f08.nq.gz
    ├── 1714b3fbdbb3b53b1f77cca5bdd3d22bfaa67331.nq.gz
    ├── 174e4c0c0483944963c544a9fdf3b1ec6cab8cd2.nq.gz
    ├── 17c91c721cb10df5d57422cc18b9a310165061d3.nq.gz
    ├── 18193a2f869e9408dc68f2b580f4916c052cbcda.nq.gz
    ├── 1855509951be2d2b8e88824dab00fbd31be8f72a.nq.gz
    ├── 1896af217cc9437cb98eae94aeb0548246306760.nq.gz
    ├── 18bc1c8067ab07255ed9c4563e680f24ffa47508.nq.gz
    ├── 18edb4b8cf7482fd55cb24b649ef3edbf1216060.nq.gz
    ├── 1a7b10822e2ee020fb0db4300e91a0b0d411d638.nq.gz
    ├── 1a7d0b169ffceb16dc4db5c8b105c51ee389990e.nq.gz
    ├── 1c1d29b658e1d70aab3b535ce595f1bc8f6b1604.nq.gz
    ├── 1c2442036cae61c178cb657921b22138d5c83117.nq.gz
    ├── 1c289d85913ba96fb590ca896edcde8ab0493b53.nq.gz
    ├── 1c50900c46594eccf184079bfd372574611b6749.nq.gz
    ├── 1c82f51036b4d13fcb0060c86ca0c0a716a962de.nq.gz
    ├── 1d1195d128b18367db4001ec1e343ac2c3c07dc5.nq.gz
    ├── 1de6b6d3374dbe6b39e8fc4c5c9bfc249351404b.nq.gz
    ├── 1e193cda8b1ba48f8b023eb786d6cdc7dc439058.nq.gz
    ├── 1f13773683ba8f57ae036d1cfaa7deadec23adcb.nq.gz
    ├── 1f1cabc4f80728e54c46db2b79e6ea40712bd545.nq.gz
    ├── 20011ac2b90c78a77f7457de89a3bc0cbc61fc42.nq.gz
    ├── 216ca277c751f61e58762b70908a3f68e0cc2dfc.nq.gz
    ├── 22424f55af0ff70cf5b4c4d8bb0187cb0b9f07f5.nq.gz
    ├── 226abcc4db833cbabfce4a3fff66df631cd0b486.nq.gz
    ├── 22983e910781fc27c923f225cd7ffae9b8b858b4.nq.gz
    ├── 22ca4a3d7653f46d77642f261b0e71b9ea7016a7.nq.gz
    ├── 2347826076e288842a352ea7c9c78456ebf08937.nq.gz
    ├── 23e7b5293af41b0d0990557628e62e44103bf90e.nq.gz
    ├── 23fa506f3ba69ffafea3848bd5b684b7478c5112.nq.gz
    ├── 24230edfaee1be0c90237a653c16316ddec103e5.nq.gz
    ├── 2435001d87afad2c464a859b03e4fa1db3e4138b.nq.gz
    ├── 24db02ea2582db19846b386f662dd284b7bd17ca.nq.gz
    ├── 253068032b2815a1b26a5db92be52d6a2aaae482.nq.gz
    ├── 253e2cda766a3ad630254ae6db427836a0a7e6ad.nq.gz
    ├── 25613ffcb6ba81a36e73553038d19019f9cc50e1.nq.gz
    ├── 2566bc68a53d7c4158a5492515861bb418a607ca.nq.gz
    ├── 2637d64423d4169e2e0da9a4a2b203f75ad51319.nq.gz
    ├── 266f0da89eb7dae6a3efe84f5e1892eb65d6a28c.nq.gz
    ├── 26ef6be8bf02716ed047d796c438b31ce459f315.nq.gz
    ├── 26fbd6e003f4b6b38435a958938045544f78c9d0.nq.gz
    ├── 273a715fc4583a9f7492273985fbb16d60ba69f4.nq.gz
    ├── 277fbf7c712686adeaf3d2417b6a1e035dbfa0ce.nq.gz
    ├── 2a47c81c07f7fbeba8bebd8d740bd9f53a56b7f0.nq.gz
    ├── 2ab57ea0011839f8ab666ed80898f8054b0bbe27.nq.gz
    ├── 2b99cafb931852e965c586ceeee9f127942bc526.nq.gz
    ├── 2bf51d6d3cc49881b57dea0dad2f0343b9413398.nq.gz
    ├── 2c5f8286f5040cf1b69e149d5c8912622187053e.nq.gz
    ├── 2d250fb4f4798b83d7b93cd56ebe44db46d8672f.nq.gz
    ├── 2d2ae6ba3941ecc2a8fce3465fc80e9db92e13c1.nq.gz
    ├── 2e110ff5635a3275f8be92e6eb35bbf90d7c087f.nq.gz
    ├── 2e1beb9e57d58008955fd6570c9d8c8facda3932.nq.gz
    ├── 2e21293f00c496037d25a26c739e90d2beb1bf97.nq.gz
    ├── 2e908403e8a94686fcb0e4bd4070a1e1ef81a66c.nq.gz
    ├── 2ee1ecf8ddb88c1053a8929368fbce008f11cc2a.nq.gz
    ├── 30304c89054dcaf8e603895c655f28dc3a231ee7.nq.gz
    ├── 3081c50f9b58b5b4117d26b844ec7dc1af30d008.nq.gz
    ├── 32264a581cbc4758791b8964f19138e78788ac90.nq.gz
    ├── 324faaacb727a6a06bba68a3d67cbdce4c8be25f.nq.gz
    ├── 32f52d613041014fd5ccacfea854acc3e8c3000d.nq.gz
    ├── 3300e899624d4c1db941df818e81ca31d3111b16.nq.gz
    ├── 33acae850eeb78352e9a1b1319027fede883ccac.nq.gz
    ├── 349f8ad6ec6beb1607a336a455e887b400ceec4b.nq.gz
    ├── 34beaaaf5b78516e0808f6282be57d8800cb1d64.nq.gz
    ├── 34efb6c4870ac24141d418d23792ecf76dce24b7.nq.gz
    ├── 35ac9c69f64c264c1f1e84396ff8bffa17156001.nq.gz
    ├── 360db26246a3dc2a1ba1f993bda6874fc245625c.nq.gz
    ├── 3771bcb179cdd1d16b2ca7ebfc737b53540d3c6d.nq.gz
    ├── 38413be681052779d9ceb3ae6e48ca3b8b739871.nq.gz
    ├── 394030fcf2dfba21ec701412222027f8fae26daf.nq.gz
    ├── 3a43e6a85d0f5479f25e5937ec52359150b2829f.nq.gz
    ├── 3b032b36a1c39705f9c83244973cfd3f55e8633c.nq.gz
    ├── 3b73bc5af8d59ab672e899f1fa7194f89339ce93.nq.gz
    ├── 3bc2ca138b87f6360fd64745c0cf1774675a24fc.nq.gz
    ├── 3db2640fbf9e0783ea8cc602a2275e5124dbfd58.nq.gz
    ├── 3e86e7b7fb227d40958ce0ac47a35165b9c8ac81.nq.gz
    ├── 3eb527a5469090157099e813780e5cf359ee10d7.nq.gz
    ├── 3f9098a466ecb7f4f7acb1ae94e2b42a263f5c53.nq.gz
    ├── 4039e057b96f86718eebcc98f3886e0ff9018d83.nq.gz
    ├── 40cb6d5b16e8ef35f07bf4d4da6783130a5e3f70.nq.gz
    ├── 4144dbc162601b8723aa304bfeeb4070997c852b.nq.gz
    ├── 425e25e29c4eba0221fd6fe836f05552edb6b812.nq.gz
    ├── 4270d8dc02f1ed3945f5ab5ff04ae3041f8edfcc.nq.gz
    ├── 427f26f5534612615544e388c95dc8c6dd5f11cf.nq.gz
    ├── 43e751c7365b4a1e1d39a2105b460ea697691a51.nq.gz
    ├── 454a882725524de8204740299ddfc57ffa1a7ac9.nq.gz
    ├── 45a3a3f54fb760e9780e206d6278ef5a53ee446e.nq.gz
    ├── 45c7193b950d671d46ddc0488c687aebe87d01b3.nq.gz
    ├── 462d853e83c6c6c244ee884959a062cf2bc452c0.nq.gz
    ├── 468ed5d7e3c6711b2bbae935e19fc618e920aba3.nq.gz
    ├── 46b5a76d5faa084f643626d1650b1be10c47d0ea.nq.gz
    ├── 470391b9eb62aaa72ce1a6da6b433fe52d9f6330.nq.gz
    ├── 471c2e817f815b813a52755779fede24160028e6.nq.gz
    ├── 47de256d23d75ace9bb3b6279a5596e57533ac4b.nq.gz
    ├── 4836c040a39b53061d2b74fb7bd747ea0bbd250b.nq.gz
    ├── 484b7661035048f1177af923e5ceda459a5cc475.nq.gz
    ├── 488a204c8915286287bb930f4d5660d67b21bdae.nq.gz
    ├── 4946aa4876dae16675a14b10884af87eedf237a5.nq.gz
    ├── 4962f067514fdc6e7a0ed77fc015d9829cb5066e.nq.gz
    ├── 49c86781ee58fd1c71f68fd9a1916c7724acb085.nq.gz
    ├── 4a2684e3b60406c6f11a9466b2ad42d90310f495.nq.gz
    ├── 4c38b7acd83a9776fc5730df96b657d0a5ca1d6f.nq.gz
    ├── 4cc7d85e4765d5aa3226e9368a124219c5cebc3d.nq.gz
    ├── 4d821f7513986f9497f52db415189514427e2888.nq.gz
    ├── 4de3dd1c12294c5a9ae7186cba1e0f3fa5bcab2b.nq.gz
    ├── 4e4bea2fdedae6cfba4a0e8dba5a78d94e2849fe.nq.gz
    ├── 4ece84b7f867de532751c37809e0ac6d95115a7b.nq.gz
    ├── 4ed019ef28a1c7cfc3f8f35044a3e02675a3a3db.nq.gz
    ├── 4f65fce19855ec7ecd43957a0227037fe3d591f0.nq.gz
    ├── 4fa4f85525bb9a2f6b6e3d9fadc345731c789096.nq.gz
    ├── 51a8ecfaaffb32dc2bd3fe859bd943fe66447e8e.nq.gz
    ├── 5261c9b97787ee7bafaaafbde4e844bca7abaa07.nq.gz
    ├── 529641e7f64202f166d8d1673e2eaf2762a22863.nq.gz
    ├── 5415f36733dcd3dd41aa7de522403a92a3d4c658.nq.gz
    ├── 54bbc99eb7e6ea0830bb82d853ea5b3175f25396.nq.gz
    ├── 550e725cfba2c21190e124b9ad8f79d546f2cff7.nq.gz
    ├── 5673c1faabd3614f4159e95947721ad8993739e8.nq.gz
    ├── 56910f0b1dce0b1eba255c0e1b0592ed97b45fa6.nq.gz
    ├── 572ae26a8c3b8547c2d87e239eefacf4878ad94d.nq.gz
    ├── 5852ca765a9a7d24a1652717ba78bcb306fe3052.nq.gz
    ├── 58cb963f085c1f833f21409ce893c3baa97abf33.nq.gz
    ├── 5a89186d634b241fbdf6101d670b4dc3db2d23f0.nq.gz
    ├── 5aabaa8fb6f9ce15f2daad36b7def51538796bff.nq.gz
    ├── 5b4a0eb1e24f84aa96be5e26a72dc4aac07e3862.nq.gz
    ├── 5b4b1ea0e92fbff0809ac6a1230e56f6b7e499a0.nq.gz
    ├── 5c202a4b7fd5b59686df60afa709696bad31a44c.nq.gz
    ├── 5c5ab85ff5951eda297b2764bd60a3064275a7b2.nq.gz
    ├── 5d4f28ff1cd3096f5d4f437778d3350099da1cf8.nq.gz
    ├── 5f142df4fe4742b4af094be3bd8978c33ffe4d81.nq.gz
    ├── 622a5ec477dc77da55982de38c720f8ce75241eb.nq.gz
    ├── 62e1e6074e6542931c2e561c72291174c2ee556d.nq.gz
    ├── 6302bbdbbc456acbedcc254c0c4ea8961446070e.nq.gz
    ├── 65b50c7c49a92ef71c5c905b79999b15e781c197.nq.gz
    ├── 65b77174c0ddc7e58ecadb3087f047fba7018091.nq.gz
    ├── 66553547fd76c6077164a940939a3ebee1bd259e.nq.gz
    ├── 6791ea2aaf70858eb22f00e2a13cd5199573873f.nq.gz
    ├── 6924b60635906f617f7ff381d5644fc8e47d4d21.nq.gz
    ├── 6964f55e28a1509008342225186071ff16914981.nq.gz
    ├── 69868d9b5fb7a8dfbbe897fa6de48b08ffe1c907.nq.gz
    ├── 6a5c0791e2a072a8d56b00f660f6042f95e67203.nq.gz
    ├── 6c2e5df9f060779103e79b83a27a72658cac7b3d.nq.gz
    ├── 6ce0614ac95a81eefb2934070eddd3ecf261cea6.nq.gz
    ├── 6d85e2cf5023f6403d8105610f9e665baa79023b.nq.gz
    ├── 6efb9dad9fc593dbc2216d0b707c85368272e404.nq.gz
    ├── 6fa2086bd75e7515bec20261591365f66caded33.nq.gz
    ├── 6faf7ab865a6be215317f966542177ceb89c3eda.nq.gz
    ├── 703c44591cb6a8015cd8d106b08bc5d993b3da6f.nq.gz
    ├── 70a6762103c69177ca22c76d61880807a327c44d.nq.gz
    ├── 71779ff71cd39486fdf90903aa3183bbbdcce463.nq.gz
    ├── 71f614f5a00c1ed739a31b6ab5ea0766d25c90ee.nq.gz
    ├── 72337f79e59ff33d2df5f729b33a2c2aa84e0844.nq.gz
    ├── 72e647bf93a7ad94d2777f74dece12e7745ba333.nq.gz
    ├── 7357545ce1a3cc753da2f425e9264cf971b02f94.nq.gz
    ├── 738911a6f49b3c8c752cea5e190a157b825649f4.nq.gz
    ├── 749708720c98a57efe97fdecafe47f12de5811aa.nq.gz
    ├── 74dad497ac3c802c51f0c924475f32c76d06ba7f.nq.gz
    ├── 7585f20d6d2889ff32b4a4f33b1e30c000c51aac.nq.gz
    ├── 75a6a35e9058d88ba03456b5ecc49ddb0e29e2f5.nq.gz
    ├── 766a5d0d18a82ff8466a495fa6538c14aa50f8d3.nq.gz
    ├── 7745aeacb96e027fd629eb4064b309b3b0b9a2ca.nq.gz
    └── 77d63d83b9c5c979c9d6a26bbc7ade207a641d84.nq.gz

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

[allenai/agentic_robotics](https://github.com/allenai/agentic_robotics)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
