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
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   ├── lsp
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   └── repolex
│       ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│       ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│       ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│       ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│       ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│       ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│       ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│       ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│       ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│       └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
└── blob
    ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
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
    ├── 1286d4853717d66385122f11869804996298a894.nq.gz
    ├── 141d6c08c8ec7248a98ac72c921fc54f823dc75c.nq.gz
    ├── 178ed63f07658465c6100f1f0d041c97a9b6c7ef.nq.gz
    ├── 18a23ae758d00c34573672ce92ae556ad59b01f2.nq.gz
    ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
    ├── 1c15151d6d896298dbfa1c6bf998be8db31f4d51.nq.gz
    ├── 1cccd3cb760503dde6a2b98453b589662b03c023.nq.gz
    ├── 1d23c7066e095b5bff2c373d4064dc4f33659783.nq.gz
    ├── 1d3d3d91de7e76a52f29f520231b020187ad6aa7.nq.gz
    ├── 1e6a2ebd38b68a923fdfecf685fb851572aa64a3.nq.gz
    ├── 1ebacd105f1d2db543422032fe8ee86082185a4e.nq.gz
    ├── 211dd9ccc530f5a3cee0598e097833040495347a.nq.gz
    ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
    ├── 21bf311e01ba41e2c379689a7eff3e008579add0.nq.gz
    ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
    ├── 23eec62091f149de2e2ec784959017ca14213bcd.nq.gz
    ├── 26b1add9d190b2544fff04c507ca6d872d8f85a2.nq.gz
    ├── 26f420f059633345749c1b1e42b249f3077a51e1.nq.gz
    ├── 27261e7d5aa4273be40594cf28cdc38c24a03c99.nq.gz
    ├── 276df14df2228bdd676f5ef4256be66c20703aa4.nq.gz
    ├── 286b50c94685e41d6d8c6dd12970a4f080fcdfa4.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2ab7e47242046e28b6143c680e968b849ef02ba1.nq.gz
    ├── 2d27e31f09ea5a66813aab1a75aa7c2a23d51a87.nq.gz
    ├── 2ed49b7fae630b9ff9d802af0f211dcaf6d4e2af.nq.gz
    ├── 3069174370995aedc6a352a11d9434d7d72c7b2a.nq.gz
    ├── 3076d7d8e9e9af9c660d4ac5ed69f75227489961.nq.gz
    ├── 317c3dbfc39db022d701cc39f2be67108636bc48.nq.gz
    ├── 323730ae29a3914bd6c4aa8f78c21e62e8bd7fa3.nq.gz
    ├── 349ea50e7f03afcf0fd42dfdb776bf1b68ba6fae.nq.gz
    ├── 354d3d0d8dc04f5d1e56811968215ec7dbcca366.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 3602782dcacfa1e2059d9a584a46d5f1576e08b0.nq.gz
    ├── 360a232dd09e43114a50814b999f67351cdf9a24.nq.gz
    ├── 36dd0d268a38675381e75a873f373d8def093f85.nq.gz
    ├── 37bd721b836c8a90ee6d54c6aa2b03cd1c302739.nq.gz
    ├── 3896d4d38fbdde84e29f9a37ed8c32448553f882.nq.gz
    ├── 3ad6e46b15e25452f952bce448f65c90bc429ba0.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 416a9dbe195acbfcef4a6479670e59f8f6072304.nq.gz
    ├── 41ec49ede535992da5a54e68c6ff0a8b882db8c4.nq.gz
    ├── 431ac41f6b41b744e2b6d9d6640d0bb678eaf801.nq.gz
    ├── 432594a958884bfafd47f7c5fb3e670ccc24bd63.nq.gz
    ├── 432dc0c03582948d197dbe0ce1273420bf68c4ed.nq.gz
    ├── 4415805caeb97da286b945ba5f63b5720e436bfd.nq.gz
    ├── 4436c48fc57565f538256ed0838715d78a84289d.nq.gz
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
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4e0a5b7577d6e2699701fafc2e2a9f87164cbd0f.nq.gz
    ├── 523dc2b8b868fa53e3b960d7017908dae486eecb.nq.gz
    ├── 524f9ddc7ea5729f4069f5751a947098c7ad8470.nq.gz
    ├── 563519cda58246ef3cc9f4bf1490073ef582ffc2.nq.gz
    ├── 57af405bc4df91e97e5c6246af3221a032b92cb7.nq.gz
    ├── 57b98fe6afd6cd15dce0bad8d9bb6e4a545edad5.nq.gz
    ├── 58579568545aafeae29905732d2774518401754a.nq.gz
    ├── 58c9fef3a01c899867e280f49283fbb8e57d631d.nq.gz
    ├── 592ccd20073f76a663c56fe0176397149782565c.nq.gz
    ├── 5ad3e5063b0df9e659aeb587fd15b328bc282165.nq.gz
    ├── 5ae5a075a56a65674e14ffaddcf157b7d8b3b788.nq.gz
    ├── 5d80641a1fb98aa97cc55e8fc921364fc861c5a1.nq.gz
    ├── 5e9db1660aef98a0499ec33426e41efb94826ffd.nq.gz
    ├── 6052fc0358649880cef8ffd6628efb706e1cc876.nq.gz
    ├── 626d1f45ef56f65dd05c6e1509bb37246fb0b5bc.nq.gz
    ├── 628b6a52a87e62c6f22426e17c01f6a303aa194e.nq.gz
    ├── 6362912b151c314bb6e2b622549ac4e89a55da30.nq.gz
    ├── 67c91bcec9663142afb91a032e868a6a4ac596f2.nq.gz
    ├── 6bb994e8396a4728a1f8debb01f59efd7590958d.nq.gz
    ├── 6c0d42c0ab4d508a0e20a5ec61c01645378efee5.nq.gz
    ├── 6caa5d51b751612808b48b06b2e6780c61700636.nq.gz
    ├── 6d4f729393525f27f4f8a9bb3f6765c9acdfa567.nq.gz
    ├── 6e7483cf61b490c08ed644d6ef802c69472eb247.nq.gz
    ├── 70a870f40ad0be24f2409f3875c8126b55aa41aa.nq.gz
    ├── 74343694e2b2114272f38b1124813b972cb592e5.nq.gz
    ├── 749e58f400cb7b4ba80526910d81424ef220e7be.nq.gz
    ├── 7608bc3e0fd03fc3cf3a41501ed9c1b49b773ac4.nq.gz
    ├── 779c7db77c901fae68e23c700ecfa7b2f16bd976.nq.gz
    ├── 79630b415dc245688dbd17adff78c63fbe8a2d42.nq.gz
    ├── 7b6b0df533de57a29e4765e90e58c7621c5bdb15.nq.gz
    ├── 7ba4d5257e258cb820c48f7bd8af0c68787ad865.nq.gz
    ├── 7be93399a4f530da7eb43e2c214ec42cea89a6c3.nq.gz
    ├── 7c79c6a6bc9a128a2a8eaffbe49a4338625fdbc2.nq.gz
    ├── 7e17fb148c63fa9780c3dd65cef5b7593927ef62.nq.gz
    ├── 7e7d0409b8237739c6f649fa9fed59bf3c2ec2ae.nq.gz
    ├── 7eb74fd127ee5eddf3b95fee6a20dc1684b0963b.nq.gz
    ├── 809c1f5828f86235347019a50e78b4b486a6a045.nq.gz
    ├── 81c9ad949b47f64afeca5642ee2494b6e3147f44.nq.gz
    ├── 84677bc0c5f37f1fac9d87548c4554b5c91717cf.nq.gz
    ├── 855c845e538b65548118279537a04eab2ec6ef0d.nq.gz
    ├── 86b378ae0395bddfa6faebd68a31d022506e607c.nq.gz
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
    ├── 95ddc52ae06c1cfe05616e5cb097bf67a316277f.nq.gz
    ├── 96a3639cdde5e8ab459c6380e3b9524ee81641dc.nq.gz
    ├── 96cc9d242954183002544136115365e032c7e49a.nq.gz
    ├── 99fde4e9e5deeec2ceac7db760891155b72c8901.nq.gz
    ├── 9addc8928edb6028d76782c30373c67b8fdc558f.nq.gz
    ├── 9bb8215b94b7a71cc80415d16b3635ff901f6210.nq.gz
    ├── 9d07b87a9fbabf33346b4a3e5c580bc00ab0635d.nq.gz
    ├── 9f2165c761a7ef39413fa5ea8f957475b2b05326.nq.gz
    ├── 9fe5f191ecc8ba4ff80dc8618180c88ffa4b3d7d.nq.gz
    ├── 9ff1cb9102b72ef8d24414748386624d7fb182b0.nq.gz
    ├── a085e7ff9384c825f7b73033302eee1c10e3ac54.nq.gz
    ├── a2d7c0f133a8a0bff8b3951b25c252fcb13f7faa.nq.gz
    ├── a2e633fc3483081fa5b985a1dead1ae9f16c82a4.nq.gz
    ├── a3001491e08135fee54f4078a665ab78e842d392.nq.gz
    ├── a302a9f0afc72e257cd378a0fff09a94f5b8a945.nq.gz
    ├── a323a352f680e636552b4afde26ca5326d9c460e.nq.gz
    ├── a3b8e33229be7db3b6cf59da16226b5c4d834373.nq.gz
    ├── a4c48b301e1d3a694cb8be082ef13dfbb46ae80f.nq.gz
    ├── a4c86caab63815840afef41c46feb3c5aabcd066.nq.gz
    ├── a60876538bbc964d1e1d6e88f118d6f026471824.nq.gz
    ├── a69c08db22d61a9f7e13dbf8adde531d0d0207e7.nq.gz
    ├── a7076081976d0ba0019f47b59cb7a907eae9d383.nq.gz
    ├── a7c153696893a1dda62211496cc8e8b0ded6aa73.nq.gz
    ├── a87ffba6bef48195c8cf4e3ccb42ea77034f7cbc.nq.gz
    ├── a9502bc1c30d319d8e1fd8b0d007ca351fec1821.nq.gz
    ├── aa01f3f4b7639fa08edecf85c9b822c35836f35a.nq.gz
    ├── aa1834ff1962a768759903fe63bdbf8e68c290d2.nq.gz
    ├── aa7b98831ace319caae3fcdef496185c408e2bcb.nq.gz
    ├── abdeb38669b0c279acc152ba4b1bfa30f47e9594.nq.gz
    ├── abe3749becbae42139be972ac001db3180b4d20b.nq.gz
    ├── ac708862f724da85c83667452d2c008b86db1be7.nq.gz
    ├── ad08a7fb940f722850e705133bbdaa831dc2c82d.nq.gz
    ├── ad690c1e738f39b15eb8357efa5fa0d1e1cf008d.nq.gz
    ├── ae73950a7cbf26705d78ed03b995e41b9d3875b3.nq.gz
    ├── aeaf7b1748db577c8665238218a2073322eabf50.nq.gz
    ├── aef99fcfc2f740b4f7797dc1ee8362748205c658.nq.gz
    ├── af2d4f013c4b724b4d485842c74157a7d4724a30.nq.gz
    ├── af661a92365ad3372f06255b49ebea173a643c56.nq.gz
    ├── af72fe1610817587a69205b2198fa57940345350.nq.gz
    ├── b09cc628bfc3d7612580b843aba11d9b19f0c239.nq.gz
    ├── b150cb44d952321868c3e18c7eae07e7ef273a9a.nq.gz
    ├── b1f0c1b9fc04f0bbc99c35295e941b1b90e14554.nq.gz
    ├── b49bc248ac775b240a420448dfef7ab815dcfd61.nq.gz
    ├── b71548b2af49e2aa08fa0982c55530f56d2aee19.nq.gz
    ├── b8cdac3ac140b5129682573d4b5ca5f8e5a3c8f5.nq.gz
    ├── bc934aa6696cf87504804b1c0e3589e78ae14f02.nq.gz
    ├── bccf2cd10a7fbe0b48517835cd8356a603e52118.nq.gz
    └── bd14ce719667c8828f8c0272e7ee232c4b369168.nq.gz

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
