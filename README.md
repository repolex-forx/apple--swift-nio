# Repolex Knowledge Graph of apple/swift-nio

RDF knowledge graph data for [apple/swift-nio](https://github.com/apple/swift-nio), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-nio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 558f24a4647193b5a0e2104031b71c55d31ff83a
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 558f24a4647193b5a0e2104031b71c55d31ff83a.nq.gz
│   └── repolex
│       └── 558f24a4647193b5a0e2104031b71c55d31ff83a
│           └── chunk-001.nq.gz
└── blob
    ├── 00457d5e197b21a81ccca344a026b498bab1e6fe.nq.gz
    ├── 00995dc244e7b4fb8edf5502c05828d1200d4e4e.nq.gz
    ├── 0195fd0efc5add655a6946bfb93b1168d72ba65e.nq.gz
    ├── 027e374bdf785b1546f825e326460763f663d826.nq.gz
    ├── 02836053ddd38d1964339d8ce65be91ccf9855e8.nq.gz
    ├── 02aaa15e7ccaeba269fcd18769380504d1db41c1.nq.gz
    ├── 02ee1d77ec9670843b888468dd5cee29372749a3.nq.gz
    ├── 03e0a2c46cc1286554d6f33e95a80fda28dbf400.nq.gz
    ├── 049062106815338d6ddb402c54c289cf4db84b04.nq.gz
    ├── 04fb464e22d8cce8100859e254cb3259c8c7e598.nq.gz
    ├── 050b72b7bf19622a26642ee73611181bc507e308.nq.gz
    ├── 0571266e1d4235d9a2aad58a0f7f7f744e4407d6.nq.gz
    ├── 05a1e508d1b14db3c459ea6e4ed5a2284809738c.nq.gz
    ├── 05daeaffe17161a0f10b62d29090f06113a227df.nq.gz
    ├── 069a450a693b726f773fb28198fa79feadf378d9.nq.gz
    ├── 06ae6deed088c17661d1e3df1f32a56403bd0b09.nq.gz
    ├── 06d9b32e80384e9bf2ae1056b0583e7cca7cab52.nq.gz
    ├── 0738bb163d942be4777c7170eb565e089702529f.nq.gz
    ├── 0809c115f408b9173e52674e88027cfc30ac9b4d.nq.gz
    ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
    ├── 088dddc3d7e27a27f18ca117d952eb433491dcd5.nq.gz
    ├── 09083bab2762342f982b26370197a7fac3adddab.nq.gz
    ├── 0911efa95910e4de2d97906c5a1eb41987fee5e7.nq.gz
    ├── 092702f50fa324ec52576a1e45cbb5811e7e6e1c.nq.gz
    ├── 09b0a720e674a7bd9b50e1597c7b965274b6be9e.nq.gz
    ├── 09e0856acaf9ce2904626f009ad256dab183fa9e.nq.gz
    ├── 0a06cac5a951ceb21cdb771d450c30c99b601060.nq.gz
    ├── 0aa7529671cd033e3a8542fa0d50d6e3e95474d4.nq.gz
    ├── 0ab3aa3e4063f1f5a67846a95b8e9c771805c09e.nq.gz
    ├── 0ab5f5fc7cdb5bde305b04cd21e9604ff4eea4bf.nq.gz
    ├── 0ade53a39a61fdb37c5a682c42098d31b050d7ea.nq.gz
    ├── 0b870fb78b40aef9361d05095c28ed0e1474d0f8.nq.gz
    ├── 0bdff70e541dbfff95c1e383f7b86e2cefd5cddc.nq.gz
    ├── 0c0786d916b713302a3f4e1d478a9de0a6911cb5.nq.gz
    ├── 0d3d76c7e10efde8ef6d2203252cf6ca24da465a.nq.gz
    ├── 0d5cbb02a63d89cd46d7a3c00353b2c807d0780c.nq.gz
    ├── 0d5cfae9bd5db5bd55c9a5dc399dea20bedb2f62.nq.gz
    ├── 0d824fca348bdc54faea8992360251361d10b0e4.nq.gz
    ├── 0dcc101fb860ed051f70b4f27fb9a7d6361eace5.nq.gz
    ├── 0e7987d729f2437ee5e0d52a41fee119195cfa8d.nq.gz
    ├── 0ed61e945db1a9173b8034e572a165c1e4ffdd1d.nq.gz
    ├── 0fa44b111d9d876589dbc1765102ce3d09cf0ffc.nq.gz
    ├── 10684b8154b1e96715f504099085abbeb088580b.nq.gz
    ├── 10bd769c7ca50d8228be5951bd7291813e1cbb37.nq.gz
    ├── 116a03e854f8bd0451440aec154b4e596e1a4f90.nq.gz
    ├── 11803d67cd2f6229a95c2ba87df3affc1e6ccd0f.nq.gz
    ├── 11f0e8b597c02b7cae9ec4c8d9ee2f9b7f609e4b.nq.gz
    ├── 1285b7584901a8c524bfe62ce35802cf62eeee7d.nq.gz
    ├── 130804ada14e4b4b4b7b511cc49fa5a285347047.nq.gz
    ├── 13386af6918f336840e864eb4f39deb5fb35fd91.nq.gz
    ├── 137d3b565a5e4f4acb2e55cd3d706ef9415cbafd.nq.gz
    ├── 14e197510219bb7cc0de338c49804f5929399862.nq.gz
    ├── 154c2d834073f6b19a3cb4da0f8c6b7504727199.nq.gz
    ├── 158d3ed80f7829e5a470a3419ede13c9c1a1ece2.nq.gz
    ├── 15dd42c442d663fadfeb32d76ca0b1b1d751d36a.nq.gz
    ├── 165cc6e491cb16934e3c23e14be2b1885d4a51c0.nq.gz
    ├── 166cda787615d0c26e3cc62bdff5437402828ea0.nq.gz
    ├── 16dafff3b70e86833e3f37b03d0b5dc8631237c0.nq.gz
    ├── 172c225833a703bf44e10f2bab47f3effe55cc8d.nq.gz
    ├── 1786529f26caadad5e0696b9be5f023e4367977d.nq.gz
    ├── 178a8c0df68a801f236ecb44d31478a5dba7082d.nq.gz
    ├── 17a8a55fdba6e3a687c1f6b9b14b02e5a6d22896.nq.gz
    ├── 181f96f34b75ef7a27239ceaa6d66b66d962c482.nq.gz
    ├── 18307c744f066eb5c71de916d47f337fa41e3fb2.nq.gz
    ├── 185ec81c868cf01679699336c193549aa290c595.nq.gz
    ├── 186ae4ad11f500a7194e44c2da2e4c112643b7fb.nq.gz
    ├── 18a33f2a5aa08b217b5d1007a634ee7e6e9550d1.nq.gz
    ├── 18bdd112047c2edb158b54aba96adc7ff3b24ef1.nq.gz
    ├── 18eab20adfeef3b62969edf70305adc20190a1df.nq.gz
    ├── 18f6740f3ede006f846c8c4ca8c4d3e377f35467.nq.gz
    ├── 19387a9fc7af6ba455599b6caf4a5fd4890e1501.nq.gz
    ├── 19fce428110cbb7bcd663c7c036184b56249b320.nq.gz
    ├── 1a6f8f50e89d74dfa5ceecec36aada918eb0f041.nq.gz
    ├── 1b1880b8f0ce92dd8e85330ad33f94ac22aee6fc.nq.gz
    ├── 1b8c4021e61adf633be6df55ae3e649159b579b5.nq.gz
    ├── 1c9b85d60b86e908bbf3f6fc50ae0919a6c1a1f0.nq.gz
    ├── 1ce663bfc4b3323bc4e90361904d23063a1e58ee.nq.gz
    ├── 1d80f8d43f7347ef55e8c9642bdf71374db53af4.nq.gz
    ├── 1e732c7796460fd78f28678e33d4b66a373cf57c.nq.gz
    ├── 1f105545bae7caba39432264a7b393a6e3cf8a21.nq.gz
    ├── 1f7cfe61b63fa4f08c5f871e91c640d52e0d4534.nq.gz
    ├── 1f820b68d47e7eb57dee101c120584784972c83e.nq.gz
    ├── 1f8ece92b29d2a21b5860218581aa80c474eec96.nq.gz
    ├── 1ff4b717cf1023a2a8fdd41a4203d43a724ec3a6.nq.gz
    ├── 1ffd665ee22157ab499b23ae4435309c34909e5c.nq.gz
    ├── 20345324243df01bea7304180777619480f58541.nq.gz
    ├── 211bcc29c7b80b24e6e1e556911f392c80f506cf.nq.gz
    ├── 215970e78b669bcb0f9fdf65947ef5487fe2e342.nq.gz
    ├── 21d0aa38bdad4fdbd17fd28ebc4df54b12f4c593.nq.gz
    ├── 21fa489499d537871c828d39bd2445534b025684.nq.gz
    ├── 22282f1b506752daaff77f7626f68345437d6e52.nq.gz
    ├── 2235af8a619e00c567eefcbf634c863aab7759ed.nq.gz
    ├── 226cb70cdce0f89f003ecbb789c136ac4ad0dab1.nq.gz
    ├── 22cd6601808d844b5b229ae40d4d6d2c4ac20919.nq.gz
    ├── 22d14669eb085a99b866409c1f487ce0394a6682.nq.gz
    ├── 2301f4eaffcbe243209d1e5971a73975a1ce0f19.nq.gz
    ├── 234346b9c0019ac0ae8a10141959ae936aec8586.nq.gz
    ├── 236af6788d898468a29bc09c036e5fa0c576c01e.nq.gz
    ├── 23ffe84e7b9f4959d9a2337571c8ceb3d60764f2.nq.gz
    ├── 24241df35720c2ada2dd68dbe5a6473ff0135a3b.nq.gz
    ├── 249a3e64a294921326c6e06eef0fa387ff532515.nq.gz
    ├── 2517bcdfa8842ca46a96d1d1ac962fbb5e728aef.nq.gz
    ├── 25de6ffc5c5b39f95823d801e69df21d1d55c94e.nq.gz
    ├── 26b6634bb069eb319f5dd69dfda69ee73082e18d.nq.gz
    ├── 26c2e99d11e1cb9bbfae000eaedaa8228a9f9f02.nq.gz
    ├── 26c75b8d1edf8b79e5db927045f14038033f7055.nq.gz
    ├── 26d133b25da9a7a9b5bc2c3fc81659a8796e27bc.nq.gz
    ├── 274be63410ff185d02377ad70e073b414f759cd0.nq.gz
    ├── 2773754c232540b68602b4b1ff44d63212a4414f.nq.gz
    ├── 2816522521821a9047a04124b94f4ec1ea6c14b2.nq.gz
    ├── 28893add0bcd35cdf85fc68adc5a41863b36dcd8.nq.gz
    ├── 28a4feff7b1bf89749a972a418a68cd54001ae54.nq.gz
    ├── 294c22a0c886121ebd34f1b85ef66426e4b8969c.nq.gz
    ├── 2970c65511abf7046222a53a966353222eb4f1fc.nq.gz
    ├── 2a415229ba08bf33257046ffe377b35a3c2f6711.nq.gz
    ├── 2a593f8eb5dfd5e30140180d11247328965f3c61.nq.gz
    ├── 2a73a8f4dfb90d675a7bd999a62b397464884fec.nq.gz
    ├── 2a7f28532c59a542af4a9d3d8007161a0dfc4369.nq.gz
    ├── 2aa2605f9507adfb5a9be0951fc33d1e1394eade.nq.gz
    ├── 2b6736bdffeff4822aa5530ffe6da7ed89ab6ce7.nq.gz
    ├── 2b73a58783491de7ef50b4a0d491f5d3495acc88.nq.gz
    ├── 2c88cdb9bc3fe86807838a9d345b32e17bb8da2f.nq.gz
    ├── 2ce5d07dd22bd9f44368691bf2fee04bfb22a37a.nq.gz
    ├── 2dd380e2f49b8362345969f55c1f32b6a2d07890.nq.gz
    ├── 2ddcddbce9c9ce2b204dd9d8e15d9fb78a0ab59d.nq.gz
    ├── 2def03562a94cbaf377769f843157cbd5cda424b.nq.gz
    ├── 2df6905a49ac261e14a02765fe8932c9a6faf9a5.nq.gz
    ├── 2e18e01ae4c9a27c7ecb53e253c0a48375650992.nq.gz
    ├── 2e190fcadfb88addbf5c12bd7905c61fd0deb0bd.nq.gz
    ├── 2e2ea1fd746b18ab750d23518eaa5328a4af980b.nq.gz
    ├── 2e48e7c7983f1860f839cd6bd541a86ed7ba708c.nq.gz
    ├── 2efb1e68e723653a499728b70e1b47a02dc4b4a5.nq.gz
    ├── 2f2aeda78d14035dcf25041221b6520271b8a2d0.nq.gz
    ├── 2f458b84bea1b4f833012936b6efebde4e2c4159.nq.gz
    ├── 2f9a135fc2cc31b4320b6930d34e51977da6e6b9.nq.gz
    ├── 300eaa3f8d87119b71ae3768b1e58c6f9fb92d1e.nq.gz
    ├── 3020a04d6f3c9fc7002fd4fc752d89a18e814be7.nq.gz
    ├── 305d452a4933a4a96c4f5dbe1e618a073d478e14.nq.gz
    ├── 30af0df7cf46d7bca76ce0ac62478726166fc936.nq.gz
    ├── 30b81bcb67912bb0df778ccd470ab51ec3c8817d.nq.gz
    ├── 30f5fdf37c50954399f60cad0f9b6de20b914e31.nq.gz
    ├── 31d89e7a227ce64514fe346d4a82421c175f0958.nq.gz
    ├── 3229728ceb179d3d5accbc330122411e8b0269a6.nq.gz
    ├── 3283e3d88d94885c6bb557e83250d37296629c21.nq.gz
    ├── 32a1996b439dbb36ef5d575b273e2fe573e7bac5.nq.gz
    ├── 32d2c704ecba6a0eec489fe4d55a94da687c5d3a.nq.gz
    ├── 32f2b1ab87c18828d23395855e464dbf95af5a48.nq.gz
    ├── 33218203712cb3a9d9c299900f82a78486ccd47a.nq.gz
    ├── 334d576e0182fa75dbbd943cb735772ec718eae6.nq.gz
    ├── 33e9954239214a5fd17bba0d47f7cd40be28ab22.nq.gz
    ├── 341bfdf6c773e0be0c4eb162f1f95179002b0674.nq.gz
    ├── 3443edef1932794086865f3bc72183d2b15f79e7.nq.gz
    ├── 346a64a8591b5df612dc2ce83d67e53c09346b55.nq.gz
    ├── 3487fcff02bd67a7155c3970784bd5812102026b.nq.gz
    ├── 34b193681bb923d38a03fd637f6b7ca15ad847a1.nq.gz
    ├── 34cee4ce568fa1de3e255b75500497c38dfbb375.nq.gz
    ├── 353fee23434d8dccf6678a682b8dfd345e85d1b2.nq.gz
    ├── 358332945bfce97e7bc2a44975f348afb24cc26b.nq.gz
    ├── 36336a1dd1eee63f9f060b1b84fe77b32db93dae.nq.gz
    ├── 370ac91b996ec2cd8cb063c55c3e8aa07c9a59bb.nq.gz
    ├── 371264a839c5dea3ac9200c3b86dc40272c6d426.nq.gz
    ├── 38267dc74404b7fcd30482efa56a98bcaa6551ea.nq.gz
    ├── 3845c4f9780722a6dc011fa4a49d75a1611327a1.nq.gz
    ├── 388623242e4a9a56cf17d213d51e6ee9546d20e0.nq.gz
    ├── 390f26a094396241d455f4855bafc26e68dddb0e.nq.gz
    ├── 399df6b9ca888e44fb74064d90671072fea84850.nq.gz
    ├── 39b7e5d608afffec04dacf8e583473a6cfc0c17e.nq.gz
    ├── 3a3d2e1b57898f28c379e6debad45e7d214c0786.nq.gz
    ├── 3a51b3a99b01c6f59839e082d5d2d5891317cb22.nq.gz
    ├── 3aa49362e26aef06086a57ae5ab95c855c79eb46.nq.gz
    ├── 3abf012360c222e62a64f3a558d1bd96d9e3ad33.nq.gz
    ├── 3b54ba80162672bc0300c927b40d3e5b46321d89.nq.gz
    ├── 3c4a5a8840a128bf8dceaf579385d3c149c0563a.nq.gz
    ├── 3c6b2b52f95589bed450728a4e30daa2d2afffd1.nq.gz
    ├── 3caee659fa45bea252d637e738fdedd1a7f836a2.nq.gz
    ├── 3cdb7a36b7393e089e0137caf817a9061aaee9ca.nq.gz
    ├── 3cefa81064abe88713d0748db00d76c53e771418.nq.gz
    ├── 3d9c9f2cd5a2285356957e96628932f52f64423f.nq.gz
    ├── 3ddd1cff186f8529e39f57783fb699a6857d9618.nq.gz
    ├── 3e61316581ec728d04c95783105cc618bf573841.nq.gz
    ├── 3e8bf65af8a2e9fdabefa0dc0111d26d79a2c032.nq.gz
    ├── 3f60cc5e8ae197185105da85fb865e3209a711b8.nq.gz
    ├── 3fc4954085b90810f9c617bca2a7077529149cf0.nq.gz
    ├── 3fd2ee4cfd80563c07fd71cbb97468c9e11564bd.nq.gz
    ├── 40bb9c45d329e263f650017088933ad288715ead.nq.gz
    ├── 40c9721d4436e3b8b7887e12d368125ad6de5ae9.nq.gz
    ├── 411777da576f12e63afd09e76e60a34d31f8c418.nq.gz
    ├── 414dec74f93dee0b289e4710365f62525ea4d220.nq.gz
    ├── 414e3e220e490226e3b9ae08ec1880c6ee1a192c.nq.gz
    ├── 41598802dc48e49f37e6ed0c6a34c831cae4593c.nq.gz
    ├── 42061c01a1c70097d1e4579f29a5adf40abdec95.nq.gz
    ├── 426125cb8466bc169c98f7c54bece903b510ead1.nq.gz
    ├── 42ba745d2cc2012b4ed7da3548b5dca816f0fa81.nq.gz
    ├── 42e8e5731ebfdd4e0e4368de648fc0b29f91b006.nq.gz
    ├── 438811e89fa897a184e882c95ecdffbbe05ed58a.nq.gz
    └── 44490255d0a56ccdc39b3ff369ddbebaf119cafb.nq.gz

8 directories, 200 files
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

[apple/swift-nio](https://github.com/apple/swift-nio)

---
*Parsed on 2026-04-20 by [repolex](https://repolex.ai)*
