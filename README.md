# Repolex Knowledge Graph of jazzband/django-two-factor-auth

RDF knowledge graph data for [jazzband/django-two-factor-auth](https://github.com/jazzband/django-two-factor-auth), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-two-factor-auth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a718bc7b822fb36587b2e1d2fb96bf065cca842b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a718bc7b822fb36587b2e1d2fb96bf065cca842b
│           └── chunk-001.nq.gz
└── blob
    ├── 013d2206752c9c9940e630fd0a8dd5c101910617.nq.gz
    ├── 01b4ae092f0e42f85be18adb94807ca9d7acfb23.nq.gz
    ├── 01e94c9358b17f2b7a792b33388b0992bd3bf3f0.nq.gz
    ├── 03b240b6273280633a1b587c6d0e45588efeb26a.nq.gz
    ├── 040ee56d719105f1e830d7acbf434635483891c8.nq.gz
    ├── 045a5b80c1b9f52f8610f2bc1195776ad540b187.nq.gz
    ├── 05e87005435de407ad5355766f5ebbce6d7b68e1.nq.gz
    ├── 05f60954d67ef948793ae22de16130af2537de1a.nq.gz
    ├── 0605edfe08b0cd28b07334a254fbd103924e943b.nq.gz
    ├── 06d7014b6caa624af1cd86dcc4827a572f14587f.nq.gz
    ├── 06f12715fbd174f297d810c824e864f2a2eba2fa.nq.gz
    ├── 0a4aed6740f142ee5caa1c507edcfb15e22b1c58.nq.gz
    ├── 0c24691654bbaf94b2c67c672d6f39333ebdb871.nq.gz
    ├── 0ccd9e2d4621486fffa08478dc3fe9a145c91cce.nq.gz
    ├── 0e6521aa79c7c604a5be522c01b54313ad1205cb.nq.gz
    ├── 0e8fcfa1f7bf1a96bde4de22a3bfc87bb5387427.nq.gz
    ├── 121340cf24139fef3c3b571af29d3840c24cc22b.nq.gz
    ├── 122305253eb0bd38ddba9cc19ab29bbc4f0cecab.nq.gz
    ├── 12bea11339a41fc5bbf82ab7695e814fba60d331.nq.gz
    ├── 12e70969b5b14c144549150e2ef67ca29ab9dd8f.nq.gz
    ├── 147015a7f24983e8afd035e66993a5b9cfec4e8b.nq.gz
    ├── 14bcf8b3e679681aec2060ec495d95165eeaf5d4.nq.gz
    ├── 15d78e93b3d2ac769fdb0bd6d417e7abb7a8da18.nq.gz
    ├── 16e89fd2257d0ae591dc9b531c21da56edd5636b.nq.gz
    ├── 17ed5fa68e1343a5b568bce5006c3d3c0e948708.nq.gz
    ├── 1863a2b949e28d123dcccbee7634d182b0788e74.nq.gz
    ├── 1977ea5e4dbfc39f2355b6f3955f1822801ea788.nq.gz
    ├── 19c37b9a07bc47d0456f9272337a45f5151ac5c9.nq.gz
    ├── 1c6ea03bbedb0e86332f494f734e98e8c8d0df3a.nq.gz
    ├── 1c9f3c6154060b111b11cc250f190493e129332a.nq.gz
    ├── 1cc2a5f704dd21a14ff2ceeb904dc30d92c0e8e7.nq.gz
    ├── 1d4caed81d7fc59a89adaaef84768b103ac51748.nq.gz
    ├── 214786fad0228e065abb3bb25d4b776ff79d3439.nq.gz
    ├── 227f504239bde8157c5cc70e121835fc9aeefca8.nq.gz
    ├── 24227d47b216f8ad3d4692087cc0b27c034ffdbb.nq.gz
    ├── 2551233aaaaf0a6d0e4df620234664f1e1bd5124.nq.gz
    ├── 25ce39551da846cafb908f981f14226cbc505cd7.nq.gz
    ├── 283233b1ffa876cbb5ce82a32158159b62bdcc7f.nq.gz
    ├── 28e99d068c186763f8617f66bedc287b15fb1188.nq.gz
    ├── 2a20c3f86b92bd97ffacc650a5c4ce3b311ec72b.nq.gz
    ├── 2bf5704f7d3b527b2b18dbb5a8f4adae837d67a9.nq.gz
    ├── 2c015bf217be51d87940decd1e990097c6fda99d.nq.gz
    ├── 2c5b2a8e042d8529ae759527d6ee534deedaf5fa.nq.gz
    ├── 2d603429f94141f921f89fa0cd4e9409c5f9b762.nq.gz
    ├── 2dd62ed44d2ba2557eb3aa793978d24813e58397.nq.gz
    ├── 2df54d0a618671ff0b217741f67b690c561b8e97.nq.gz
    ├── 2e9fb2a86cb278b492adb3e95cea082572e4810f.nq.gz
    ├── 2ef8bca28a02e97fb4ed7654b5dedc1f3f93a4c2.nq.gz
    ├── 30b91e48e90d2d27c3b8b01d0c0b08817d9fe412.nq.gz
    ├── 30e631c0e0b87368af6d07d7b775f8dfc9704a7d.nq.gz
    ├── 32210cb68790fe6da855dd3a0c4bee3637ae4824.nq.gz
    ├── 33dc61bfd8f04b222e59f916af39bfdfc28f75aa.nq.gz
    ├── 371999e294dc1bf85510a7a8586b640bf175ebb7.nq.gz
    ├── 37dfad9e8cfdecb5e57cb58da1451933196322ed.nq.gz
    ├── 3af5bc26f8f1ff74aa251cfe0d82a3098cc7961c.nq.gz
    ├── 3affd74d954ce292357f98c83707f35ffa0818c2.nq.gz
    ├── 3c03e997f96875f4fcdd86f39ab3d7c81347adca.nq.gz
    ├── 3cdcac2e60900a0edef40f0cd10c7b8b3db3ab13.nq.gz
    ├── 3cfdb7654a8abe7b58e4ec496e7531632f7c41ad.nq.gz
    ├── 3d38e953e01ac59cf838a85f87021b4135cd69c2.nq.gz
    ├── 3dce07204ab68402cd0cbbbf46e52388c2646bc7.nq.gz
    ├── 3ee2c19886a8ca56479ef714e71ee6c343881da9.nq.gz
    ├── 4054d18fe791f22069064d2a778d641c573194eb.nq.gz
    ├── 422f5382c2ae9290c44600a2a19746c5ba606b01.nq.gz
    ├── 43b57601752c4414350f0155747e5a9d8e02eea6.nq.gz
    ├── 44c452d3d55d2c97e589687d94d46f662d8a3cf3.nq.gz
    ├── 45af82641146ba59dd2cdcd6ba6f2bb6bdabe65a.nq.gz
    ├── 461d6193e5ee51b2fd6aec54d3b6dd7fcb391ff2.nq.gz
    ├── 46caf7a1c906c0a5391427ab82e3b461789b0841.nq.gz
    ├── 4894e04940c4c5e242718af620abf424b1f93e5c.nq.gz
    ├── 48ae8d75c899ea567a34c69e20ee878065c31782.nq.gz
    ├── 48d7eb5953a9ade319b60a11c1c3f9cd5757d4ae.nq.gz
    ├── 497fe371b78d5e274f3054057eb20655155462e1.nq.gz
    ├── 4aad51885267332ecca42a8c40b2125071003990.nq.gz
    ├── 4c053d6c9bedbfe3d89be6c1b29ed1c193cdb159.nq.gz
    ├── 4d90742af95963b9a2179c9a5de26222ea54c4ea.nq.gz
    ├── 4eb4f786d300d93d44108525a656a01f98131e7d.nq.gz
    ├── 4f8b929de1e73aa3576ba87985f258453128d173.nq.gz
    ├── 4fb2b9bc06a2d8ae1430d0ebb45059ea59508474.nq.gz
    ├── 4fd3ee23b73306da3d0a3a9a2036eca607c44883.nq.gz
    ├── 4fe4a839303dffbc89af4d71b5fef9f2d949d8e7.nq.gz
    ├── 510dc60222ed29c747fec677b2adeeb66b84a5d4.nq.gz
    ├── 51465c15279b1af1e9fb514959a150b04d40e5fb.nq.gz
    ├── 5242638fde4612180468338b288b19fe8099408b.nq.gz
    ├── 529ba97c7773c4bf0e7b3dd6a3ab792729ca0fa0.nq.gz
    ├── 53126e5f3ef70bdd0c684d1cf5230eae2916ae3e.nq.gz
    ├── 53214429c53fbd7ef8cf9c5e61eed94471fb2d87.nq.gz
    ├── 55081e3a57fbe3f09581667d2ca28f2622de3756.nq.gz
    ├── 55d87798c013c77d15f2cb6fba1323324802cca7.nq.gz
    ├── 5845bc9e0c6fd601bfce92ea581ff9f700078ae8.nq.gz
    ├── 59527213e8062f2a6d3691b9631623330d6f9981.nq.gz
    ├── 5a1ddd363a55de724cbe4950c3b55ef7897c7a6a.nq.gz
    ├── 5a66e103051ceef2093870a3b03159d9c48cba8a.nq.gz
    ├── 5ab6b915aa3c1835bc73861bae640fb94d16a686.nq.gz
    ├── 5ca254a198b540bd23ebc12e92c957f97d5346a4.nq.gz
    ├── 5ddc94a68ff4ba63e531272ba21fb68e419623c4.nq.gz
    ├── 5e49eb5cb400be85fc7df3060fe62f7d800316ba.nq.gz
    ├── 5e580a4fa1f94582987837becc7f52632f51e16d.nq.gz
    ├── 5e95b4580acd0093afe01ddfdb17c733e326ec46.nq.gz
    ├── 5f17b9cbcb1a53485beb0737ffaf9c9b10ee0f9e.nq.gz
    ├── 5fcf3cedcd19b51bf0d9b7d671e8516f541bd2ae.nq.gz
    ├── 616addcf0778dbf6e51b1d111d490043d58217b1.nq.gz
    ├── 620d2524abbaa5ca6ae23b7f6c454bcabd87ebbb.nq.gz
    ├── 622b7190d0fe85c9a89ba291bb818ccdf894953a.nq.gz
    ├── 6232ea83e43651d6aad26ebb852da200eb1fc63c.nq.gz
    ├── 6258b04dd7189e1d8d6d707ebb7b9067f1b87bb5.nq.gz
    ├── 6299d767d3e49b4e716e1fd8e787c0d15f7c84ce.nq.gz
    ├── 635551e0fec200cbd3d35ce79eb682e26c21b6f2.nq.gz
    ├── 64a073faa90f847be72cc110a6bd54abe3957406.nq.gz
    ├── 657fe93fd7c4de5247465f3ea6593250f61bab29.nq.gz
    ├── 6592725d98d41a275a5466aeca1ddecc3968632e.nq.gz
    ├── 66b69bc61919b38c4e2b0b07d746999d49e706a4.nq.gz
    ├── 68a413b40c746d893d2c234aa687e0fb0a66d4ac.nq.gz
    ├── 68c3054dc9ba3aa9cc90b9560e2c761e0e50a480.nq.gz
    ├── 6be3a6abdb6471868b98af2c0fd37d8e42f29128.nq.gz
    ├── 6c43f434925e865a4e96d1d58c31350503485a88.nq.gz
    ├── 6c5e738ecfe6c7f7fe4541225342976399577d24.nq.gz
    ├── 6c84bcfee5930bf2d704817f8ae0fb50ef09db89.nq.gz
    ├── 6cb9cb9966ffb2250c158220cacef6c7b19ac86f.nq.gz
    ├── 6e24331bdbb3e8666c8631824991f525ec915c82.nq.gz
    ├── 6f8fcdff4ea5455284492f0897d38d714f2137bf.nq.gz
    ├── 720b60d6ddc9b172f4f8ba5f9c9b4fbb8834f865.nq.gz
    ├── 740266e53b3ae043f907f2f5fa1c5e93c98842c7.nq.gz
    ├── 74b963f9178964ac9077a3019fda24e2c35b872b.nq.gz
    ├── 752d013d289d2bdcaf634f12b2b22e1493f97f78.nq.gz
    ├── 75bbbb66e57833c42e9b07884325de6e51c364ce.nq.gz
    ├── 768616d032c990817fdbf335d5c62e25edb2b70f.nq.gz
    ├── 76872690602e59b99c004131cbb868d6ed0f5e87.nq.gz
    ├── 7756bba7e7a3977903b98772de98a07ca5a2c57d.nq.gz
    ├── 77580b85e3bc6ce07f327dfbb44287b6a6e6d6b9.nq.gz
    ├── 7784d53a095b08d01e2a590f8a49000fa031488c.nq.gz
    ├── 7859c7f216b67e4c24978946b7a44ff5fa875cdf.nq.gz
    ├── 7957832f67bed3644a258319b21635a8467e3152.nq.gz
    ├── 7afadb3fc9915feb91aed869d1855452acd91bea.nq.gz
    ├── 7b9f358ead1e0c8a776be268522b1c4bbabb1265.nq.gz
    ├── 7c76b1203b9a1d51d9798fefd2f6b7a98103c102.nq.gz
    ├── 7f1ee11f43cedd79a3bf7ca9f4301c54f316e629.nq.gz
    ├── 800fdebd6d20e6af7175f312642d4a88156c7c13.nq.gz
    ├── 80c6d5a45d6545463048963fb549cfcc9d53143d.nq.gz
    ├── 851f2e7137afe4128d67b40d8bca108ca6a07405.nq.gz
    ├── 85a36192bd75f45eff687c32e08f45eddb70a98c.nq.gz
    ├── 86813f4da2b438dddf13a3b0a2fc0f4bdc4f0932.nq.gz
    ├── 878add21d6053bf3da07cded8d129423ed4ea4ac.nq.gz
    ├── 878b9f79b3e0af1ac992913bceaed2978fd63337.nq.gz
    ├── 888851949b6a5814cd12ff95499b265b158556db.nq.gz
    ├── 8a1371c6f81ac40e5f953d10c35816a97f440fe8.nq.gz
    ├── 8a86372d596d66d65cd4f3fc62017c1e2230a2cd.nq.gz
    ├── 8ad8f15e0a8abeafe7accf3e44914ec925006da4.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b182fb0fb1befd01a23cefcf4cbe114d03ff9f7.nq.gz
    ├── 8b41d1ae40c1ceb017cf240ad3fe1c4dcb7a74e3.nq.gz
    ├── 8c0bd4ae2bc86369dabc8f0fb3da5005ff5a496a.nq.gz
    ├── 8e7531f0910563dd6fb272c5653ef7fb46d32566.nq.gz
    ├── 8f87a4b6990812634c107d37dea9f10c66aff106.nq.gz
    ├── 910b9b32f24836c902c942030b9b81cdd77c9131.nq.gz
    ├── 9162f94519436cd5036dd10db4fcebec48631967.nq.gz
    ├── 922c3fdccfba9588ee4138be58720acaf90c5c84.nq.gz
    ├── 92d6c2b7a7e7b2817baa9055212847d6e39942e0.nq.gz
    ├── 92d9bf6300a3bd90cdf1d0fa184af50b9d248b56.nq.gz
    ├── 932222bb084a606c3cde9109b10e9606d0a1fb67.nq.gz
    ├── 93f4dd106b71c7b3f3e2e784beaeb3e27b2fd91e.nq.gz
    ├── 94955b07fb0d99c694f92c93d5dd5d7a9d27f107.nq.gz
    ├── 94e842f85789f9024d2ab2f72620e8a7b4d97f0d.nq.gz
    ├── 9648715ba0c89b4ff8f9abd36718411b4af00b02.nq.gz
    ├── 9659a15a16e03ce3503f406d32efcd5ef4e48faf.nq.gz
    ├── 971b4f64b4ad55272e3b72481ee82b0ae03b6edb.nq.gz
    ├── 988a9005cacc8d7fe75fc5a6dbd6e45dd2736fb1.nq.gz
    ├── 98edf26688c712368ed2b196cb7c9fb1dd720666.nq.gz
    ├── 997609b8326b49fdfe945a2ad4a4de612b8254e1.nq.gz
    ├── 9a47ea80c5a377cf75478fd0e77c2c21d5537d0d.nq.gz
    ├── 9acd95c58a8a0179d062ed3d40774c9629d90848.nq.gz
    ├── 9b0a3180ec0b3633effa04a82ef71723405cfa09.nq.gz
    ├── 9bb9b6dac681733e826f2649995feb25623a3d7a.nq.gz
    ├── 9c79f23cbd16cb42aadcc6d4938bb15840b59cf1.nq.gz
    ├── 9e2c830d1d3a6c756c15fd8ca0ed559a7c68b2b9.nq.gz
    ├── 9fe4ee325390c66f7a477c2157884cd97ffc1245.nq.gz
    ├── a174d86d84c6c58a2b0b5996d6110ef53ac308c1.nq.gz
    ├── a854ef53eb4f6d43a642e1cc27394c6171d36b41.nq.gz
    ├── a8c9d1c61b05cd8ef1f572470173ab043846a2f1.nq.gz
    ├── a9cdb7971f54357efa3355095771633a8c04d8a7.nq.gz
    ├── aac42c5a57f85a667907d24df4ccdad416d9b96b.nq.gz
    ├── aba2e45b4c15e7fe3d76ea6dc02cfb2543a87981.nq.gz
    ├── adebc60d5281d695a7d7027e0939888ee27d2fa8.nq.gz
    ├── aedbe7c99707b3a84f6a67e0e73cbb84e662affe.nq.gz
    ├── b0884dc622169569a351f01f70d189294414e82c.nq.gz
    ├── b122572e23231b7166dbb6558aa690378d21893c.nq.gz
    ├── b139e0d305ea0c3750d253e5c1b54c05e14a6703.nq.gz
    ├── b1eb757c6dc639afe00d3ad0d2f5881d4c1c2e76.nq.gz
    ├── b2c211810b6f60561d18684b5410f877a2e70e21.nq.gz
    ├── b40fb9e557921c17e61fb6f61b7e9c4bffa4f8a2.nq.gz
    ├── b416b93e1194fc38c862bd61bed07d6bda8b128f.nq.gz
    ├── b528886f49a47706dd382f3274a075a52c8aa46b.nq.gz
    ├── b63823057853df2bdab81eb44870e539fe3307a6.nq.gz
    ├── b756e8e9aa47385df38f1ef1cb52202979507737.nq.gz
    ├── b7964f6b1fefcaa1e7889b0fe9891cd94122713c.nq.gz
    ├── b89492f3b8b846ff2bbbf7bb05d6d80d6c8b5f94.nq.gz
    ├── b8fd6e658b41ed0306d6476cc8c65175b0b8054f.nq.gz
    └── ba4dee6db92d81993e943a7e6809647462363917.nq.gz

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

[jazzband/django-two-factor-auth](https://github.com/jazzband/django-two-factor-auth)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
