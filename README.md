# Repolex Knowledge Graph of huggingface/datatrove

RDF knowledge graph data for [huggingface/datatrove](https://github.com/huggingface/datatrove), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/datatrove
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 384d81c011fda5cf54be3ba1d58967c21fafe25d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 384d81c011fda5cf54be3ba1d58967c21fafe25d
│           └── chunk-001.nq.gz
└── blob
    ├── 002491473f8e5eb075533c3ad886722b93d8c25a.nq.gz
    ├── 01947048000a8e2904d2402b30c831735dede7e7.nq.gz
    ├── 03bda79d4fe928b31acc2f72405e7be0df4a1bd3.nq.gz
    ├── 04ead8c7d4a08eea288a2bf544d67061daa6906c.nq.gz
    ├── 065496a21c8669bb765e5711a710be65bc056039.nq.gz
    ├── 07038d30558de5c55c99219e738b47ae7066f926.nq.gz
    ├── 076b1252fcd62214a5bf00fa1b69c501ca75f260.nq.gz
    ├── 0876536e0e8349095c770fb6b0695e5739767d9a.nq.gz
    ├── 0a1c97f2a3ea3f0143563173217eaae23696ecdb.nq.gz
    ├── 0b0256ae4c90dd198e0027109bbec4594ed07fb2.nq.gz
    ├── 0ba14065d3181938ad36bbc2a21eaf3180974c6a.nq.gz
    ├── 0c86a0422eae6db148d81ad0bb02ffd067d40df1.nq.gz
    ├── 0c8ed021fcfe8dda7f3ac83fbab0dc1a9e95aa7e.nq.gz
    ├── 0f01af393a9bdd8b32aa6f6a590f94207c558f1f.nq.gz
    ├── 10c59ec3e5b3b624140b67d01f571ea9c6a6d88b.nq.gz
    ├── 139590bac2edc74727fcfd6370f71619bb1e9767.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 16e754c99937e9e66fb83d584e8d645a3dd04f64.nq.gz
    ├── 19df542cd671044f6ade387e6600707833c1d130.nq.gz
    ├── 1b084b810eff98b579ed5c96a891385b95e44d74.nq.gz
    ├── 1b9f0131ad26be2e7a32da3f7b0be23445b84403.nq.gz
    ├── 1e02755a3eabb79bc91784b8e4d2e1cd2862b56f.nq.gz
    ├── 1e19296e619cb72c6980a7db97be7c5fefac369a.nq.gz
    ├── 1e4bc484c49074526452380fa1b8e4d06ad9d005.nq.gz
    ├── 1e8adbd8a80b55883ed322a26dc9a74ba4470045.nq.gz
    ├── 1f3d895e31b66542b10583d31bd34fc5279e5d0f.nq.gz
    ├── 1fad1508a7ed25dc20e05d293613b243475c6182.nq.gz
    ├── 210d22f0494e6e623c587d882d97a0e2e061033b.nq.gz
    ├── 21337b9bc49bccbc9b6645cf9b2451b7c3f663a6.nq.gz
    ├── 216f9efded09a8720621836fdeb10a8b8e74d263.nq.gz
    ├── 21c0ec5b7005c8a9de7d8e98f4cc1222a612055b.nq.gz
    ├── 2238ab4f5824f1884d01c39a245f4d8c89b2d6d2.nq.gz
    ├── 233a48dbe254ff2947863d2935c3b204692233ae.nq.gz
    ├── 248c5a13550b6cdeab51fe1aa4b10fa0481e6fac.nq.gz
    ├── 2536324cf18337319817b42ce0a052356c5112c5.nq.gz
    ├── 260b4235db592b9f9a589a9f1da06a9bc847b895.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 269277883ee64289c674133c8f0f795ebb18607d.nq.gz
    ├── 28c9def700026fa35dff4d6ee697fff65dd9fefb.nq.gz
    ├── 2901e388207fdad195c98e8950d501312aad2541.nq.gz
    ├── 29359aa793d5edf00bf7fdd1a4df4222091af1cc.nq.gz
    ├── 2ab5298df1b6b53cd62af3efae75a6990604885b.nq.gz
    ├── 2ea91942fd79a5114943dcc568ef927e99925871.nq.gz
    ├── 30a1dd4138bb0d2119b2b708da889d3b92d7d4eb.nq.gz
    ├── 31a0e4061b8161f10e4b434dad2dda7afb6be515.nq.gz
    ├── 34e600490635fadb7b093f36c16cb498df2cea2b.nq.gz
    ├── 3526ac5a97167edc6d335726680e71cc74d30227.nq.gz
    ├── 366386f892731a34628227f3c9ca4df5f2fcac34.nq.gz
    ├── 36744e7551f3c5f34b783ead3ea5952a6b35ec40.nq.gz
    ├── 3684905675a10f21106b2905468d0d9c9f02b995.nq.gz
    ├── 36edddf6262ad94fb646524e802ac3081f9f497b.nq.gz
    ├── 37101364eb03538a58bafe76ac2708612b2d2b69.nq.gz
    ├── 3cf55d8b43990eedcdb7da41b7eb20055fd44836.nq.gz
    ├── 3d1b7a49b74a9aa139889fcadfbc14ea626ff568.nq.gz
    ├── 3f21993b3f21c483d27be4f8d58c29f61ef321bb.nq.gz
    ├── 44205ec78378ce6b837bdc882b273880f95de82d.nq.gz
    ├── 44d7c49b2a55dabfed25aa1c622b96f1dc64196b.nq.gz
    ├── 457455670f0317dace929f847776a249c677becf.nq.gz
    ├── 463e002d0ee4ef984391a5b9d3c255e11e1f4ff2.nq.gz
    ├── 47878cbd93cc62c79fa82a5bb4fc0aa262b349ff.nq.gz
    ├── 487ebba1d85863cbd0c75d143e83642c1b57c0ad.nq.gz
    ├── 4992265f4bfaa83d178ecf9916f2348081b12cd2.nq.gz
    ├── 4a05fc5df76995bbe41ea8c9e7939e23c712b989.nq.gz
    ├── 4a3b2986351899d48d9178c87e6dd0e74d187cfd.nq.gz
    ├── 4c0d4911ccabdc0a7633e9c3a2b5ac3f66b37902.nq.gz
    ├── 4c46e5c0e2eb9a25d9b9011fd33aae03fdf0ef72.nq.gz
    ├── 4cfe265f92a09750674bae2b593f459be9d318c3.nq.gz
    ├── 4cff7daa0a1596ee0586499d1f0d94182dde79c4.nq.gz
    ├── 4dce04be19308958ec8e26e0e2e1342126ab8ca7.nq.gz
    ├── 4dda1062417a0352c59047b296b16290272aec22.nq.gz
    ├── 4ecb936509d212838f455882e540aacd1916c76d.nq.gz
    ├── 4faf346d8ef7963454771eddee9a69fc95cb45cb.nq.gz
    ├── 52712754220141425bd386fb276aeb5480b33bec.nq.gz
    ├── 54fbd62e660a3f9930e65f3d983060eb44e6688f.nq.gz
    ├── 559931b006aede16ffd81f24e7b12d934fa04236.nq.gz
    ├── 55e8ec644d8eb8eec767fdbd074460b103787071.nq.gz
    ├── 56136a315a6239e60773fb2dc864fb1fff90a893.nq.gz
    ├── 58482a1b1d6a26224afdc18068e991328d4c88bb.nq.gz
    ├── 58555d8f902d62cdf570a72957cab5d6c2497d99.nq.gz
    ├── 58b2b4da150fbadbc2a3dc56fa2234fd86f9481d.nq.gz
    ├── 58da56a0fae5f794d3b699f7aaa74e9b17b1744b.nq.gz
    ├── 592a660ff1ed25a73d268885845afe45ea557986.nq.gz
    ├── 5b776ca4d47c40b16028430e5a04f48a000e1e68.nq.gz
    ├── 5f460e7d967438bc4a194e4f4f3f3b3aba6f1848.nq.gz
    ├── 5f540bb59bb2c14f3a506d07e55fff6837c26fcf.nq.gz
    ├── 5fe72de5d6c129d86343681f6277867bb8ee64ff.nq.gz
    ├── 604c591e65528f2df868afbcdaab32ff636f2110.nq.gz
    ├── 60a7c06f4a7ef1f0f246145d9c1b3794d7e78408.nq.gz
    ├── 610dc794971efeb402f0616dd8c34b458f8228ab.nq.gz
    ├── 615a58ec22d5b65d7c7be049de73f951cb6f6ddf.nq.gz
    ├── 65116334019d70a11a044ac6962b6740fa14c3d8.nq.gz
    ├── 65675dc4a87e98b0a89d1d35060a0ed8522fe162.nq.gz
    ├── 671c66e478aa02021048f99466bd32267efe449d.nq.gz
    ├── 68e94c764f1c597c3b91458993587791faae0e7f.nq.gz
    ├── 69651d0fd2f9ed984b65d3f46d961c6eac15e34a.nq.gz
    ├── 6a4b96ce095aed9dfa6f43ccecbf8ddcd0852ace.nq.gz
    ├── 6ce2b16a3dbda5f305538731197347f303cfb57b.nq.gz
    ├── 7218c520393d5ab0089faef7ab1a6e3e3842abd0.nq.gz
    ├── 7235745411f3c59199444671c417391a99e01fd1.nq.gz
    ├── 735244f0e8dfe2c180d050b1e66d478fa8a18b02.nq.gz
    ├── 736f63b76399efd08dc7db594c58c3281f2ec0f1.nq.gz
    ├── 764930efe7ea4332b04dfc4f42c8d63664376adb.nq.gz
    ├── 76ed30a22753bcb1ea8f10a7027ef33b32f43b76.nq.gz
    ├── 7894b56d543947e77593fc6ece571ef1f22766ef.nq.gz
    ├── 7ab7d3d4a1bedbe94b5542d96e901bccebc401f9.nq.gz
    ├── 7b6dd9e509cd36d7ecdb49c65381cca467166d09.nq.gz
    ├── 7b7d6c707f5d86011c49d6953668ea2479c2eb68.nq.gz
    ├── 7cb1c5f22b0ab9acd7f0792997a75893433cfecb.nq.gz
    ├── 7ee24d53c23c5e49961ffc73cf0c17158800c02f.nq.gz
    ├── 7ee90ae46c2eea05761e6343f67cedef899a48e2.nq.gz
    ├── 7fa51f164e742e43ff757a5e14824d16a613ad2f.nq.gz
    ├── 7fc6fe8240301c9112aeedc28bfd69de8e673b68.nq.gz
    ├── 7ff044bb11a0bffa12b0555ba33610967fddd279.nq.gz
    ├── 7ff45c8756c401bea5188a8473d5acf3949a4a53.nq.gz
    ├── 80578eea97858b667dd3c02ca3db9524afee0d58.nq.gz
    ├── 8081fc808da4da84ba7f215ca70e1d0bef410bb1.nq.gz
    ├── 843e2c5909a9b22caade5844ac739c6a65d75f05.nq.gz
    ├── 84709ebd14aedb9fbfddcdddfdec5642d46122f8.nq.gz
    ├── 848d5572d81af4254f2f755faf9c42ca95f9a2f4.nq.gz
    ├── 8559200de8f0637ef2e578353c2abf979dba72a2.nq.gz
    ├── 85d76bb308978b37a50e30d4f3cf37566e50d33a.nq.gz
    ├── 876bfa7d74e60eea50c60b6bd8c5995cb4353f6a.nq.gz
    ├── 88856a2f50e8ede10fa56c7f4b76beb2d9cd103b.nq.gz
    ├── 890a882891fee4f2f5bb85b3dd16fcf14234cf27.nq.gz
    ├── 8945b00d8d84440bd15d98532c2d1586b5d845d6.nq.gz
    ├── 897f3dd5284b80b85c904dc1f82da1984f36606c.nq.gz
    ├── 898c739999b9f285e37a842469f423857ce09235.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8cee638b2269661400cf9bc37e607191b44bac54.nq.gz
    ├── 918b29467d56f5c4060d870fb7b96857fa366e7f.nq.gz
    ├── 93471fc4d5d44f7723ca88f92b45a2182fa87e1f.nq.gz
    ├── 94f3c0ab4df45edf7b00a24203e1ea5392abeabb.nq.gz
    ├── 96188205d163d0398490d2099af8062fef29433f.nq.gz
    ├── 9620bd2f8e4778186ba86aafcbb3c9f2485c99ec.nq.gz
    ├── 972a438b515dc85b51b7469fd05718da2718e8a8.nq.gz
    ├── 9aa7f59e7a91414336f80c11902421b783c1ca73.nq.gz
    ├── 9adc11c44808a1f1c47f5a00e388d2bb4bf281be.nq.gz
    ├── 9b47d1dbdf91d2eb308fd211c6c9652ea0eb9dd2.nq.gz
    ├── 9bf169a1eae658f2ccefdc7013af81cb0370664b.nq.gz
    ├── 9f0c67f4c1fb3d10c0d9e3cd61b52b709d2c8f26.nq.gz
    ├── 9ff4b4a430579712ddd42da29d2730fa7326c2ae.nq.gz
    ├── a10ffbd31c39ffb010760773b7dbfcb5a59c40e7.nq.gz
    ├── a1b76b176bd0324a3f098d5f5160a175d08f999d.nq.gz
    ├── a1ee720a64bdacea40c9279bfc5dfb91df02b9c2.nq.gz
    ├── a228e5929c1784b74267265a93f817a0cff5d964.nq.gz
    ├── a38b4f97ef101796df5010b978093b08626e4abc.nq.gz
    ├── a42f6294298f47b4e54151d9327a58b2b5af6b89.nq.gz
    ├── a52a5873939895e9cd0c6715b0132ff439180bbe.nq.gz
    ├── a5bbaba41697f38732d4128a575005ed1c0749b1.nq.gz
    ├── a5f9c35ed4ef22339620ba239f05333be93d667f.nq.gz
    ├── a776f78ff3bb26fbdd915d1d56660076208215e3.nq.gz
    ├── a871e98057b077df87e307e1bdf4c709b2a211e3.nq.gz
    ├── ab832b27758a09dfdf0b6bb5b764bdcfba1b280a.nq.gz
    ├── aca0b24ca18f690142fe9ff9302dfda8b1b0cd11.nq.gz
    ├── ae0fda5c046d7ad1425ae0346711abf0c08930b9.nq.gz
    ├── ae268901ad7cdb39c260d77e0b0f6c6cea40ce93.nq.gz
    ├── af585260d02c2152cd9757cbc5336b9573343280.nq.gz
    ├── b024f1116ff640a375331fe67f02947550f7de17.nq.gz
    ├── b043a4a8fac6281874116d0bfa469fbc607b7ad3.nq.gz
    ├── b0a0aa7bb58bad6b3f95b31ef29dd8b3ce55d989.nq.gz
    ├── b117b8d5c8b3942af4a829b57e63a520bbcc4936.nq.gz
    ├── b22670c6561616ef011eeb55857e888f89bdb93f.nq.gz
    ├── b248dbde244e0a25f6d07b73a63d8889faf4fe9b.nq.gz
    ├── b2507077d23d74ef428b428e837a6e3a5cb4a953.nq.gz
    ├── b3054cd00f7ad4086f98bcf4a38f0da32c5cbec7.nq.gz
    ├── b48c020f51a7f1ea6dbbe9ab9a880dfa3b548be6.nq.gz
    ├── b892a07fb28af0e43938eed11c560e6583dd17e9.nq.gz
    ├── b9ee0d23032521873b748a46cca146ce6b64cc0b.nq.gz
    ├── bab07155de75195f8ddb8f69d24aa77245ea99f1.nq.gz
    ├── bc039c52663a10e8ad746300668381bb351df4ac.nq.gz
    ├── bebaddb8116458e93aae5872b47e5a1bcb1fb4d2.nq.gz
    ├── bec00ae7567ad23e31237d768d026cbdd812ce75.nq.gz
    ├── bfba43068b37ee682feb2a5c3d6f314da7bab844.nq.gz
    ├── c00160ff784a6370888afc83007d6e853fa07632.nq.gz
    ├── c0582459081dfbadab56cf9ab36fb9241694a339.nq.gz
    ├── c059d792624bfcf349109f983303177887b37565.nq.gz
    ├── c0ad956e21dc308c7321250db1de72da2379fd24.nq.gz
    ├── c14bab52fc38df645ccca9ab3a80ac801baecf08.nq.gz
    ├── c1ad05d2bdfbd0f8e2a9a865278d8ab607577e44.nq.gz
    ├── c27ac4fb74ad43eefb2a751bd75d3424088da23e.nq.gz
    ├── c328221fb5016198fad68fd08e7357027e7ee3e5.nq.gz
    ├── c4a09765b73dadae7b7c18eb4fa20309475aa054.nq.gz
    ├── c4f6f25f61fcfea8e479ad2a50bd229e4f09b9b9.nq.gz
    ├── c7d188580159994f23ceae79c6508bec23d69967.nq.gz
    ├── c944c9b4bccf2145ca0a179238d7f567d1dc09f5.nq.gz
    ├── cc269e1e223533b0384d2333d77b63c7a822f013.nq.gz
    ├── ccac663653fa072a7d70c7d32fc02ccc048671c4.nq.gz
    ├── cd2e735b136c767c89c837eaf21c7999053efe0e.nq.gz
    ├── cdcbe35030a5ad1186c78ab41c6fe1f3e6c992d9.nq.gz
    ├── cf381d4d638a091a5fbbe79724503595f66f099e.nq.gz
    ├── cf4d49f49dd04437eacb745206f5c1de9f775cfc.nq.gz
    ├── d3a0f6cf53d06ac2d589cae5ba06a4b319b2253a.nq.gz
    ├── d5193064378070ab8f513249e914570f2b4e0294.nq.gz
    ├── d99059e33daf1dbba8334bfd62103f0a7d632cb7.nq.gz
    ├── d9a565a43abe3acec12f3ff8879ee93212e63900.nq.gz
    ├── d9dcf15485b51d430a985fbe389d63847557d29f.nq.gz
    ├── da13a4ecf308d173fa0734cd9ac215ba1e1dc504.nq.gz
    └── dad66dc8ce8431e324631d36c289a91817a51679.nq.gz

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

[huggingface/datatrove](https://github.com/huggingface/datatrove)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
