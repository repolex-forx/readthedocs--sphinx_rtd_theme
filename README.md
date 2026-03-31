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
│   │   ├── 064b6c9f0515f1c1737262058cb64e093cd3ec86.nq.gz
│   │   ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│   │   ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│   │   ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 615eb528cc56721cfecce6ea8362e64401a2666c.nq.gz
│   │   ├── 6444ca893043d8a0ca704474f7cf7d5a148f6767.nq.gz
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9899ee4ee2f547f81e51297dc12317f018e62fdd.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a87790a4e27cd0a347db00ee9888f6b5d203dd58.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── c143f60f1eb510434c6c89361ca3621d3beb23fd.nq.gz
│   │   ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│   │   ├── ce20cfccca7d305c201bcecbe69b4298fd9c6c37.nq.gz
│   │   ├── f193a86b1b36a496a95bdff4971dfa1613af7357.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│   │   ├── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   │   └── f854c890e1445b99a43ac5f10463a5df83739a2e.nq.gz
│   ├── lsp
│   │   ├── 064b6c9f0515f1c1737262058cb64e093cd3ec86.nq.gz
│   │   ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│   │   ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│   │   ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 615eb528cc56721cfecce6ea8362e64401a2666c.nq.gz
│   │   ├── 6444ca893043d8a0ca704474f7cf7d5a148f6767.nq.gz
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9899ee4ee2f547f81e51297dc12317f018e62fdd.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a87790a4e27cd0a347db00ee9888f6b5d203dd58.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── c143f60f1eb510434c6c89361ca3621d3beb23fd.nq.gz
│   │   ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│   │   ├── ce20cfccca7d305c201bcecbe69b4298fd9c6c37.nq.gz
│   │   ├── f193a86b1b36a496a95bdff4971dfa1613af7357.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│   │   ├── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   │   └── f854c890e1445b99a43ac5f10463a5df83739a2e.nq.gz
│   └── repolex
│       ├── 064b6c9f0515f1c1737262058cb64e093cd3ec86.nq.gz
│       ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│       ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│       ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│       ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│       ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│       ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│       ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│       ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│       ├── 615eb528cc56721cfecce6ea8362e64401a2666c.nq.gz
│       ├── 6444ca893043d8a0ca704474f7cf7d5a148f6767.nq.gz
│       ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│       ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│       ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│       ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│       ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│       ├── 9899ee4ee2f547f81e51297dc12317f018e62fdd.nq.gz
│       ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│       ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│       ├── a87790a4e27cd0a347db00ee9888f6b5d203dd58.nq.gz
│       ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│       ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│       ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│       ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│       ├── c143f60f1eb510434c6c89361ca3621d3beb23fd.nq.gz
│       ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│       ├── ce20cfccca7d305c201bcecbe69b4298fd9c6c37.nq.gz
│       ├── f193a86b1b36a496a95bdff4971dfa1613af7357.nq.gz
│       ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│       ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│       ├── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│       └── f854c890e1445b99a43ac5f10463a5df83739a2e.nq.gz
└── blob
    ├── 00430ef2b13e0b363325020cd80d2286a4cf1cfc.nq.gz
    ├── 00a21fe14e1a1207e9d8d2a506e2c7a71e909b27.nq.gz
    ├── 012e63fe6d75f6fec0c8bed10d706143b58e7617.nq.gz
    ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
    ├── 02580a0ca285f8e59cb4c6094faad9e7bb3b23f8.nq.gz
    ├── 02a927fcb88e584e93b4d8a39767b4b5307379d8.nq.gz
    ├── 02c67ab85418eb419b3109a662340e66f25b58d1.nq.gz
    ├── 02ffa1cf8118d1d03a1d4148c12348edd8248897.nq.gz
    ├── 030cb489008c46d7bafb2a0d15036109e36103ff.nq.gz
    ├── 03a13df6204ea179d325093aa504176eb6856342.nq.gz
    ├── 03a622c50adcfc0efd8dc4ae84bdc66c2a8055ce.nq.gz
    ├── 0433ff7661cc318b4116abfcb2f0a6dfaf1dcf86.nq.gz
    ├── 04ea8efb1367727b081dea87e63818be0a4d02f0.nq.gz
    ├── 0559f04441e758fbb9ce1e0a94e220dd401ec6b9.nq.gz
    ├── 05f65b695a4530ee24115d90731dfee0deffdfe0.nq.gz
    ├── 06177d0ad928d51d201784b385d6f958b25d0840.nq.gz
    ├── 06858e6802a34c5c5119eb9074ade415c7e6ba23.nq.gz
    ├── 0686fdf0249205c87ad55bbd1432deb47df4618b.nq.gz
    ├── 06f282ce200356b962718dfd0239cf754915ce78.nq.gz
    ├── 086c9d6f380385f0de778869e5b90e30629ab674.nq.gz
    ├── 08cee9c2c450113595ce7534e27707b2ea0c46c8.nq.gz
    ├── 09a1af86db9062c3475b1f36d55676c904d3620d.nq.gz
    ├── 09b8b29737a832ffcf7a3a25dda33a85e901f26b.nq.gz
    ├── 0a4b3473d92a7cd9555c164ce1fac33cc7b88f34.nq.gz
    ├── 0ae1fe3b626b0981453f9c50f27f7fe622dfe43a.nq.gz
    ├── 0b2450257dc0fe4effec63a7762addd91bbe2dd2.nq.gz
    ├── 0b69d14192e30a81b99862b05edd4eef24aa2f41.nq.gz
    ├── 0b9752bc559f0c3611487485e678341a52474e84.nq.gz
    ├── 0c0a530b936e7f0e83e5156a45c975cef3dffd10.nq.gz
    ├── 0c8b8291728f4f45344c01c0f5fd4d15a27da0a2.nq.gz
    ├── 0c9e06c309fabb75ac38272b69d527fda44f2871.nq.gz
    ├── 0d3ad504400a042599db5ade75b6600e8f1129d9.nq.gz
    ├── 0d616e647954a082c43dbe227bb0d36203535874.nq.gz
    ├── 0d9ae7e1a45b82198c53548383a570d924993371.nq.gz
    ├── 0e02343c55fec206e4db175e73edda4a69e94d6a.nq.gz
    ├── 0e49a6aa333f768324235d293f86e7feb1aac154.nq.gz
    ├── 0ed467e4aa07a25e4cfe1b0f8a0a8a3b3ec09a60.nq.gz
    ├── 0f198ceba9e9b468dfa564855da7972908b74eee.nq.gz
    ├── 0f3d0f837d24834b9b5b0a6b735459c56f5e75c3.nq.gz
    ├── 100499365728b1723f21ad7d89d4b317864e76ff.nq.gz
    ├── 1036b2ad9d58a420ffe7b0c5cf94ee95ddfe443e.nq.gz
    ├── 1040b6830e4824f76faa88fbdcd0c344cf6d4bb0.nq.gz
    ├── 1092287d9eaa5a3d705b24e9f4365730bb5338ab.nq.gz
    ├── 10cf73d16c3ccaddd92fe38b0647152396533e63.nq.gz
    ├── 10e84fa9497df93af19e771228fcf3fc380248a9.nq.gz
    ├── 111972519ffd498b7e098c1bc968cbe155483756.nq.gz
    ├── 113ea2d1ebf2024b008c01165ed21f6eb782408e.nq.gz
    ├── 11ae869eeecf9097a32a89621e19202f91c6416e.nq.gz
    ├── 11e3f2a5f0f9b8c7ef6affae8c543d20f7c112be.nq.gz
    ├── 11eaa0e4d16131adf447f337dbb48253b38a7eba.nq.gz
    ├── 120e4182f07dfedf3880198b2c160754c6689153.nq.gz
    ├── 121c36d4d00fbc5509c1f8df42c47c92b1901b72.nq.gz
    ├── 125962a29c649fb96e886cc3d3e99905a30fab55.nq.gz
    ├── 1285eb708bc105cc22cf08573d6503e001db5b52.nq.gz
    ├── 1286d4853717d66385122f11869804996298a894.nq.gz
    ├── 1330c04480a29c6fb0a78f135d3ab83350fe3f54.nq.gz
    ├── 1365033f8b87be043f395676a3f87c0a340f9d50.nq.gz
    ├── 13703b4a91ff9878f62ccb137dcdc0ca10a89afe.nq.gz
    ├── 139779c17bd86eadbd52d955afd1c88a51fec3ad.nq.gz
    ├── 141d6c08c8ec7248a98ac72c921fc54f823dc75c.nq.gz
    ├── 144589e499457482fadd078c574a4b166985ee90.nq.gz
    ├── 14ea694c332821789654cb1cc5ab074f2304aea4.nq.gz
    ├── 15c3a58ea50900a171e4ce310dcf368b593e30f7.nq.gz
    ├── 15cafee269a6f681ee8974182fa59c7e9cd39edd.nq.gz
    ├── 1622f8eefbb13138ae06288efea8766ce7011af5.nq.gz
    ├── 1648d8d1ae84f0b3a353c5894a9a1dfef9a7339c.nq.gz
    ├── 17011ed8b7320179255ed9427fc03ee13039196b.nq.gz
    ├── 17577e67a930695f0896239d2aab572e9a7daa17.nq.gz
    ├── 178ed63f07658465c6100f1f0d041c97a9b6c7ef.nq.gz
    ├── 17b588d168f4ac7253d3934c5edba011fd549812.nq.gz
    ├── 17e7436f74ec27b40e401a0cf12ce6044e08eb22.nq.gz
    ├── 18a0549bcc32993d8d819317870b153a78b53f84.nq.gz
    ├── 18a23ae758d00c34573672ce92ae556ad59b01f2.nq.gz
    ├── 19a446a0e70027fc1c2499729def6191c4bbbb20.nq.gz
    ├── 1a3679fac21f8b42b1f7bcc243dd9f2a7d755eed.nq.gz
    ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
    ├── 1b2cfbe5a3d58435b69be0dfb86312bfc193e472.nq.gz
    ├── 1bd966fde28f20e277b44661cae3a7e1e4a80ac8.nq.gz
    ├── 1be9cbc1ba4b4b2f572f34f5eb07cfe7b11159e0.nq.gz
    ├── 1bef4d70f8e01054b16a49c14671713e9656c251.nq.gz
    ├── 1bf607d5544ea2cba4674901c070bdb1588671e0.nq.gz
    ├── 1c15151d6d896298dbfa1c6bf998be8db31f4d51.nq.gz
    ├── 1cccd3cb760503dde6a2b98453b589662b03c023.nq.gz
    ├── 1d23c7066e095b5bff2c373d4064dc4f33659783.nq.gz
    ├── 1d3d3d91de7e76a52f29f520231b020187ad6aa7.nq.gz
    ├── 1d58648fce5d2b80592991cb8afe4d06184e651d.nq.gz
    ├── 1e42764102fdec5fbb7fbef9ec68cec2cc075eb5.nq.gz
    ├── 1e44ebf44622923e158a191708ddc28ae842c479.nq.gz
    ├── 1e69ef18cd506d68712f1c548c53bf985ed18508.nq.gz
    ├── 1e6a2ebd38b68a923fdfecf685fb851572aa64a3.nq.gz
    ├── 1e7a89b847a68e7a6c8d0313574a686510ef4c40.nq.gz
    ├── 1e8839a040a3aefa742c886a66b9bd4f23f3aa02.nq.gz
    ├── 1ebacd105f1d2db543422032fe8ee86082185a4e.nq.gz
    ├── 1f2f7950ba2d0eae878e22e27a4e1eaecb19b6f9.nq.gz
    ├── 1f40dd3bfaa9f373e1794b59f088945a5e3534da.nq.gz
    ├── 1f7a8375bc82a13b2d3574401ed70628fac3bcd4.nq.gz
    ├── 1fb5be97d172e5c1d9823545c1aa474a0c97212c.nq.gz
    ├── 1fcc90055c03904a5070c73e2d4f9e3ff1e25c42.nq.gz
    ├── 1fddb6ee4a60f30b4a4c4b3ad1f1604043f77981.nq.gz
    ├── 200d9499cae2edc108fe75b45153f423ab4317d5.nq.gz
    ├── 211dd9ccc530f5a3cee0598e097833040495347a.nq.gz
    ├── 2162143c30855eb7ec419b4a8696a37999d50be0.nq.gz
    ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
    └── 219977cbb53b15ebb1c8894e840f9cd3c93bf04b.nq.gz

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
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
