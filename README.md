# Repolex Knowledge Graph of block/thread-manager-for-amp

RDF knowledge graph data for [block/thread-manager-for-amp](https://github.com/block/thread-manager-for-amp), parsed by [repolex](https://repolex.ai).

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
rlex download block/thread-manager-for-amp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 126cf2234a13a08a93d0d4cbd758a8fc77301d78
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 126cf2234a13a08a93d0d4cbd758a8fc77301d78.nq.gz
│   └── repolex
│       └── 126cf2234a13a08a93d0d4cbd758a8fc77301d78
│           └── chunk-001.nq.gz
└── blob
    ├── 010f7ba29efc7f13603f4c7d68e3569978b34225.nq.gz
    ├── 014594ce3587089362f6790dd4c0204d020891a1.nq.gz
    ├── 01b1b7f8f5f0d7e58ec18e1d62ef319c67335526.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 055ef420758f436af3e1c7f6ed431ddbef8140be.nq.gz
    ├── 0580bd161a3de96077ed13a39f052b6b00358a45.nq.gz
    ├── 05ed23fc3f8059a836585c23ad1dbd8c7b495b76.nq.gz
    ├── 081cbe83449cf8e625a3e2e79b6b35415c4e1503.nq.gz
    ├── 08a3ac9e1e5c44ce374f782d7c4fa3aa70e4c1ff.nq.gz
    ├── 0a257b6096ee713cb0f6498e3f4c71cc1bbc01ff.nq.gz
    ├── 0a82e1b9eefa1daf103b9f7cd293390b7ad7b60f.nq.gz
    ├── 0b5718c4d12603d953c84243e2624c27a4bc8b0f.nq.gz
    ├── 0b594bdfaa10e338c0b4ad64915d79fe09f1a40c.nq.gz
    ├── 0baaefa40782b56da369d9944f60595822b06d97.nq.gz
    ├── 0c26f61a86263dc8d476055e2188f0f7fe29fe3d.nq.gz
    ├── 0c6b73331ed894dba9f60a6a852e9045fe7504ab.nq.gz
    ├── 0ea7fa1e8c59633217d77fc82221a2eb9163b797.nq.gz
    ├── 0fff11ec9597c1b9df961896c403a2671c9ecfd6.nq.gz
    ├── 110977e00b6e864c9c94f6d816f71a1d78857b03.nq.gz
    ├── 11a5c961c01dbb6c8c9401323eea366e20818dd3.nq.gz
    ├── 11ad74bcf1f7a24db2bb7dd7f671558d0342d76b.nq.gz
    ├── 11d275378b3f73aafc14c1fbcda94b3fe58953d2.nq.gz
    ├── 128771e09ba9e27113022a3c35beccdd6807f692.nq.gz
    ├── 1559d279743d31924619849a58317b11a79ca0f7.nq.gz
    ├── 157679121167430d6a88e8fc5c8af1a88d6a2359.nq.gz
    ├── 1615dac9fd7e360b04a144f195fb889ca2d5397e.nq.gz
    ├── 164cece914a4b62be6b66b43887d3f49d9b1fa75.nq.gz
    ├── 194c5da8e63b8831713f8221a148369d17cfa445.nq.gz
    ├── 1a85c4c8a283dc39ecc8898376abd022394db8ad.nq.gz
    ├── 1a8b2b3503fee7dcf35a833f1a64ec0238182f21.nq.gz
    ├── 1a8ecb5192b61cd8544a2fcf770d9f6c80ef352f.nq.gz
    ├── 1ac375277c35d34716d48eaa57fec29bc6d39bf9.nq.gz
    ├── 1b9503075adf339c122e13046903da8e3dce3eb6.nq.gz
    ├── 1ca1482232bdeb755c06acf3cb7a58f23e9df72b.nq.gz
    ├── 1d8c73f278bd8bfd9bd5f42a58c411f6adccd022.nq.gz
    ├── 1ed71bb81dba1b1ef3986b65870aa7fb772bdd7f.nq.gz
    ├── 1feff4fbbf6a4d5608f81f948bc2976b55bcc02b.nq.gz
    ├── 1ffd2aa9f59ad98c7a663856ba78a50afc3184cb.nq.gz
    ├── 21a6f7df4f736c99813596b363f15228ff5b7a66.nq.gz
    ├── 21dc7935a62c8b5d5d8af3566557ed609711dcaf.nq.gz
    ├── 220d546eb6182e05efb965937962fec15a032157.nq.gz
    ├── 22ef07e1d11a1a2a1744eea84183d854ab4c70d5.nq.gz
    ├── 2312dc587f61186ccf0d627d678d851b9eef7b82.nq.gz
    ├── 261c811d502edc595432e30411ba63fbf110a496.nq.gz
    ├── 2696333e7f2fbd1316bd7f612d4a0b32e69d65b3.nq.gz
    ├── 27b64087896c692d3b71ef18b6ebb082f1ec75bc.nq.gz
    ├── 27d230ca3abf3391cf2e3192654b19cd284be244.nq.gz
    ├── 281badd234a8b505f2360f5d7a3171be6a6c9e1c.nq.gz
    ├── 29284c3dc9ab06d819ac3db71e949d24a4ec7828.nq.gz
    ├── 2983e37725ea2b405c737f99362eca4b8f10b9a9.nq.gz
    ├── 29af57244f1773343747609a674bcc92312300bf.nq.gz
    ├── 2b7772a9424265d01bd79d520f98dc476ea305e0.nq.gz
    ├── 2c32911a1f0a4e2cebf86f8947a8761f8ab0b6d9.nq.gz
    ├── 2c752481115b15942b8813de4aaf6714bdd8632f.nq.gz
    ├── 2d009a6495ea44a8acfb2d918c0108aeae9f0bba.nq.gz
    ├── 2e3ab6fc351dbd84e7121c062f5540efb346fdf0.nq.gz
    ├── 31be5d95830211c64240e193e3534cbc6ebf2669.nq.gz
    ├── 32f8c50de0cdbb7d55144a97453b8e8587475ecb.nq.gz
    ├── 338bf79b09aa4d5780e83bc1add1c4083d1edefc.nq.gz
    ├── 33ce9e3868fdaace458ea11c28df282e10ee3764.nq.gz
    ├── 354a37a457ff6fa6d694cc3844c5135a07d6551f.nq.gz
    ├── 36bb439fa904a71beddc2bf207ef5504c1461fba.nq.gz
    ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
    ├── 3932e7e96223c28b3f89fd1ece373b94283355b4.nq.gz
    ├── 39a66dabe1d6670e1b4bd45a0515a60bf7119c31.nq.gz
    ├── 3a9317a1581d52b710e06f34bfc07eb2fba01824.nq.gz
    ├── 3c231c782d2fe153d710667af3f911227e6cbb36.nq.gz
    ├── 3c5c221774b60df6e2e4727f38c23060a262f658.nq.gz
    ├── 3d362ac4c389616b713732d98c415a0bc3d8eb2d.nq.gz
    ├── 3f27ce5bdfe6559dcd923515fdf534ab710cd63a.nq.gz
    ├── 41631a840451a167f435e6a1bdc0013cfd007cc4.nq.gz
    ├── 419c731844f9a2ed501e593cc18ad62cd9ed721b.nq.gz
    ├── 424a622c01d458e58eaeb41dd58b92622e2217a3.nq.gz
    ├── 42556591f5303411790af54e304c14cf813aa8ec.nq.gz
    ├── 4291d5ca827b35b59dc6c683b639c1caea33d803.nq.gz
    ├── 434ad2f8963bcee0d6f0e97da1abbf3c790501f2.nq.gz
    ├── 446a30edfc8177a382351be3519a63504334ca05.nq.gz
    ├── 46ce2284022c04f5792949ac2672879edee757a7.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4928c66f3f97d62e92a3fc15bdaf7a2eb0e98924.nq.gz
    ├── 4a78ff9e6785a57e9cdd403f8e2e74d8a3d90ba2.nq.gz
    ├── 4a7ea3036a20398caf9a9daa984acb4a019f3090.nq.gz
    ├── 4b7283c13f1170a45c46e29a7c5a0a9c2e4c37b2.nq.gz
    ├── 4be5660cbe67e953c478e2c66233d03d5c4340d1.nq.gz
    ├── 4c921534d1e70715878d09d21bdd5fa6553bf447.nq.gz
    ├── 4cfab2c7ad5f6cef032e92187bf33762c218085e.nq.gz
    ├── 4e605c7125727501096e3ba5827ca3f4ac09d6a2.nq.gz
    ├── 4e70cd673dc4c986467bf766a010d68649a02efe.nq.gz
    ├── 4eaaf92f3e9f943e70223d9f943a77ece0ad3681.nq.gz
    ├── 4eedd815a953cd854005da2f5ed1f2c06cfb3c23.nq.gz
    ├── 5131e70162ba8da133a2eeb51181a402b6c30c22.nq.gz
    ├── 51ad7fd2bab210d322970d25737674c05a83b31b.nq.gz
    ├── 51fcf961eeb4c55528d7eecf5080a0121a4c937c.nq.gz
    ├── 52526dfce62e2112a5f97b01c4ffddf85e51c2a0.nq.gz
    ├── 5426f80c80b618aae383a40905d39fb24c04ef76.nq.gz
    ├── 57fd12cf05cf8c607ed057923f7743942f09a026.nq.gz
    ├── 5915a535571fddf7e5b5f27c6cc64ef88b98fcc6.nq.gz
    ├── 592783dd35a6c22d8394d88f995b7993573913af.nq.gz
    ├── 59ee0866b96cfbc7e51c50ca5616c5356d8c5efd.nq.gz
    ├── 5b551bf6da172518e11eefcb50a19739c9616041.nq.gz
    ├── 5efa4f1082d1d052ad8877b7c30594845cd5e438.nq.gz
    ├── 5f3841b2340f478247ad4ac57d37977be1651863.nq.gz
    ├── 6004878182a807333ad37baca8567a393bff8006.nq.gz
    ├── 60e5ee2281c942912c8468bbb452886b850dae7f.nq.gz
    ├── 62291f7cf71b513d0ec4d5da7181cfd3b02178d6.nq.gz
    ├── 62d36f23dc4525318083965a589716a0565f9c9c.nq.gz
    ├── 6319bd862a26d9b6718d8bcc846c4412dae9b0c5.nq.gz
    ├── 66bddb859ba35209965e7caee5e26a27c384f768.nq.gz
    ├── 66fbaf97db7438c0b38d76475d821c1e6895267f.nq.gz
    ├── 6930ee1b759b5c7c4786f4d17cfa0b3d09dba636.nq.gz
    ├── 69a14eeb89d56bb626a8279565c668100ae89faf.nq.gz
    ├── 69b298181a2bd43e1ee372a2136fd5af65d9ad17.nq.gz
    ├── 6a21a5ec41bcad6cbe5a85db5ef10bb77a39be02.nq.gz
    ├── 6aa57b28c0df70d7a7c8557a5d912b55d126a332.nq.gz
    ├── 6d52d7d3425f55f8c16cb89b76f7edbe8926f74a.nq.gz
    ├── 6d79208adbe6ce889eef9244b9647c85d0af536c.nq.gz
    ├── 6e5019bcd8bd91e0be6d5fc7d09bfb27e7057eec.nq.gz
    ├── 6ef2fe9be54ec2568b96483a62371f7568890688.nq.gz
    ├── 7088ea3b1f25ee672e6d36c5e0b338b128790376.nq.gz
    ├── 71bcf428a6c5dce7fd3d98b32d939a72786df2ce.nq.gz
    ├── 749502a3f01ce60cc04d655597261a9c1374a670.nq.gz
    ├── 74bbbd2cdd7808a05720ebbe30266b0c54f82cef.nq.gz
    ├── 7668c0bf4b25a5274ee80792fcfab8f6be2e54a8.nq.gz
    ├── 776d977964e1e406e68946d903664031336e015a.nq.gz
    ├── 788f3e8d9fbce5fe33f551e5b24509b000096b03.nq.gz
    ├── 7ad54d46ba3147b1feec618d3e19cc306ab19d35.nq.gz
    ├── 7ba2c6bde181ae8e3497bfd6406a976534393fa0.nq.gz
    ├── 7bae69a9065290f5018c8e90c05fe007cf2bf5c6.nq.gz
    ├── 7cd169e17bc8e4abf2c82429559c9214d60ff9d1.nq.gz
    ├── 7ebc132f92b3c2131d9bb9a487bf0c9acac49f76.nq.gz
    ├── 7f8cadfca3460d02217053ce2e903c5907134c82.nq.gz
    ├── 7fa32287716abe911ce0cc6b7067410dfab0dfa6.nq.gz
    ├── 8002834d7e5c44e787135a801bae8399b00e7350.nq.gz
    ├── 800bd3b30e98799042e6945c3bda565ae659a879.nq.gz
    ├── 806fde69dd47b82e119f5e12ec919a181fd18bdd.nq.gz
    ├── 81c5ebb98eac6fd867465d67fca27ae863118984.nq.gz
    ├── 833cf5c6c95887ecd0c5437a8ec2cf61a2e94b66.nq.gz
    ├── 844c1690aa2d61b7b888f85d3877a7df74ba9908.nq.gz
    ├── 85f00fef94c28e1ee7573df6e6dcaba6a07c4541.nq.gz
    ├── 87acaadba3d3a97cd17d084637a6cdd94caf2167.nq.gz
    ├── 88455fb39b67739b22ca636afd5422dfe2eca24f.nq.gz
    ├── 8894b6e2dddde7f710024a77b9be7051c3a99db4.nq.gz
    ├── 88e7fef73ce5b204b6f3873654051f345a3d341e.nq.gz
    ├── 89c1c47eaa4ab3c25abd28f95b99c35b41737d76.nq.gz
    ├── 8f5212b719a07ca3f08f6054d13d3e9283b67296.nq.gz
    ├── 8f6f7a019079892df5591c2d980b53cc14a6a4a0.nq.gz
    ├── 8fc42fe0f251b4cbaf7b605237c13cd100b052ce.nq.gz
    ├── 900563dace2fa13d582e63550171c0d38f0096d5.nq.gz
    ├── 9445f6d1e15857f57579f229cd72df713e2c8417.nq.gz
    ├── 96adb1c4e590d698e800a6a4ba745e9aef615ec5.nq.gz
    ├── 96edc713cac3dd42ec66cfb0c835ba1f88b64318.nq.gz
    ├── 97bb664dab26ca5f5d5a273f8eaa74cf5b6e93b4.nq.gz
    ├── 98b36116992eecdb3db9d8cf349a953cc20fa5a1.nq.gz
    ├── 9a6b2484e9e5d368cb4ffb4c535d72df10835135.nq.gz
    ├── 9b617eee3b675d67c382b1e930d664a6b61e7188.nq.gz
    ├── 9b817066a5b7fd74fa5cd6df64628b181e852941.nq.gz
    ├── 9bb339826fede790f4bebb893bd6b7b3fed581af.nq.gz
    ├── 9c25e134e72ef11b2e7d2da55500abb13baf7bca.nq.gz
    ├── 9c3bbdb9b81197f3a033b072ab068137ed648c5a.nq.gz
    ├── 9cb6674ca9438c40c096ad56fd32698bb8bc8cf5.nq.gz
    ├── 9df1326374b7c20fdef358d0f10963b996ed2041.nq.gz
    ├── 9ff6a93309df2ab5c5adc7183d68efc966eff96a.nq.gz
    ├── a04f413838218a9df4ce449fdf08e41eb1ca0f60.nq.gz
    ├── a230f9ad5daa743a76d7cd68df71ed72cdefa2cb.nq.gz
    ├── a25fb2a0dfc86f3bab957a766f548875b032e1a0.nq.gz
    ├── a275ea149cb4423af3cbe56af2dbd97d62937534.nq.gz
    ├── a2d0f289ae2bfa5fc95c6b02e3430791fb1a64c7.nq.gz
    ├── a539dd8deb5850fc5004836aae6240a2d5583493.nq.gz
    ├── a58486ef5158d7595bb07666bdb5064dad411326.nq.gz
    ├── a5d25b62a93a961dd7c49ddb940e99b2984bb33a.nq.gz
    ├── a60015997117f54557ad102539efa18f56401c21.nq.gz
    ├── a670457d9c5733eda6463dc3a453f9648880d2b5.nq.gz
    ├── a74544628e12cf541137cc150f2dfc85136dc719.nq.gz
    ├── a9380bfcaba2c5d85957b9150b6e1e4bd50f5be6.nq.gz
    ├── abcbdfc7ac5751fe7162b94e03995c91250d8dd6.nq.gz
    ├── acec939a999e59b1abcafca967411a27b81a5fd3.nq.gz
    ├── ad09809371a79369e03277351e4cbd7f3dea27e3.nq.gz
    ├── ad3d65e2256c9bbe35a6ea1a6d1f3f2ae25d2cce.nq.gz
    ├── afa8aefb3d005283c79f44edd56785a2dbbb855e.nq.gz
    ├── b1599ccc705dd1ff14c83bb21dfe41edd0eb9740.nq.gz
    ├── b186cd54257bed1f1874b6d72fd3c2967b6050cf.nq.gz
    ├── b1a5f93a4114d8217472b888aa112a854617526f.nq.gz
    ├── b20bedfe8fc67c0a1c837a2cba4724931146ba3c.nq.gz
    ├── b2c5b1472b2a0b1afe985e233af2c648e36f5070.nq.gz
    ├── b449c938dfa72fcd4d103fafd0538c1d428db2b4.nq.gz
    ├── b561075e0f1b1426118bf6e591ab69bbe681efa9.nq.gz
    ├── b5f4b8188ef0b5fa33125a1e794ce94507513f53.nq.gz
    ├── b645fc97ba2389627b97137ff874d9bdb837d1f0.nq.gz
    ├── b6ade4c6728f4b83eba27ec5f2848093f6a9cdab.nq.gz
    ├── b6e741b08e5f60a98d1f11c9017b8d5a7a7b746b.nq.gz
    ├── b70e437552658eab37258511748aef0cab40174e.nq.gz
    ├── b882c0b487636060ceb5bc9ef456c4511454ec59.nq.gz
    ├── b8a65a437fefc57c343e2307996b59859ccefb6e.nq.gz
    ├── b99fe19fbf0d99a8d0eabc38895a0585f6bd19b9.nq.gz
    ├── bb02c60cd055452852c33afe9078e35455935fb0.nq.gz
    ├── bb0f606a77046e6d65f92e22769c737aca9edbff.nq.gz
    └── bce83fc1af443784afa0090c77acb73b7bcd901a.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/thread-manager-for-amp](https://github.com/block/thread-manager-for-amp)

---
*Parsed on 2026-10-03 by [repolex](https://repolex.ai)*
