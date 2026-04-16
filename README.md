# Repolex Knowledge Graph of anthropics/anthropic-sdk-php

RDF knowledge graph data for [anthropics/anthropic-sdk-php](https://github.com/anthropics/anthropic-sdk-php), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/anthropic-sdk-php
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 723229c47833e6d180ce43b8b8af7d56cba26ea7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 723229c47833e6d180ce43b8b8af7d56cba26ea7.nq.gz
│   └── repolex
│       └── 723229c47833e6d180ce43b8b8af7d56cba26ea7
│           └── chunk-001.nq.gz
└── blob
    ├── 0010226edc3351bee9f75f219c8499363fd2f4c3.nq.gz
    ├── 007fb20e70580057a653b8a973a916c6b5bc1030.nq.gz
    ├── 00cc04d882aa46dbaa8cf71cf47f29e2c6adbe36.nq.gz
    ├── 010fef2f677bc92d9eba4fb5a2602280e1ea6978.nq.gz
    ├── 02106e4f9f0c7a040487e6683566403000c6b7a1.nq.gz
    ├── 026d8ff0dac9e9ab8388cdf4935c13da8569fc5a.nq.gz
    ├── 02c5e7e2b8440df09fa975c6e9e34a1182bb0028.nq.gz
    ├── 02ccda59159f2181a022d957fef6dc4e7440342d.nq.gz
    ├── 03250b1bb310c2ae473228cce5ddb7127200ff72.nq.gz
    ├── 0338a0b681d203073adb34a9c2e2afddd99af65f.nq.gz
    ├── 03eea431908843a6a1bad7f6bc8cb5097729a88e.nq.gz
    ├── 043ad85a7e3d1eb471c90cdfc52dec55fad63125.nq.gz
    ├── 044811f9732b6320cbb5fc47290edef6e968f23c.nq.gz
    ├── 044dede666ea41225df47f17385ad3287b9fc3fe.nq.gz
    ├── 04a98be615e2b6a38c9b9ac4b25b7063f44a7902.nq.gz
    ├── 04f6674515eb58d6f8572a1f91e38b2056a957aa.nq.gz
    ├── 0514165c9cbb3427554d94a58c2d2107087f8498.nq.gz
    ├── 0562594bf05eedde60867c1f2005df5876d30301.nq.gz
    ├── 06136c9e3a05af7f31df1adc6cf6648224103bf2.nq.gz
    ├── 06b9878b1375caabf75fca60f1e361805abefbd4.nq.gz
    ├── 0707e682ccc6a9dfc4059ef04ffce0eb03755876.nq.gz
    ├── 078537c5bbd01be3ed03a9633f231e71e69336f4.nq.gz
    ├── 07a0502afbf4534829a6f1a42cf3d1b5b05d244a.nq.gz
    ├── 07baf015e424656ef2a8100d14f6b8a9b5112ae0.nq.gz
    ├── 0810f1e389e21a0a52ab5a1cfde351ca947a16aa.nq.gz
    ├── 0862df730248d67d634e86f347eef82829dbd0ef.nq.gz
    ├── 08d131ab2a1670ae18e2ff3bd1ddb8772f7ad94a.nq.gz
    ├── 09135f5e57ebb9c90a6743e2dca09582678d765c.nq.gz
    ├── 094b0ae0078c10828593909ac07ec7e02fe9bc4b.nq.gz
    ├── 09c4fe44c9a9db1ca49df2aedde856a808690a0e.nq.gz
    ├── 0a50c0448c9579bce3236eee043ab5eee83ced53.nq.gz
    ├── 0b305b2be558594c6a885a060ed153e42f3e354e.nq.gz
    ├── 0b3ae6872489ebca5fd0479f91b317d2669b931a.nq.gz
    ├── 0bbd53b62481a20c6291562a36fe97bb71ec0ad5.nq.gz
    ├── 0bbee298c14d16ddacbdbbce70a4f01108ee2f90.nq.gz
    ├── 0c4fd7113ab05501de1a31b812ce8b64d7964968.nq.gz
    ├── 0c68ea2a3c2518f1d1e22e0a7c8d879d8e2330b9.nq.gz
    ├── 0c6eef498611a163a6f2cd0ae5548fc45546fb84.nq.gz
    ├── 0c78034339230ad6aa267de72f5a40ebd47bc1d8.nq.gz
    ├── 0ca6480a259effbd72ea9b433e6eb49ca031474b.nq.gz
    ├── 0ca8cdda9c56f5e02b4600f00e987bccb496ee62.nq.gz
    ├── 0cf7cf27fbbf0d3e4ae4ebb0704e5409271195a6.nq.gz
    ├── 0d288657837c4c9a81cca3c0828db6086e214731.nq.gz
    ├── 0d9c55da7e5683bdb255e595f8898ea04da7c985.nq.gz
    ├── 0dbc83defa68f2406f8219ac3d6b2d472949a7c6.nq.gz
    ├── 0dfc9349ac5385a68d9d870dc4c4a59354897b15.nq.gz
    ├── 0e21b8b93c636da06bf2a9984add74409ddb871d.nq.gz
    ├── 0e36b9d4905b8674a4b1810ab28c6e0b1262b5bf.nq.gz
    ├── 0e3cc908723596f36c625f9ffd45a41534129729.nq.gz
    ├── 0e6302200a1c870b87aaebdedbdaa26e57533f35.nq.gz
    ├── 0e66cf16229c567f75fc6956ac904d45af422796.nq.gz
    ├── 0e85fbc7c005d617026a45138b37fdfcb3797b54.nq.gz
    ├── 0f11e1824549c5df39010214e0f54a8c3012cde2.nq.gz
    ├── 0f2d681e3a322b2fe2945c5a43474246f4d0e637.nq.gz
    ├── 0f617dba754659f2aa589dd68f6ac0837dc484ec.nq.gz
    ├── 0f7e16b75c9abb81607fca5b0fba50dde8fb49c6.nq.gz
    ├── 0f9ea925995b2850f8913668cb5671385f1f6bd9.nq.gz
    ├── 0fc020f4db8718f1fad2f245ce947b4aa8800e23.nq.gz
    ├── 0fefc1f6d9b14157b41603886e91bfeefda2a2b9.nq.gz
    ├── 100a0d1a4d12173f3ab6cf9ed1eaa285af2c7fd3.nq.gz
    ├── 10288b78544e7be60b884a6accae0384569693b6.nq.gz
    ├── 103f32eb1e259a26c2f9b4588c47b69633e5be8c.nq.gz
    ├── 10647dd41a7a628c8863ac25603f012c7fb886e6.nq.gz
    ├── 1065437f57c055d0dd9e21458a31bf572d2fa97a.nq.gz
    ├── 10b79daebdd8f700924f36ff045c63f52855ff93.nq.gz
    ├── 10daa5146efa3f3ad515b3ad95ea01783bd3e0ad.nq.gz
    ├── 10e5d0782c0b8527936d41b7b26bcea152d6f570.nq.gz
    ├── 114b7edcfb53385aa4ecc494aa4df0b982269959.nq.gz
    ├── 1166892102c05230779ccdca73603465bd5dbeef.nq.gz
    ├── 11d461300386a6bdf28eab0b22c03a7a1cbe072a.nq.gz
    ├── 11eb74868357d6f29a46e93b2d99b0cc22e8b29c.nq.gz
    ├── 1227adaa47421898f8038667ade1c0563002ac49.nq.gz
    ├── 1268da4f7608701fc2ac15e6868d72e6762bf713.nq.gz
    ├── 126e212f8c2a92fd01a3b81a2b3ea15f30bfcbe3.nq.gz
    ├── 1330aa9cb8ab4c37da1691e586b4e719dec1e4f6.nq.gz
    ├── 1374558bfe832982e7dee750a191400d3cbd8cf4.nq.gz
    ├── 138bde93070fda6d698e71107e2433d70c0bfe80.nq.gz
    ├── 13e0b1e956d6d2d91d212caa3f2c7f9c54b1a7ea.nq.gz
    ├── 14a808fece49c92518ce184a3f2054b972766521.nq.gz
    ├── 14b5cb4870003a714caf254699475d628b57f410.nq.gz
    ├── 14ca1763b79fc5a4f0ba7af5237851226bda57bc.nq.gz
    ├── 14ca8288c6ba54332155f702831cd8efa0d782e6.nq.gz
    ├── 14ef697ed109e44bb4021d465e51227810c6b6d6.nq.gz
    ├── 15021f42bee84ee269182004533546175290101b.nq.gz
    ├── 154316ab43170b24d1fc10dd3f2cd0092253f66d.nq.gz
    ├── 154c91c83393f5053ed18a8373b2a9f3ad02f835.nq.gz
    ├── 15a215e876496942a56c193deada46a13f1c75c3.nq.gz
    ├── 15b66074fac924100ca68d463f9edb74e356218a.nq.gz
    ├── 15e2e0657bdc08af6d1c973cf52ff0fa6f21cd4c.nq.gz
    ├── 15ebfde9d3b8ad5fd0f8ecf2cafc79f20597e23b.nq.gz
    ├── 15f05d81d145577d7bc3b854c4231e086d27647a.nq.gz
    ├── 15ffc37ee9fbebbc9e0f4d75860dd381b631d5ff.nq.gz
    ├── 162bb3aba19b5d81899c5cf68b7f20de648c70a1.nq.gz
    ├── 16364d142b032ee8221f800575ff7a671c55ded2.nq.gz
    ├── 163d0250f567b21b4a5be79fc61a06a6cb5ac0ec.nq.gz
    ├── 1719536e242673d483e6b6de52556d056bb01e01.nq.gz
    ├── 1733bb2e33f8aad705ed92bc2c788c0d640e4149.nq.gz
    ├── 1761067e31d9043c2bdabc7aa9412a1d47068b8c.nq.gz
    ├── 17ab60419ba8663d7a34f4d75a6d8d529f956ced.nq.gz
    ├── 17b914cc5bccf7d8be1de6f983caffb74f5086bb.nq.gz
    ├── 17f9b7ff996699169e65231f798bc5d1e9cfbb31.nq.gz
    ├── 1854588216bd9287e161f95e7dfd208e86b6b529.nq.gz
    ├── 18fef626c62b4e5fe713aa1e836dce182bdb6763.nq.gz
    ├── 192de5534d61857b555fcc6968eb0c2d30e37ef0.nq.gz
    ├── 1975e6a6a5ebbea633604fbbaac284797622f8ec.nq.gz
    ├── 197cf2cfbc3f844c6a66462a473a6d78d0ad76d1.nq.gz
    ├── 19986d7e3c6975ab519cb20812394cafd9fc730d.nq.gz
    ├── 19b9126fabde0b7b5694fcd938e6307225d0332a.nq.gz
    ├── 19e5f8d5a12c3278883b346c4760ebdfea5a84d6.nq.gz
    ├── 19fd828c493aba809d7381fd5c65784128bb5411.nq.gz
    ├── 1a161361e654a2e1c30300e051049a4f9ca807e4.nq.gz
    ├── 1a27d78af31a5f84fb68260dab110f62c30a9874.nq.gz
    ├── 1a5cf9644810c4fc1405bf13e47b03245194e042.nq.gz
    ├── 1a5f32daee42c89b226228fc8372763ac7450cb6.nq.gz
    ├── 1a8c4b3388371a75a3c3be47a567fe6e8f690f4c.nq.gz
    ├── 1ab3bc55063c382690c08f0e4324be9a3712de26.nq.gz
    ├── 1ac349a3fc19f2b35ea8e810fddfe64801ed2b25.nq.gz
    ├── 1acadc783ba1620ddd3cd349c407ab053cc8787d.nq.gz
    ├── 1aea254e9e740ad7c53c644726ff88221096593b.nq.gz
    ├── 1b119f10fdeb9d773708297dc0aabaff98f49c12.nq.gz
    ├── 1b14973734dca9487b858bd4e309a2eb6880bcbb.nq.gz
    ├── 1b7552b96f1f500cf5f67a3eccf4bef9fe6980f2.nq.gz
    ├── 1b8b302fef9deb617cce176ca70ca0d2a37b4d57.nq.gz
    ├── 1bd621a1a5abf575ef2d5cf789d362d06015589d.nq.gz
    ├── 1bd82d42783e27ed54af44899d5af1e007d91479.nq.gz
    ├── 1c9cf4c8355dd8c6c9256e536b8883ec2ef7bd2e.nq.gz
    ├── 1cd5a9c19604d2bf2c60462d0f3d31482639653b.nq.gz
    ├── 1d601a8832c348bcbf7401734c0c7c2fe2578d86.nq.gz
    ├── 1dd1ce8add60ba9280f36eeaf6dab9bd44fa1dec.nq.gz
    ├── 1e535e1b07687ba3480aa75f1a91fc8715a33d0e.nq.gz
    ├── 1e5653fbcd1669bea580c8741ef44aa6b74df746.nq.gz
    ├── 1ea7826dd6bc382adc7284a61a1a5c3ff06124e0.nq.gz
    ├── 1f33d640ddfaf33ffc1f8854bbbd6bad2aa14ba8.nq.gz
    ├── 1f4321ddc2a21030e1fc802ac26ec771d81eb3c1.nq.gz
    ├── 1f4ccc12c99386ddbbbb505f3b81b14a938fcf86.nq.gz
    ├── 1f5db4a2b7eb0c53798989be902f95a72a49ece1.nq.gz
    ├── 1f6192c69dd228131818247cad961d68c24b4bfe.nq.gz
    ├── 1f661c58a4ab1479b4b8c3a2763065bebb0ba549.nq.gz
    ├── 1f82639df74b8374916b14eebdacbf1405fc49e3.nq.gz
    ├── 1f84b12f7356b61215d32b059471b687be56b09d.nq.gz
    ├── 1f87d328b5d28854f166dbbbbc87e89806a76fec.nq.gz
    ├── 1fb7cf4dc3eae838212ec69b4b734bbdedafb778.nq.gz
    ├── 1fd57dd1c184999d501eb59df6383e8c6955d360.nq.gz
    ├── 202db752ee13e9b2c0767491e27c6d192ec887ba.nq.gz
    ├── 20aa595eac7695b2d354777423ef47e5f1cad330.nq.gz
    ├── 20b51b28d84e8b185524cc1f4b3ba913c715cd0c.nq.gz
    ├── 211ce90684b46080f03b8376661695e08eacd4ea.nq.gz
    ├── 219cc966a55583b6adb993d074ef175a66fd44a4.nq.gz
    ├── 21b700ef73998dd75982df301e2262dcc4440852.nq.gz
    ├── 21b725d22806afaa0639e837a75963691c90be77.nq.gz
    ├── 222c0ba3b24225b34c6cbd534d1c5cbbf3a8a97a.nq.gz
    ├── 225da729469e82cae7f652bfe8d1980d92429653.nq.gz
    ├── 226941032382c7f00993c86aec8813ad8c11e815.nq.gz
    ├── 227b161faf648fce257520f9da8bf71505f90c44.nq.gz
    ├── 228a1a7c7452d33fa1bc9fc4e5000f308489ca26.nq.gz
    ├── 228f37a1e742f96e65fc86e355ffd8de9c88f901.nq.gz
    ├── 22b4d8962e6d942ece6589596f05d0a0af7d7fc3.nq.gz
    ├── 233b1d23d5103319654a1ad379995295f2196169.nq.gz
    ├── 235b919bf5c91c2c6e6e5f7a0261bf0905244af1.nq.gz
    ├── 23a9dc5c19e432ccb4762d309c7c450ed2ca4580.nq.gz
    ├── 23efd1e5b9078a82efe1b8f0ab581895ac889b5e.nq.gz
    ├── 23f81f53a7bf1cff375c3fd33e9b8e4b143900c3.nq.gz
    ├── 250914ee930ae79378c358c219af542c84ca6a15.nq.gz
    ├── 252ee27a24e44111812c2b975998e6d7d02c6260.nq.gz
    ├── 25992a329e26c124ace7888a8ffa9eda3d12a11d.nq.gz
    ├── 25dc7f852a43adbec18d46e6db48a243e8139984.nq.gz
    ├── 264fcb4765aeca5bbf973a94e7302093a6126847.nq.gz
    ├── 26b7b6250151ba5c57d1189af78b1f27166fb39e.nq.gz
    ├── 26db379d976b0878d1c763d3b7a7f2d19183bfbf.nq.gz
    ├── 26ebb65a580e921beb5c5766d17b22f64eeac340.nq.gz
    ├── 2709a1da087f177aac877eeb8d351c23a0dc261f.nq.gz
    ├── 271f8b1ced368b7c26c4ad139cbed40b7d61fc30.nq.gz
    ├── 287a3afe520c3f15447450f16b23f056fec04975.nq.gz
    ├── 28b0c077019661d6ec49ddc573f2ea9c94f4c33b.nq.gz
    ├── 290b842a7372c9bbe955e511d7294d4385955e3c.nq.gz
    ├── 29378267140ac5f89f296b03477a48e8709a08e6.nq.gz
    ├── 295376a73c54d3ea0eb5edaf9d28f4d1225a25b6.nq.gz
    ├── 299b26cbce6b78d1c227383f93c205da34a79496.nq.gz
    ├── 29e299627d840208f289c22ce8524a12943b10a1.nq.gz
    ├── 2a096b47a3837502533d87b9765dd72a6465979d.nq.gz
    ├── 2a22c368d24de895626fcf16c1a619b75a16b005.nq.gz
    ├── 2a27ac11bc4a94511257e18566cf3a3b2e624315.nq.gz
    ├── 2a30ddeee4e5f060c72f5ba2199e545f27e4592e.nq.gz
    ├── 2a375e2575a9ff4fe8f89e06f7d7e000f041a2c8.nq.gz
    ├── 2ae45db83f97248c522866f055bd3987c7dc218a.nq.gz
    ├── 2ae9865a0801990646338040ae72c56f3c2a8a28.nq.gz
    ├── 2ae9d4d85240044bc293a6a39d86e8908049627c.nq.gz
    ├── 2bdc8a27e91afedb674fef8b438cf063cad97cc9.nq.gz
    ├── 2c31ff9814f2ba71289888094d892e834b65ef58.nq.gz
    ├── 2cac0c043805cbdd2f316382f77ae0a8c92fef78.nq.gz
    ├── 2cd2468a33237bf5fca9b633004c08685d9e2426.nq.gz
    ├── 2d3307061126d0180edbd74f7e64ede9df458534.nq.gz
    ├── 2d616d24be3ff85a5ac2fa359d784fb956620cb9.nq.gz
    ├── 2da60abfd4c25a33bedcd3ff0c042fe0a1923f94.nq.gz
    ├── 2dc30772509fb96c21d5fc49695290eb368f3dca.nq.gz
    ├── 2dca76f5259d89d603b7295bba7fe049cf19c60c.nq.gz
    └── 2dd68d29ce1c3d68abf313ee92259faad16deb08.nq.gz

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

[anthropics/anthropic-sdk-php](https://github.com/anthropics/anthropic-sdk-php)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*
