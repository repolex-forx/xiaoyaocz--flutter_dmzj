# Repolex Knowledge Graph of xiaoyaocz/flutter_dmzj

RDF knowledge graph data for [xiaoyaocz/flutter_dmzj](https://github.com/xiaoyaocz/flutter_dmzj), parsed by [repolex](https://repolex.ai).

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
rlex download xiaoyaocz/flutter_dmzj
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6e27f949f2932708f9e2794a3b9e7a6e0e7909ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6e27f949f2932708f9e2794a3b9e7a6e0e7909ef
│           └── chunk-001.nq.gz
└── blob
    ├── 0078076c586f38a690cd86aa60c72fa779f0b60e.nq.gz
    ├── 01320b9269211fde85450b1dda1ef14e4f6c3497.nq.gz
    ├── 01d349fcaf79e4be30e0277fdfe69f87aaf55ae5.nq.gz
    ├── 03bfe0a8d49307462a6c8a856fd294aad02af9f9.nq.gz
    ├── 03f280227a80f1c533c39b5dfb580bc1b391f6a1.nq.gz
    ├── 040824a64df486857f5636fdc8d11b8a00454f9a.nq.gz
    ├── 049abe2954279f0ed15c66d4c858fa4ae2a590bf.nq.gz
    ├── 04e6d52165453a135f490f9448b9a3e40971c03e.nq.gz
    ├── 05d50f1f0a57e11964a6e2c4a8f625d2091a1a24.nq.gz
    ├── 06bbe04b1a57690b53ad202aef68bfd914bc13c4.nq.gz
    ├── 072239b4d720a75dc6e9da2953ecc2433a191027.nq.gz
    ├── 07e02901765f88136121ea52356fc0d4b3acacfa.nq.gz
    ├── 083aea6eab1c7d978a41a1008c46717592e74349.nq.gz
    ├── 0b02452d3e23f5c383c63f4076aef41c02b9367c.nq.gz
    ├── 0b336a670e94632048fb7447f2f99d435b28eb30.nq.gz
    ├── 0b414bc9c1a9f5f77c32a5a6655aa0ca1227d40c.nq.gz
    ├── 0ccc107319b83288d8ba55b59f499d1002b4967d.nq.gz
    ├── 0e87c9c5d1dead3d0749bcae66cc2ff3632a5061.nq.gz
    ├── 0f5e77d728c5ae760d3a6d4e5ae8fe1ccc5cf916.nq.gz
    ├── 0fbd61224f762ec16f60040e2caab0fbbdd6e5ce.nq.gz
    ├── 0fef2606905a0fab009f332475b629fb3d7117d6.nq.gz
    ├── 10729e67cc0697b9df13a4bcf78d892289ea6ddd.nq.gz
    ├── 109befba55ee05c97f67d87e3de1888496ff76db.nq.gz
    ├── 10c8d03ecbb083199d7a1c5b709abd18bdc693b1.nq.gz
    ├── 11864a7e411fa8d2925a7a85c8738e4e101c4682.nq.gz
    ├── 12f03b39d7f3c3c50d420b514b947619f6a94d4f.nq.gz
    ├── 14da648f35f351228580213ae24786d72a42f22e.nq.gz
    ├── 15dfa91f6362256ddcaae3ab7daa80e50dfdd57b.nq.gz
    ├── 168ab0bed78a2915417271bad30be8335feaa7b3.nq.gz
    ├── 17ba431125b4b5e7df0c768da15f4aded702e6b9.nq.gz
    ├── 186ae98e899858bc80132dd0350ab564a355da72.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 19958abd42e93b3fe88dd240b3448345a4a5a880.nq.gz
    ├── 19a42d80f9205bbd259a7482c865c0e151822028.nq.gz
    ├── 1a48ce28f335268393e6db5817311273f2860575.nq.gz
    ├── 1b7d143a7a55557d1161173fe3d40a06c536abed.nq.gz
    ├── 2014038ac2120a1cd7c442bf5efa3ae467ad598f.nq.gz
    ├── 21329f3caf10a4165ff93d27bdb73b4979a36cfb.nq.gz
    ├── 215389f8fba6e8870d03d6bbc6c77e69e4dc7d0b.nq.gz
    ├── 21731fbeb9a170ee078b302838384a7f9f7e02c5.nq.gz
    ├── 21a3cc14c74e969ab1548274a8512ebfecc40f78.nq.gz
    ├── 21fc01ecd9e28cb8963fe50bfc0f4bf718bbd768.nq.gz
    ├── 23c410c29dfe7b9766f52ec3cb57de1cf072e3b1.nq.gz
    ├── 2439f15c2cb7d1046af45236a2fe03358d2153ca.nq.gz
    ├── 268af418e242551fc05de0cb8c86e6a37644d655.nq.gz
    ├── 26c7bddc20f7d330ef8a41f6aee0d2e611a172f6.nq.gz
    ├── 26f32dbfa1f53cd2ae7ed097346cbdec45612b77.nq.gz
    ├── 2722837ec9181c3c1b2f1c1298870185c03ba354.nq.gz
    ├── 275882d9167a8d3c78683a7af38a1b171e34598d.nq.gz
    ├── 27b653d0ace19478d82cde6773c76029b0c2876c.nq.gz
    ├── 27c3f134e4e1216498217aff33f7b0851dd13d23.nq.gz
    ├── 282b59d497d6ffd0975e0a692ad822aa298b75f0.nq.gz
    ├── 2832dca3d443f09d864db0aab6b9bd975881a032.nq.gz
    ├── 2923d8730bc3b385b99467e137073c1e37e931bb.nq.gz
    ├── 29d3dd78791fe7bd4571b894872e72164e3c901a.nq.gz
    ├── 2a26ed6e86bd10ba4c14ef2cc80c85fa5a2d9982.nq.gz
    ├── 2a7b7a34b05647f3f6da402842e66616c8aabe84.nq.gz
    ├── 2b5dc72d54e9a967daac0221f89130abc9c943b9.nq.gz
    ├── 2c17c86af26cf15ec60830b2e275863cc58846a4.nq.gz
    ├── 2d7c7bb8fb612c3a8de03e2ff30af33e9bf02a79.nq.gz
    ├── 2e6f0b72b4b609722c36859cc77fff08041eb9bf.nq.gz
    ├── 2eec9ef3756a7891edd30b9736e87990ead75bb4.nq.gz
    ├── 2ef44ced304df08f8f44f6aed14e21ac74b07f1b.nq.gz
    ├── 2f82c6d5b9c97d98f8e04f7cd0904a5f7ea62ed0.nq.gz
    ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
    ├── 308a2a560b42f17aaf3c36e4e9c8cd07182fbb7e.nq.gz
    ├── 313653c07cd305e0ca31c338741c152fe62d99c5.nq.gz
    ├── 31762262971f37a4ef88ea13e2af9d64ba7b61a7.nq.gz
    ├── 32f61718348d9cc8f61a51f865217a12b011d3cb.nq.gz
    ├── 3485f42f76a04f075642bd72c1c343b75c93aa42.nq.gz
    ├── 34b76c8d0ebf1ffa1e9bd0f1dcd284549c79523a.nq.gz
    ├── 34fa6cec6027837893d7a91cc9c6257d6f5c2cb9.nq.gz
    ├── 36083d8c3429c13ea94bafb4c5be5a825a4676f4.nq.gz
    ├── 3693f6469bdfe3f73afafc37d67d725883e4a14b.nq.gz
    ├── 36ab315e99736e69ea6a8cabec2decc5a571715c.nq.gz
    ├── 36b0fd9464f45b33f482e64bea579787e142affa.nq.gz
    ├── 36bc5ebd38a087be46f3d2f70b7fb00fe22e804b.nq.gz
    ├── 37898526bc540e0bbdfd11bcc77f3f91c942406f.nq.gz
    ├── 379ee09b9b898616f47cf77703aa8d38fa3cd937.nq.gz
    ├── 3879d54755798567f0f318d63340508d5668eb96.nq.gz
    ├── 38bd01d6de6d1fe4cb6f3ebe00ed29f783c235e7.nq.gz
    ├── 392cf40d6e437a9379873476c5f461ccf3ebb315.nq.gz
    ├── 394917c053a04daa76d8b94f0a02db0bd99e1034.nq.gz
    ├── 39514af5c63925e55e7056fd240bfa73033d70db.nq.gz
    ├── 3993ce7b75311e026cc90e10c227496865488866.nq.gz
    ├── 39940e79aa928ad5324180f738548bbb375a2b6c.nq.gz
    ├── 39c82bcd8735d5a366f9480740919274cdaabc16.nq.gz
    ├── 3a66706ba14133f26b8ca125c31d2baf8ba5d493.nq.gz
    ├── 3b5526bed6e9db9fcee02a618751d67e1777308e.nq.gz
    ├── 3bb5b514599df7ff6d7b3c1545e01ed1a38f5fcd.nq.gz
    ├── 3bd1798e8f561012064c169b48aa5a8ca22b8bad.nq.gz
    ├── 3da0e41f7ee4e6c722b9ae8c77976a55b3ebc39e.nq.gz
    ├── 3e0ff16f724399bf0a76fdb11f7cea462daa315a.nq.gz
    ├── 3e9eb7c3926abd72c52df82c5f1f0b14c764b999.nq.gz
    ├── 3f728e3a9693cf59f7b775134d425a215f11e5d5.nq.gz
    ├── 3fec07ba7c2b5d939a642646ba96ebcee016b8a7.nq.gz
    ├── 411547995e3ed96ba24e14ff85a0adb9f24c3bf1.nq.gz
    ├── 425ed37e942893bdc3f87ef5e05d2315d24df481.nq.gz
    ├── 427272f19fde5e76a736460c669b2f43d343fda1.nq.gz
    ├── 42aafa40f9b3b12ad405367b1040be62a821a2b4.nq.gz
    ├── 42bcbf4780b187e80025b7917058bcb882012aa1.nq.gz
    ├── 43d5a304f8358e227c3d07646722ed31b5a5bc75.nq.gz
    ├── 446053341437561e16348595b25f7e91d955ba81.nq.gz
    ├── 449e249d39d1ed446f14a8d2b0d143b2ce1aae46.nq.gz
    ├── 44e62bcf06ae649ea809590f8a861059886502e8.nq.gz
    ├── 4593528db7b2cdc42a6d6fa8a86eb16d106b292a.nq.gz
    ├── 4789daa6a443eefa7f3f729164a18351e06e9800.nq.gz
    ├── 48ab2c156a6c9a16b81dde7dd7da35abaded58fc.nq.gz
    ├── 4af8dc65861b223401cacc51c2e9644e8938a1ed.nq.gz
    ├── 4b3d1e819cdf5a180d40172d5dc0596ea064c7d3.nq.gz
    ├── 4b81f9b2d200fc807eed25bca04dff9ee9dcc45f.nq.gz
    ├── 4b9037400b62076f8538e8e781cd2ee0c9574d54.nq.gz
    ├── 4bb22448bf09f82407297d8dcf2e1e126eb6451e.nq.gz
    ├── 4c2c0a2df51e30d5fa20a5edfc84d1c7697cc3d9.nq.gz
    ├── 4c6a7bed5bafb2c0986c5541b3156691ea6f2eeb.nq.gz
    ├── 4f39659a8990ba8c0c19b7df8f6a39a34447f461.nq.gz
    ├── 4f71e514c448267f672917fbba9330b223b44386.nq.gz
    ├── 4f959f681c8e15b09d2f99b903425bd0c9487fe2.nq.gz
    ├── 4fe5f2b528f2f135777ea27e4f0c3c23aebcad59.nq.gz
    ├── 4feb5cc7b999ad640b4eeee0fe3b8fae59bc5920.nq.gz
    ├── 502bfacf0b39e9e683ab5ac5f365f0a4873582e7.nq.gz
    ├── 5055d70c6580732bce165cfdb49c5fc5f295467b.nq.gz
    ├── 5517d36d4c5a28f862eb9eba5b7fa536c5891a32.nq.gz
    ├── 5730ffe20945277651687f082d2efbbcf9bdce4f.nq.gz
    ├── 57aecb61eac777015941a4352766114af7d4e712.nq.gz
    ├── 58dfa2277c6df15139c4ea340fc0c7ac0289f0c2.nq.gz
    ├── 5a07d3b8cb85ff3b93855b0c2270fe0956cdf306.nq.gz
    ├── 5caa9d1579e481a5894c37e2e56b0da062e95b35.nq.gz
    ├── 5caf564cb4dbc79b784d226d432f6140543f712c.nq.gz
    ├── 5d3b6fd7a8a5b2c04ca7eab94a30ab408dd8ee1c.nq.gz
    ├── 5eaece27f9bbe1b5d0fd3cf15f63b14bc6062c38.nq.gz
    ├── 6145493db157563b21d67c052064f0c5a754d4a8.nq.gz
    ├── 61b6c4de17c96863d24279f06b85e01b6ebbdb34.nq.gz
    ├── 62253aeae02d9528d4b7c390cd39c97643ce148c.nq.gz
    ├── 624b372ce000c93633820bb02306d3ab367f0a5b.nq.gz
    ├── 629c68c459d111e9da4f4086ee5e3d5acade2b50.nq.gz
    ├── 646a2ca503c1eb636d0716057fac990d86497eb6.nq.gz
    ├── 65165ad4aefa79569a178407af444aa6da3b4ff8.nq.gz
    ├── 655316c05338b431f5bed6493de44345897112df.nq.gz
    ├── 66a65d1e4a79f230031ec0e0959a721039e7282f.nq.gz
    ├── 6a3569da694d5bed68024c2b91d95c804c1af002.nq.gz
    ├── 6cef4b0b6b98f42ee371ddc174775fa252fd9c0d.nq.gz
    ├── 6d20bbd018482f408e29e75669e9db939d75f79c.nq.gz
    ├── 6d713dd02403aac97aaf2ca04d4d57ec703f5d85.nq.gz
    ├── 6da0652f05f28fc6950cec20ebdfbae89b665479.nq.gz
    ├── 6e3227d43f3236f059e2d12f9d219669f479575f.nq.gz
    ├── 6e7ce79a665c174d5671ed8ddce819c735bc6e29.nq.gz
    ├── 6e9778b10076a97c6e780eb5db18f8678e475e2d.nq.gz
    ├── 6e9f9af2fa3ff0cd5872b6b26a5fa790f6f5885c.nq.gz
    ├── 6f568019d3c69d4966bb5a0f759980a1472afc1e.nq.gz
    ├── 6fafa59c86f625200aec45c2787ab1ae17b7c290.nq.gz
    ├── 6fc7ef89a7a611d564f3b2c57106417e19063162.nq.gz
    ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
    ├── 71465c47a8759efbc65bc6cb2ad41742204be13d.nq.gz
    ├── 715196cdb40a16dda44edb2da378f1aebae8c8c2.nq.gz
    ├── 71b4a8bfdad39cf94bd8552a7561fff940a93906.nq.gz
    ├── 72271d5e41701cfbffad74d38640bf9cc7c1f7be.nq.gz
    ├── 7299b5cf271cb63fb6c0dc16d78c40ac2133856c.nq.gz
    ├── 7448c35c78c33cef8855f4413b6dd869c49ac6de.nq.gz
    ├── 746adbb6b9e14b7e685c91e280a4d37a672afbd8.nq.gz
    ├── 75334525240d3773a6bd7c2029aee0fd6dd411ab.nq.gz
    ├── 786ff5c29768bf39b81046dfa5165296356425b1.nq.gz
    ├── 797a562d5c25a052d7bba3876f69691afba9281a.nq.gz
    ├── 7a5f0f05006bf60842957010ef81cd2b2c76c49a.nq.gz
    ├── 7a7f9873ad7dceb4dc17087fb06c800fa0191376.nq.gz
    ├── 7b0fb547cb81cb033294168e9a3042e881a4d4fd.nq.gz
    ├── 7c5f35785eaeb4afd45f4d5a43765eef48f1f6eb.nq.gz
    ├── 7cda621e4e38a772c8a40ba353cc7025cd3b3b67.nq.gz
    ├── 7d072e0b834cf834ec886eb3cf36824ec8e97fb7.nq.gz
    ├── 7deefe13bd431ad700b46af641668e0e134fe645.nq.gz
    ├── 7e2155ffb56e63855c25c485641b762ef034d940.nq.gz
    ├── 7e6cff79353fc3250d6d3b05add8fe916ce7b21e.nq.gz
    ├── 7e73cf0fa4b3c66b4c7986b6d6d4c302a7ce2ce6.nq.gz
    ├── 7eb1979ae42e3ff46b48e01bb50df5467ecb4b22.nq.gz
    ├── 7f0e91745ab4096809e65d7065bfc70454f516d6.nq.gz
    ├── 7facd292eb56e15a1dd02b3dc03f284e4e5189dd.nq.gz
    ├── 80261890567ce2263de057d80324329f43cb1cbd.nq.gz
    ├── 80514a9c3d580a37a044b938c90413b942075f5c.nq.gz
    ├── 80868ff373525b896535772b619e82770d8f327b.nq.gz
    ├── 80e867a4e06b4dc26d0a2b327cbd54041addc50a.nq.gz
    ├── 8123dcb9191bccb7b7b22f50393922743436fbf8.nq.gz
    ├── 816df8b44fcd6c6ebf82e6565ba50c4f289085b0.nq.gz
    ├── 82255d415c7d7a5a10577527e4b732987e5fa688.nq.gz
    ├── 826f861748658ee95a569a32936beb2f97205f0f.nq.gz
    ├── 82bf9312680e5b3e2f5b0d4bbe05838b43fbb7b5.nq.gz
    ├── 82fb13e1523e9fc23dfe667ba135a203e46d859e.nq.gz
    ├── 839b881303862109cd5cd3aa04bb181f479b18d4.nq.gz
    ├── 85aff46e87b711b591b2baeff721cd617c38e743.nq.gz
    ├── 863e6a1605e74c1ab568961a3b88baa866b403d9.nq.gz
    ├── 869ca4d337aa5991ff494a8e7a7bc16d8207a83b.nq.gz
    ├── 89272c1a471d5e400dd7646b610c23f33369e149.nq.gz
    ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
    ├── 89c3877da1b23db92274bc10da2d1c44b9f00ad7.nq.gz
    ├── 89c86337c9e0476c6a91351d668bb3df46e3c729.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8c31102c9c227ab471b032c462a0efff2721a144.nq.gz
    ├── 8e8a50b35f693bf38771a4630cb9d8d1dff6f798.nq.gz
    └── 8f4aebb5a8d17a12fb8c05ddc3ebb6968a6aebd2.nq.gz

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

[xiaoyaocz/flutter_dmzj](https://github.com/xiaoyaocz/flutter_dmzj)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
