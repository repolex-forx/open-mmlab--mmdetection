# Repolex Knowledge Graph of open-mmlab/mmdetection

RDF knowledge graph data for [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection), parsed by [repolex](https://repolex.ai).

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
rlex download open-mmlab/mmdetection
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfd5d3a985b0249de009b67d04f37263e11cdf3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cfd5d3a985b0249de009b67d04f37263e11cdf3d
│           └── chunk-001.nq.gz
└── blob
    ├── 00d2567b245dba2b2be815a92146ea1364e1e799.nq.gz
    ├── 012e711cb96f9aa67460b86694838d592fd1ae25.nq.gz
    ├── 012e89b8338c69c4ffdf4182827a185233945288.nq.gz
    ├── 01b40273341f2a85cfa427f8adfc945a1b7da58a.nq.gz
    ├── 02425551174d57ae6fecd51be7960acad84c934c.nq.gz
    ├── 025e54beb14a28f09b23fb32b3f71f068494955d.nq.gz
    ├── 0273aa08fbbd4493042a9f3b707a6dff002e727a.nq.gz
    ├── 0276fb331f23c1a7f7451faf2a8f768e616d45fd.nq.gz
    ├── 033cf574962f51a75c3fce1e74a22efb9c6320f2.nq.gz
    ├── 04072f9b84c06d546767649f7e17736444db7ce2.nq.gz
    ├── 04d67d0ca8f08860462eb0eafc645c403e792394.nq.gz
    ├── 051db7f1319f8146e5bf64f788c327381065e36d.nq.gz
    ├── 0542b9afcb07f05891980eb657337318c439d091.nq.gz
    ├── 05d62b850a70ea53948b6a687f2c14967f882cf2.nq.gz
    ├── 062190fa077d7b01e0c1db76bea0cfb5dc7b6620.nq.gz
    ├── 07d7db2432a39580acd5f1fe6dcdde593bc8ac05.nq.gz
    ├── 089934148f5f21e36d74ea247817d034dd364e6f.nq.gz
    ├── 08dbfa87f5625ba6500c731910c178a5e2684e0f.nq.gz
    ├── 094306b2fbd18ba45536470ec80443e4ff793e67.nq.gz
    ├── 0aac6cf33a92827c9c350175977bb1a595d2c0c8.nq.gz
    ├── 0bfcc728dc4cc33c0b705a2ab22a4e3f4ad7386d.nq.gz
    ├── 0bfcec1891ccb468bcccf975b9bd26bca53e0a7f.nq.gz
    ├── 0cf188653cd9adda59decd45f65fc4ede63fe3a7.nq.gz
    ├── 0dc98515e62b2dba225e822850229f0a2f802d63.nq.gz
    ├── 0eaac4422896d01f63807c29851f11a06f7ff45f.nq.gz
    ├── 0faee07007e809ef08e86a88e8b11c2be1a64034.nq.gz
    ├── 1016999729263d72bbd75019be4968bc3960e368.nq.gz
    ├── 1090678f652444c82a627fbf8bdda39fe0077f1e.nq.gz
    ├── 11360af18de729bfd9e8d8cb6597067a588852c9.nq.gz
    ├── 1177fa9faad623df03d8df816077e83914570cb9.nq.gz
    ├── 1271ae1d8a3e9b052d06e72f7b764887d171d96e.nq.gz
    ├── 12d9f13263619333391befd6692c83622091ef4e.nq.gz
    ├── 135bb60bb340c40a47a9bd64e5a8afc57ede60db.nq.gz
    ├── 142f27d7f94c463e679828ea3c6c1caa99f3b95a.nq.gz
    ├── 1452baeca7e680b11f9b2ec654abe689d3e53042.nq.gz
    ├── 14562aa1069464c0986ba09ffa9187c62fbfc0d1.nq.gz
    ├── 14ee62a7910d90a108fefb2acef00c91ab83ecc8.nq.gz
    ├── 155af5fd5264b245c918e314289996d3f0471b3e.nq.gz
    ├── 159d96d712ae047efd7988bc53ae65006291478f.nq.gz
    ├── 15bef293a591a7f4c099febdaa82abaf7fb4928a.nq.gz
    ├── 15dd7b2fb5b2f890de78d036746b3c8371f0ddf3.nq.gz
    ├── 16290076c07d7a97108b89e4a41b5ff51cbbcdc1.nq.gz
    ├── 183f3167445dc0818e4fa37bdd2049d3876ed031.nq.gz
    ├── 18f6601ff82394864d53351b10b40f51eb2aec6b.nq.gz
    ├── 19c3e1e335ca4e4a9d5befcbffcf4665b459cb5a.nq.gz
    ├── 19dbeef1cde79fcb2aa80bb9936a60cc30089963.nq.gz
    ├── 19fbba80f0396e1dad7a330ef769d98ad1a0c4d2.nq.gz
    ├── 1a07c8b2302b9c2337d4da2d32c388142ca1f748.nq.gz
    ├── 1a24b82db328fe206eb618c542ed8d58affe42e3.nq.gz
    ├── 1a5e505d2888f4c521c29d9c8bc6079fac077590.nq.gz
    ├── 1abbc5d9bb9cf1656ff95fb813fee0db4a40d74e.nq.gz
    ├── 1b791d01d50ad8a28bff225fa1d3f5af8d348207.nq.gz
    ├── 1caa901228f2439492b82d1890eba468963eb28d.nq.gz
    ├── 1d6f48f94f286e3c5e3179f752a7b36ea77c0d45.nq.gz
    ├── 1db71549d89766c45012517c20cef443f4760419.nq.gz
    ├── 1e01bf27c03d09d1e66df8e6569b89c7d26f90c9.nq.gz
    ├── 1e54b030fa68f76f22edf66e3594d66a13c2c672.nq.gz
    ├── 1eefe4c532267be1480d13b8d73fc54bf694e81c.nq.gz
    ├── 1f19e5e498b18a404f3c4e6419316b5f9981e811.nq.gz
    ├── 1f79e447d3f24e364739740be504bb234adc1e98.nq.gz
    ├── 1f8fb68cdf836d4bb70ba22362a91679e1f06cd5.nq.gz
    ├── 1fee345967ed72cefdd50c3116d81668c91943be.nq.gz
    ├── 202122f685402e41bbfb270b445a7b1c04ccf1a8.nq.gz
    ├── 21b6d2ea1c0167b8dd643211b520ac89ddd63e10.nq.gz
    ├── 222671d49d1e3fbc31285e4f13487d86642ebbe3.nq.gz
    ├── 22a2aa889a59fd0e0afeb95a7369028def6e4fa9.nq.gz
    ├── 22f3e3401a4abd9cc35b41d24efe23e5655a905e.nq.gz
    ├── 23eadd4f655b0eff31d2840cdcad332afab073b7.nq.gz
    ├── 24b3f7841947204f2ecea385dcfa8b97fa0c6e85.nq.gz
    ├── 24c0655ee1c36e0110cf6578d1c095c50a297d81.nq.gz
    ├── 25c547f8eca6a5211d9bad4fd8c99b7ea59cb1bb.nq.gz
    ├── 260ec470fda46ae8d41dd768c5924da59803eb94.nq.gz
    ├── 26325e249dc6f867925c10390b0c52cc6c52e6e0.nq.gz
    ├── 26a49b52476dfa72bde2923db73662ec25f50f33.nq.gz
    ├── 2737ec0efce53fc0ed1542451262d153845aaff5.nq.gz
    ├── 276d45d8c21fa1eba130e834671bdddd794fa1f5.nq.gz
    ├── 27f49355f3be8f6a53038894405c5f1b3d9b46fa.nq.gz
    ├── 28953256200a3a6c76254de46f74875f070be172.nq.gz
    ├── 28ba7c77ddf10d295d371db2f46d6c1f117ac7c6.nq.gz
    ├── 28d6290be7a75b7cceef8957e872e221fd3e78f5.nq.gz
    ├── 2a1e38cf14c298ec17f038e00e7af9e36b4029bf.nq.gz
    ├── 2a527828a467df069bbdbe624b55c1afcaa3521f.nq.gz
    ├── 2aa3e536c7b2477177b70045181f6f27635d96f8.nq.gz
    ├── 2ada04d2a0127e93d6f8d364f39b5b40c67ef2f6.nq.gz
    ├── 2affe520918d0f26c0a858f97bb69646a2860f87.nq.gz
    ├── 2cf429153ba7e0be025396b069aef8212144e34d.nq.gz
    ├── 2f10db2f3c84d4b1970f13f54c563408487d04af.nq.gz
    ├── 2f53f456c72db57bfa69a8d022c92d153580209e.nq.gz
    ├── 2f64450e94cae436a05f46da67d3a1264235ffbd.nq.gz
    ├── 305b9d6fee8d75273b588f32b2e21582473cb137.nq.gz
    ├── 307dd5d15c962b97dc60b899e60170d0bfed90a7.nq.gz
    ├── 30b96f07cece7666c488972e315dbdcededdb21f.nq.gz
    ├── 30f7844b8344110896c5d885bd0ca340322045e4.nq.gz
    ├── 3110f9fdf590ea665c9d7b7e28a56613cd79b786.nq.gz
    ├── 34a818caefcbfcdd9e51ec304fb94906c20ceb9a.nq.gz
    ├── 34f7f0b8f90ad29f5250c8c86366e0a02a30142d.nq.gz
    ├── 3503a40c8eb6d6c0496ea0f31740acecf774113a.nq.gz
    ├── 35b9df0c45148cb18e8afb659b10dd0b9e866b99.nq.gz
    ├── 35c8aa6748d25e4c9c834478488ee21b44c8f2bd.nq.gz
    ├── 3779744322a19d2865f1e6299aba564c4ec1e3d5.nq.gz
    ├── 3782eb898cf8acace63b4f16204cae6c07eb6e30.nq.gz
    ├── 37bb92f5787d598571aa0189f2a7adbbc05e6963.nq.gz
    ├── 388305cceac2e81eb1b4df6eac36662df7b8bf0d.nq.gz
    ├── 39639d874cbeb54b64a2789f251f1f6dad585ce3.nq.gz
    ├── 39db35c26830871755ef072d4a3d9ffe6dd628fb.nq.gz
    ├── 3a5e04e1a9fbdf20e43cd4fa7cff179a6702082b.nq.gz
    ├── 3aa2dfd49669ba931d20ad9482cb841698cceb8a.nq.gz
    ├── 3ac884ac8b40c1543ed840dfcafe367fbe4bda62.nq.gz
    ├── 3ba4aea8eac72f347940fb12ac964e9bf67c2e0e.nq.gz
    ├── 3c402c08823a60759c984093ba7f05f1e310dbd9.nq.gz
    ├── 3c78909df80173eb37ff83c4ba12614e73848f29.nq.gz
    ├── 3d05f0ce1c0cb095c0c9f9a65bd7666cba57afe7.nq.gz
    ├── 3d366f3ba0e5ff098db3e409171a88860f1cf3af.nq.gz
    ├── 3edf49f052f1f3c875cca2c061276cc1aca77604.nq.gz
    ├── 3f6f459cbbb48c50d5fbd6abec3c6dbda4d422b4.nq.gz
    ├── 403b18a4ca8ed61aedcb99218ecc79302826ff8c.nq.gz
    ├── 406a39a4264a0d6ea5d7950a205b0bac72e8f846.nq.gz
    ├── 41f1c7166e6c7d05c5414cd04ad3eb3cd467f1b6.nq.gz
    ├── 4232fac1d4bb110953b7ce012f3e6ee92320f2e0.nq.gz
    ├── 42b9aa6d05dc64f3045685a7c23d632a6041249c.nq.gz
    ├── 43d5dd60b8af8a6200e21a196c47d00dd2812a46.nq.gz
    ├── 443a0a71b46f4d2eda45571d6b7e108af6528d02.nq.gz
    ├── 45041f6d236be95eb7592035d31f155c61bfcb25.nq.gz
    ├── 45260e2e39b53c0107e257ef2d05a14f5d5c0323.nq.gz
    ├── 4636b8e785a9db92938378781a5a46547eb94fa2.nq.gz
    ├── 468461b41799f27b29342091185294b7b2a98896.nq.gz
    ├── 468b9bfb2453f97c83282cc2f383c7592694269c.nq.gz
    ├── 46d41ed4ed5d1d6345e98434221cc5b07c60767d.nq.gz
    ├── 46f60577728d3e9d8785f19d8cda34991bae06d3.nq.gz
    ├── 47511b78ed2edb43121de2fc27986f6bb81abcfa.nq.gz
    ├── 47d1fa6a4852c40f3f9962a47ec90e365671c61c.nq.gz
    ├── 47f5e6563b7f47dd6cfec02248d4c8decd32afe4.nq.gz
    ├── 496104e12550a1985f9c9e3748a343f69d7df6d8.nq.gz
    ├── 4b5c46574a30bbb2253fc69f79edbcf0cb016505.nq.gz
    ├── 4b63ba340b2577e12ff052aef66730a633cb8c6b.nq.gz
    ├── 4be492d5419b8598120faa29eed44eada0fb5ba2.nq.gz
    ├── 4c0f69a9e339e2a4e082dd0ffc7ede68cd834a4a.nq.gz
    ├── 4d6afa75cd268d3cca9b777b9a9d2eb9544af468.nq.gz
    ├── 4e09990c603aee8ced3bf3a65ceb530142e6e873.nq.gz
    ├── 4e2e0b79b60392e410c9fa4225894ed245bfd41d.nq.gz
    ├── 4f232d6111026488020e586440852c012dd94608.nq.gz
    ├── 4f38ef44e482039fdf7476d048eee5df2a96fd9b.nq.gz
    ├── 50c57f01ca3a6ea827f71801b0c233af268914f9.nq.gz
    ├── 5160a2fbdefb67550967047eef04b6104e4abd5f.nq.gz
    ├── 5225d2ab672738d4d427eba252e92bd554252476.nq.gz
    ├── 5330af1d1fa20597e4e8c7f8b7954632a743b424.nq.gz
    ├── 5471caa139c0b7670f995501347ddf80383e9268.nq.gz
    ├── 54b29e4f7aea547e2b26782b71ada8053930d325.nq.gz
    ├── 555b10102f67ee625d65dbfe0894eb4b41198595.nq.gz
    ├── 5598dabaf6f3b3a09f4348fcd65ff39897b7068f.nq.gz
    ├── 55ad113be4606c82ecfbacbf8e615c22594f26b3.nq.gz
    ├── 55b5c35b3a4888c95c6646df3fa080347afe4704.nq.gz
    ├── 55c5c8e4fae7d4e941a770d985c7253fd70f2226.nq.gz
    ├── 55e3c05b7aba188608f7dd2fdda54e0759cee03c.nq.gz
    ├── 5609c0821dcff4ae1e9b33a00d24cc61b59ebc36.nq.gz
    ├── 56356c3c555e17d35b806cd8e96c73e279b800ff.nq.gz
    ├── 566397227f7861a268c4cc4e111279b95b620ab8.nq.gz
    ├── 567c31bd0e986e071b50ff2aac9cb896d4daf6fd.nq.gz
    ├── 56ca2c3c18fee94cc4a039b769e42521bd14907d.nq.gz
    ├── 56e534176006f4b710d936cbe872755dccc0a2c7.nq.gz
    ├── 573271cb5d0cb83571564272895bddde9a5f6ad7.nq.gz
    ├── 5759499e95dde6ef99246ab00c21264192ff511c.nq.gz
    ├── 57664c7ea2bdd17681ccdabe9140eb043a99e155.nq.gz
    ├── 57a86d739d586e47e007d26de4542d6bdeced755.nq.gz
    ├── 5831f898b4a706accb2b828b6194b2974e78d0fc.nq.gz
    ├── 59a52e4394b5825d40a99e08793147fe836b4c19.nq.gz
    ├── 59f6dd3336e66065dc88b702e925965d4089c72f.nq.gz
    ├── 5abc77a591c7ee5d67cdf4dc4c4926c84894ba1d.nq.gz
    ├── 5b7b241de6f3285e0f127f3c0581c8c84de463e4.nq.gz
    ├── 5cbf1760d6afacde7709e8294de96bcd7d5f49e0.nq.gz
    ├── 5dcda7bf994db9f3f5c785d8dea824b3ab8e56a2.nq.gz
    ├── 5de37dee5e86e202c211464eaa08dd295dba44b2.nq.gz
    ├── 5fa77e4195ba3f50dd113b1a25cb2307cdc3218f.nq.gz
    ├── 5fe84e9f7c9fdac45db6210e2be9176b53e74536.nq.gz
    ├── 60874c66dbc37df824a9c44bb8c28a441f7f84e4.nq.gz
    ├── 6129bf49972233206b3c05daa2174f99723d1b9d.nq.gz
    ├── 622087ba7164fda53a70eb927b9258572b7c8ef0.nq.gz
    ├── 629872824d7c8f23542e3414f7faed71ea4efa93.nq.gz
    ├── 62f064b7473f4e6fec3ac50962240ac1f828753f.nq.gz
    ├── 63719fc4b85341de489fc0f73be82addf743807c.nq.gz
    ├── 63e233002ee60288acf206b7cfb22ac880758205.nq.gz
    ├── 655bdc60c772875e0a1ed871bd6bf02aab8e39cc.nq.gz
    ├── 66d2c4141a3c5520d568559aa0f70a3c670ee30a.nq.gz
    ├── 6736049fef688e0d663d6195c79ec9688dc4c5d7.nq.gz
    ├── 6757869d5a663738bd8c8321e22d491d3a92dbbf.nq.gz
    ├── 67bd8879641f8539f329e6ffb94f88d25e417244.nq.gz
    ├── 6811ef7699ab70fc63e33a07103d3c6d4e16970c.nq.gz
    ├── 68467a7237ca893aa79eb5b0acc9d159f7082968.nq.gz
    ├── 69958eece3671c9040c1f5561e724ca2d5f8e155.nq.gz
    ├── 6a32a0c1b79d42806e2ef1898f72ebb1e57ec9f1.nq.gz
    ├── 6abf91664dcf6d22850fdc971596b24a894cd487.nq.gz
    ├── 6bd445e4fce1a312949f222d54d230a1a622d726.nq.gz
    ├── 6be010b4508d6ba300a1305a1d405ec9a265ae07.nq.gz
    ├── 6d7f4b90c19d9fdcc3c895deb4101cf7acd7bd8e.nq.gz
    ├── 6dc712b3bcb4f8dd1018b175d3a4e7f59be3a990.nq.gz
    ├── 6e43a172ca7175b23c82f60894faf38ec6c437e3.nq.gz
    ├── 6ea250c812215f6726449c89b958bbde16bdc936.nq.gz
    └── 6f4eecc5144ac51a73122a641a60743be9aea05d.nq.gz

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

[open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
