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
│   │   ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│   │   ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│   │   ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   ├── lsp
│   │   ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│   │   ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│   │   ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   └── repolex
│       ├── 1671672602bbb86acac14d22f2ed5b80899c0e83.nq.gz
│       ├── 1df9968e3214aec0479f35ec734e5584677f453e.nq.gz
│       ├── 38c30bf8ac99f648aef15907c623648739f373de.nq.gz
│       ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│       ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│       ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│       ├── 5a16288abca8b797b9e04500965ca62595fdcfc9.nq.gz
│       ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│       ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│       ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│       ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│       ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│       ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│       ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│       ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│       ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│       ├── af3ff632f169b588f59012ad5e3f2187bb70d1f4.nq.gz
│       ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│       ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│       ├── c9b1bde560d8ee31400e4e4f92f2e8d7a42265ce.nq.gz
│       ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│       ├── f6554bfcbfc404db824e11608b1a91c275b3e3d3.nq.gz
│       └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
└── blob
    ├── 00430ef2b13e0b363325020cd80d2286a4cf1cfc.nq.gz
    ├── 00a21fe14e1a1207e9d8d2a506e2c7a71e909b27.nq.gz
    ├── 012e63fe6d75f6fec0c8bed10d706143b58e7617.nq.gz
    ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
    ├── 02580a0ca285f8e59cb4c6094faad9e7bb3b23f8.nq.gz
    ├── 02a927fcb88e584e93b4d8a39767b4b5307379d8.nq.gz
    ├── 02c67ab85418eb419b3109a662340e66f25b58d1.nq.gz
    ├── 030cb489008c46d7bafb2a0d15036109e36103ff.nq.gz
    ├── 03a13df6204ea179d325093aa504176eb6856342.nq.gz
    ├── 03a622c50adcfc0efd8dc4ae84bdc66c2a8055ce.nq.gz
    ├── 0433ff7661cc318b4116abfcb2f0a6dfaf1dcf86.nq.gz
    ├── 04ea8efb1367727b081dea87e63818be0a4d02f0.nq.gz
    ├── 06177d0ad928d51d201784b385d6f958b25d0840.nq.gz
    ├── 06858e6802a34c5c5119eb9074ade415c7e6ba23.nq.gz
    ├── 0686fdf0249205c87ad55bbd1432deb47df4618b.nq.gz
    ├── 06f282ce200356b962718dfd0239cf754915ce78.nq.gz
    ├── 0a4b3473d92a7cd9555c164ce1fac33cc7b88f34.nq.gz
    ├── 0ae1fe3b626b0981453f9c50f27f7fe622dfe43a.nq.gz
    ├── 0b69d14192e30a81b99862b05edd4eef24aa2f41.nq.gz
    ├── 0c0a530b936e7f0e83e5156a45c975cef3dffd10.nq.gz
    ├── 0d9ae7e1a45b82198c53548383a570d924993371.nq.gz
    ├── 0e02343c55fec206e4db175e73edda4a69e94d6a.nq.gz
    ├── 0e49a6aa333f768324235d293f86e7feb1aac154.nq.gz
    ├── 0ed467e4aa07a25e4cfe1b0f8a0a8a3b3ec09a60.nq.gz
    ├── 0f198ceba9e9b468dfa564855da7972908b74eee.nq.gz
    ├── 0f3d0f837d24834b9b5b0a6b735459c56f5e75c3.nq.gz
    ├── 100499365728b1723f21ad7d89d4b317864e76ff.nq.gz
    ├── 1036b2ad9d58a420ffe7b0c5cf94ee95ddfe443e.nq.gz
    ├── 1092287d9eaa5a3d705b24e9f4365730bb5338ab.nq.gz
    ├── 10cf73d16c3ccaddd92fe38b0647152396533e63.nq.gz
    ├── 10e84fa9497df93af19e771228fcf3fc380248a9.nq.gz
    ├── 111972519ffd498b7e098c1bc968cbe155483756.nq.gz
    ├── 113ea2d1ebf2024b008c01165ed21f6eb782408e.nq.gz
    ├── 11ae869eeecf9097a32a89621e19202f91c6416e.nq.gz
    ├── 11e3f2a5f0f9b8c7ef6affae8c543d20f7c112be.nq.gz
    ├── 120e4182f07dfedf3880198b2c160754c6689153.nq.gz
    ├── 121c36d4d00fbc5509c1f8df42c47c92b1901b72.nq.gz
    ├── 1285eb708bc105cc22cf08573d6503e001db5b52.nq.gz
    ├── 1286d4853717d66385122f11869804996298a894.nq.gz
    ├── 1330c04480a29c6fb0a78f135d3ab83350fe3f54.nq.gz
    ├── 139779c17bd86eadbd52d955afd1c88a51fec3ad.nq.gz
    ├── 141d6c08c8ec7248a98ac72c921fc54f823dc75c.nq.gz
    ├── 144589e499457482fadd078c574a4b166985ee90.nq.gz
    ├── 14ea694c332821789654cb1cc5ab074f2304aea4.nq.gz
    ├── 15c3a58ea50900a171e4ce310dcf368b593e30f7.nq.gz
    ├── 1622f8eefbb13138ae06288efea8766ce7011af5.nq.gz
    ├── 1648d8d1ae84f0b3a353c5894a9a1dfef9a7339c.nq.gz
    ├── 17577e67a930695f0896239d2aab572e9a7daa17.nq.gz
    ├── 178ed63f07658465c6100f1f0d041c97a9b6c7ef.nq.gz
    ├── 17e7436f74ec27b40e401a0cf12ce6044e08eb22.nq.gz
    ├── 18a23ae758d00c34573672ce92ae556ad59b01f2.nq.gz
    ├── 1a3679fac21f8b42b1f7bcc243dd9f2a7d755eed.nq.gz
    ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
    ├── 1bd966fde28f20e277b44661cae3a7e1e4a80ac8.nq.gz
    ├── 1be9cbc1ba4b4b2f572f34f5eb07cfe7b11159e0.nq.gz
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
    ├── 1fddb6ee4a60f30b4a4c4b3ad1f1604043f77981.nq.gz
    ├── 211dd9ccc530f5a3cee0598e097833040495347a.nq.gz
    ├── 2162143c30855eb7ec419b4a8696a37999d50be0.nq.gz
    ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
    ├── 219977cbb53b15ebb1c8894e840f9cd3c93bf04b.nq.gz
    ├── 219cf85066f2f817a4c32abcad94281f70112619.nq.gz
    ├── 21bf311e01ba41e2c379689a7eff3e008579add0.nq.gz
    ├── 21d23582194b8490084bcd65b06b6746c1d4beb0.nq.gz
    ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
    ├── 2399d3a7f02296de42be674130063301ad33a2f0.nq.gz
    ├── 23a7d265508b93dc79bae1d04286f2934541daca.nq.gz
    ├── 23a849a13768d990adb50edb9e119427f75d4a33.nq.gz
    ├── 23dd21b87d716ace6299599bb28cbc41a0495c2b.nq.gz
    ├── 23eec62091f149de2e2ec784959017ca14213bcd.nq.gz
    ├── 2606428e3f653ef97b36cf779e9077bbac82a283.nq.gz
    ├── 263040c2cd300802d0af988df109a9cb16d6837e.nq.gz
    ├── 26931c71bb3524a449e13a5f3a1e8383493042e2.nq.gz
    ├── 26b1add9d190b2544fff04c507ca6d872d8f85a2.nq.gz
    ├── 26dfb3228b76d7737c02e0f1c791d287c09194ce.nq.gz
    ├── 26f420f059633345749c1b1e42b249f3077a51e1.nq.gz
    ├── 27261e7d5aa4273be40594cf28cdc38c24a03c99.nq.gz
    ├── 274bfcc7a1a2fc3616f14d7405c527333e3ebf5f.nq.gz
    ├── 276df14df2228bdd676f5ef4256be66c20703aa4.nq.gz
    ├── 279380b25bb8e70bfe205d1f39bf056e8c0a685e.nq.gz
    ├── 286b50c94685e41d6d8c6dd12970a4f080fcdfa4.nq.gz
    ├── 28bb8c07f19a292583b15f8e01d42cf7ee2d7a5e.nq.gz
    ├── 29d53c10ed6468d13bfa9eb5f62ee4f4c9353a2a.nq.gz
    ├── 29f691d5ed0c2d3d224423bb0288e6bd59292511.nq.gz
    ├── 2a6d5ffac3d5f1fc06f969d77509b736217b922b.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2ab7e47242046e28b6143c680e968b849ef02ba1.nq.gz
    ├── 2b0941629bfb6b63ea40b16bc2104a79cfa3e2d4.nq.gz
    ├── 2bd1039e2d421af5894b4d7477a774529de2ba2d.nq.gz
    ├── 2be5a44cb6be6e77f848ccfc393370e3f43bee43.nq.gz
    ├── 2c1760e141ae797d7c27116790fe794742320b63.nq.gz
    ├── 2d14f23016d5509c5ebbe52dc78b9f0326377097.nq.gz
    ├── 2d27e31f09ea5a66813aab1a75aa7c2a23d51a87.nq.gz
    ├── 2ed49b7fae630b9ff9d802af0f211dcaf6d4e2af.nq.gz
    ├── 2ef56dbbc013e0af321b6f45105fb27743ae7abf.nq.gz
    ├── 2f3ee0645471e2a35acdbe8d6d2dee92e216afae.nq.gz
    ├── 2f7ca78a1eb34f0f98feb07ab1231d077b248940.nq.gz
    ├── 30244d3e38072a2e6c97422644b5de359171e901.nq.gz
    ├── 3069174370995aedc6a352a11d9434d7d72c7b2a.nq.gz
    ├── 3076d7d8e9e9af9c660d4ac5ed69f75227489961.nq.gz
    ├── 30a22872e217432d6f0ed80026c0a18cd5e1c8c3.nq.gz
    ├── 317c3dbfc39db022d701cc39f2be67108636bc48.nq.gz
    ├── 323730ae29a3914bd6c4aa8f78c21e62e8bd7fa3.nq.gz
    ├── 3247c8ba65229d1b86f2d3207a5bf148508229a8.nq.gz
    ├── 3361183a419c188282a8545eaa8d8e298b8ffaab.nq.gz
    ├── 338b24134fea7feb46cd9f779540dc233062b8e4.nq.gz
    ├── 33f2ed7d3c51ba3111d2d9849faee810e3c810a1.nq.gz
    ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
    ├── 34167d9c75673e518ce0124947cf9bec9fd7f0f3.nq.gz
    ├── 344542cf345592b60579a4fd6686ea4eef19e2a0.nq.gz
    ├── 349ea50e7f03afcf0fd42dfdb776bf1b68ba6fae.nq.gz
    ├── 34de86c025284aa644742dc996012aeda8ee863a.nq.gz
    ├── 354d3d0d8dc04f5d1e56811968215ec7dbcca366.nq.gz
    ├── 356006e44d3ecfa24450c5116958b3e3d0e4da15.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    └── 3602782dcacfa1e2059d9a584a46d5f1576e08b0.nq.gz

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
