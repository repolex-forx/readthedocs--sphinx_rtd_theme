# Repolex Knowledge Graph of readthedocs/sphinx_rtd_theme

RDF knowledge graph data for [readthedocs/sphinx_rtd_theme](https://github.com/readthedocs/sphinx_rtd_theme), parsed by [repolex](https://repolex.ai).

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
lexq download readthedocs/sphinx_rtd_theme
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   ├── lsp
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   └── repolex
│       ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│       ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│       ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│       ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│       ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│       ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│       ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│       ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│       ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│       ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│       ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│       └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
└── blob
    ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
    ├── 030cb489008c46d7bafb2a0d15036109e36103ff.nq.gz
    ├── 03a13df6204ea179d325093aa504176eb6856342.nq.gz
    ├── 0433ff7661cc318b4116abfcb2f0a6dfaf1dcf86.nq.gz
    ├── 04ea8efb1367727b081dea87e63818be0a4d02f0.nq.gz
    ├── 06858e6802a34c5c5119eb9074ade415c7e6ba23.nq.gz
    ├── 0a4b3473d92a7cd9555c164ce1fac33cc7b88f34.nq.gz
    ├── 0e02343c55fec206e4db175e73edda4a69e94d6a.nq.gz
    ├── 0e49a6aa333f768324235d293f86e7feb1aac154.nq.gz
    ├── 0f198ceba9e9b468dfa564855da7972908b74eee.nq.gz
    ├── 0f3d0f837d24834b9b5b0a6b735459c56f5e75c3.nq.gz
    ├── 100499365728b1723f21ad7d89d4b317864e76ff.nq.gz
    ├── 11ae869eeecf9097a32a89621e19202f91c6416e.nq.gz
    ├── 11e3f2a5f0f9b8c7ef6affae8c543d20f7c112be.nq.gz
    ├── 1286d4853717d66385122f11869804996298a894.nq.gz
    ├── 141d6c08c8ec7248a98ac72c921fc54f823dc75c.nq.gz
    ├── 17577e67a930695f0896239d2aab572e9a7daa17.nq.gz
    ├── 178ed63f07658465c6100f1f0d041c97a9b6c7ef.nq.gz
    ├── 18a23ae758d00c34573672ce92ae556ad59b01f2.nq.gz
    ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
    ├── 1c15151d6d896298dbfa1c6bf998be8db31f4d51.nq.gz
    ├── 1cccd3cb760503dde6a2b98453b589662b03c023.nq.gz
    ├── 1d23c7066e095b5bff2c373d4064dc4f33659783.nq.gz
    ├── 1d3d3d91de7e76a52f29f520231b020187ad6aa7.nq.gz
    ├── 1e6a2ebd38b68a923fdfecf685fb851572aa64a3.nq.gz
    ├── 1ebacd105f1d2db543422032fe8ee86082185a4e.nq.gz
    ├── 1f40dd3bfaa9f373e1794b59f088945a5e3534da.nq.gz
    ├── 211dd9ccc530f5a3cee0598e097833040495347a.nq.gz
    ├── 2162143c30855eb7ec419b4a8696a37999d50be0.nq.gz
    ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
    ├── 21bf311e01ba41e2c379689a7eff3e008579add0.nq.gz
    ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
    ├── 2399d3a7f02296de42be674130063301ad33a2f0.nq.gz
    ├── 23eec62091f149de2e2ec784959017ca14213bcd.nq.gz
    ├── 26b1add9d190b2544fff04c507ca6d872d8f85a2.nq.gz
    ├── 26f420f059633345749c1b1e42b249f3077a51e1.nq.gz
    ├── 27261e7d5aa4273be40594cf28cdc38c24a03c99.nq.gz
    ├── 276df14df2228bdd676f5ef4256be66c20703aa4.nq.gz
    ├── 286b50c94685e41d6d8c6dd12970a4f080fcdfa4.nq.gz
    ├── 29f691d5ed0c2d3d224423bb0288e6bd59292511.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2ab7e47242046e28b6143c680e968b849ef02ba1.nq.gz
    ├── 2be5a44cb6be6e77f848ccfc393370e3f43bee43.nq.gz
    ├── 2d14f23016d5509c5ebbe52dc78b9f0326377097.nq.gz
    ├── 2d27e31f09ea5a66813aab1a75aa7c2a23d51a87.nq.gz
    ├── 2ed49b7fae630b9ff9d802af0f211dcaf6d4e2af.nq.gz
    ├── 2f7ca78a1eb34f0f98feb07ab1231d077b248940.nq.gz
    ├── 3069174370995aedc6a352a11d9434d7d72c7b2a.nq.gz
    ├── 3076d7d8e9e9af9c660d4ac5ed69f75227489961.nq.gz
    ├── 30a22872e217432d6f0ed80026c0a18cd5e1c8c3.nq.gz
    ├── 317c3dbfc39db022d701cc39f2be67108636bc48.nq.gz
    ├── 323730ae29a3914bd6c4aa8f78c21e62e8bd7fa3.nq.gz
    ├── 3361183a419c188282a8545eaa8d8e298b8ffaab.nq.gz
    ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
    ├── 349ea50e7f03afcf0fd42dfdb776bf1b68ba6fae.nq.gz
    ├── 354d3d0d8dc04f5d1e56811968215ec7dbcca366.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 3602782dcacfa1e2059d9a584a46d5f1576e08b0.nq.gz
    ├── 360a232dd09e43114a50814b999f67351cdf9a24.nq.gz
    ├── 36dd0d268a38675381e75a873f373d8def093f85.nq.gz
    ├── 37bd721b836c8a90ee6d54c6aa2b03cd1c302739.nq.gz
    ├── 3896d4d38fbdde84e29f9a37ed8c32448553f882.nq.gz
    ├── 3ad6e46b15e25452f952bce448f65c90bc429ba0.nq.gz
    ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
    ├── 3c297568698963b1c04823241f4711ba5d6329d5.nq.gz
    ├── 3c33cef5450e1a6e12a4e33928cf2bdcdc4db2e0.nq.gz
    ├── 3d4154936b42522fac84900c689a901ac12875c0.nq.gz
    ├── 3db297ba8a88a07b5d0918146eae1c8778783ffd.nq.gz
    ├── 3f826421a1d97b09797fad3d781a666a39eb45c9.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 40ce51fb550209b2a15a35aa8f9ccc8a3eeeda95.nq.gz
    ├── 416a9dbe195acbfcef4a6479670e59f8f6072304.nq.gz
    ├── 41ec49ede535992da5a54e68c6ff0a8b882db8c4.nq.gz
    ├── 431ac41f6b41b744e2b6d9d6640d0bb678eaf801.nq.gz
    ├── 432594a958884bfafd47f7c5fb3e670ccc24bd63.nq.gz
    ├── 432dc0c03582948d197dbe0ce1273420bf68c4ed.nq.gz
    ├── 4415805caeb97da286b945ba5f63b5720e436bfd.nq.gz
    ├── 4436c48fc57565f538256ed0838715d78a84289d.nq.gz
    ├── 458722c86b8f62061fca2a4a5bd161f9e39301ba.nq.gz
    ├── 45fdf33830123533459b17fbbf91735489fd6bd8.nq.gz
    ├── 468a42476036c9a706b099beda4715898a87eb32.nq.gz
    ├── 46eb4645321dc45be8fffb2d36e93136adfc4391.nq.gz
    ├── 47affdd2cf7cb9ac3fc135328c85c7f46a6d7711.nq.gz
    ├── 47df30e3e340888c1f3d379a2e46c26d6e63970b.nq.gz
    ├── 48a9f06b5b893afd1afca05d880273eb6cbaf941.nq.gz
    ├── 4914b3ff58f712aa219e34237813c84706a51f0f.nq.gz
    ├── 4aab819e805575c65c8f24588efef4ce27224556.nq.gz
    ├── 4b8a36d249a05a0fe1575dc3d96ef7079dba6b07.nq.gz
    ├── 4c7642e5c591c26a776b81f0e490679c79f5e4d7.nq.gz
    ├── 4cd77967ce2e35de206f61d9bcc950873835f3df.nq.gz
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4e0a5b7577d6e2699701fafc2e2a9f87164cbd0f.nq.gz
    ├── 523dc2b8b868fa53e3b960d7017908dae486eecb.nq.gz
    ├── 524f9ddc7ea5729f4069f5751a947098c7ad8470.nq.gz
    ├── 563519cda58246ef3cc9f4bf1490073ef582ffc2.nq.gz
    ├── 570abd245c53081b2dc81aa76fef7ce4ac44b99f.nq.gz
    ├── 57af405bc4df91e97e5c6246af3221a032b92cb7.nq.gz
    ├── 57b98fe6afd6cd15dce0bad8d9bb6e4a545edad5.nq.gz
    ├── 58579568545aafeae29905732d2774518401754a.nq.gz
    ├── 58c9fef3a01c899867e280f49283fbb8e57d631d.nq.gz
    ├── 592ccd20073f76a663c56fe0176397149782565c.nq.gz
    ├── 5ad3e5063b0df9e659aeb587fd15b328bc282165.nq.gz
    ├── 5ae5a075a56a65674e14ffaddcf157b7d8b3b788.nq.gz
    ├── 5d80641a1fb98aa97cc55e8fc921364fc861c5a1.nq.gz
    ├── 5db8595023e32d26b0ec1443f038c7885216529a.nq.gz
    ├── 5e9db1660aef98a0499ec33426e41efb94826ffd.nq.gz
    ├── 6052fc0358649880cef8ffd6628efb706e1cc876.nq.gz
    ├── 60eac2532ebf28b6c941cfa0e199b8f3aa276f2e.nq.gz
    ├── 626d1f45ef56f65dd05c6e1509bb37246fb0b5bc.nq.gz
    ├── 628b6a52a87e62c6f22426e17c01f6a303aa194e.nq.gz
    ├── 62bc0b75adb49dccbfb714754ef83181c0a7df73.nq.gz
    ├── 6361ad0f1dfecaf38e1ea33d831a8a3e29173440.nq.gz
    ├── 6362912b151c314bb6e2b622549ac4e89a55da30.nq.gz
    ├── 67387b775112611f3b87e8204fe996618ca661b9.nq.gz
    ├── 67c91bcec9663142afb91a032e868a6a4ac596f2.nq.gz
    ├── 6bb994e8396a4728a1f8debb01f59efd7590958d.nq.gz
    ├── 6c0d42c0ab4d508a0e20a5ec61c01645378efee5.nq.gz
    ├── 6caa5d51b751612808b48b06b2e6780c61700636.nq.gz
    ├── 6cb60000181dbd348963953ac8ac54afb46c63d5.nq.gz
    ├── 6d4f729393525f27f4f8a9bb3f6765c9acdfa567.nq.gz
    ├── 6e7483cf61b490c08ed644d6ef802c69472eb247.nq.gz
    ├── 7059e23142aae3d8bad6067fc734a6cffec779c9.nq.gz
    ├── 70a870f40ad0be24f2409f3875c8126b55aa41aa.nq.gz
    ├── 74343694e2b2114272f38b1124813b972cb592e5.nq.gz
    ├── 749e58f400cb7b4ba80526910d81424ef220e7be.nq.gz
    ├── 74decd9ebb8d805201934266b3bda6a9d5831024.nq.gz
    ├── 7608bc3e0fd03fc3cf3a41501ed9c1b49b773ac4.nq.gz
    ├── 76114bc03362242c3325ecda6ce6d02bb737880f.nq.gz
    ├── 779c7db77c901fae68e23c700ecfa7b2f16bd976.nq.gz
    ├── 79630b415dc245688dbd17adff78c63fbe8a2d42.nq.gz
    ├── 79dc8efed3447d6588baa2bb74122d56f3500038.nq.gz
    ├── 7b6b0df533de57a29e4765e90e58c7621c5bdb15.nq.gz
    ├── 7ba4d5257e258cb820c48f7bd8af0c68787ad865.nq.gz
    ├── 7be93399a4f530da7eb43e2c214ec42cea89a6c3.nq.gz
    ├── 7c79c6a6bc9a128a2a8eaffbe49a4338625fdbc2.nq.gz
    ├── 7c9b71a8542f2c9c3a35625a08d37a0b027e345e.nq.gz
    ├── 7e17fb148c63fa9780c3dd65cef5b7593927ef62.nq.gz
    ├── 7e7542dfa42152b8747c96d2ddb1a534184627c3.nq.gz
    ├── 7e7d0409b8237739c6f649fa9fed59bf3c2ec2ae.nq.gz
    ├── 7eb74fd127ee5eddf3b95fee6a20dc1684b0963b.nq.gz
    ├── 7f70473d828246f737c5dc3f9702b1403a0c31cb.nq.gz
    ├── 809c1f5828f86235347019a50e78b4b486a6a045.nq.gz
    ├── 81c9ad949b47f64afeca5642ee2494b6e3147f44.nq.gz
    ├── 84677bc0c5f37f1fac9d87548c4554b5c91717cf.nq.gz
    ├── 84c5c5f2d379b061c2b8c09fe0561941e64b2dd2.nq.gz
    ├── 8555d79b71a1a347857e06b8a6223df1ccdd7859.nq.gz
    ├── 855c845e538b65548118279537a04eab2ec6ef0d.nq.gz
    ├── 86b378ae0395bddfa6faebd68a31d022506e607c.nq.gz
    ├── 88ad05b9ff413055b4d4e89dd3eec1c193fa20c6.nq.gz
    ├── 88ae87159e1be46feebb98bf5ac9a217b460beeb.nq.gz
    ├── 88ddcce25cef361552426e7288e24197b29a89ea.nq.gz
    ├── 8b0f54e47e1d356dcf1496942a50e228e0f1ee14.nq.gz
    ├── 8b2a207134386312d979f5b332520b9d39ae7aff.nq.gz
    ├── 8b66187fe067c3aa389ce8c98108f349ceae159c.nq.gz
    ├── 8c1748aab7a790d510fb3f42a8a8971d96efa79d.nq.gz
    ├── 8c907fd422a22c2f016346a4e92561c0406be987.nq.gz
    ├── 91659ad41da2a6ea2ad9698b89cee6b1914537ae.nq.gz
    ├── 91d1754f6cb1b088f399458541ce3b1276c6fc91.nq.gz
    ├── 921f0738833c4c1d3d7657bf2e1918d3cc5a21a5.nq.gz
    ├── 9293dc164cf1e1a43a8b5c1a8101ff38f28a0ab8.nq.gz
    ├── 932c0056af996fdf3fc7c71c303d87cf239d2481.nq.gz
    ├── 933c399bfc76ce7a1941bab326076826a2e49735.nq.gz
    └── 93659f493092acf4211fb6654fc20e2d334ac744.nq.gz

6 directories, 200 files
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

[readthedocs/sphinx_rtd_theme](https://github.com/readthedocs/sphinx_rtd_theme)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
