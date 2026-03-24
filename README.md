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
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   ├── lsp
│   │   ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│   │   ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│   │   ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│   │   ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│   │   ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│   │   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   │   ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│   │   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   │   ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│   │   ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   │   ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│   │   ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│   │   ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│   │   ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│   │   ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│   │   └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
│   └── repolex
│       ├── 4dc19dc62abf432736f563c900668dc155ee7a8c.nq.gz
│       ├── 4fff7fe5b9afb0a8a1d3817893ca94a5e3a08d6d.nq.gz
│       ├── 55536dea2bc4bc567e7ce41880d2375d0381fa6c.nq.gz
│       ├── 5b33b5674749d8b85999be2a9aa16a990e648dd3.nq.gz
│       ├── 73fe2fba498bee59e98dd9230bb740c9a4ed9ea9.nq.gz
│       ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│       ├── 7de6da682c15867172715b88c7f4f0884b8e8101.nq.gz
│       ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│       ├── 96e8042212f6b943e68906bf7825b65d7476cb8d.nq.gz
│       ├── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│       ├── a3ab477aaa23f3b7ab7d62c7abc2cc74102ab2b8.nq.gz
│       ├── a8b74fff1c77f04a399134dfb417f199be0dca8f.nq.gz
│       ├── b07560bf97dad3a4266f6145bd4b662ac708ab00.nq.gz
│       ├── b5b633a8415de721b18e79bdf5d72a4973496fec.nq.gz
│       ├── f20bfa5882979da724241f06bcab075ec3411486.nq.gz
│       └── f6b8005077385271b0f58f0982bfaac113146cd1.nq.gz
└── blob
    ├── 00a21fe14e1a1207e9d8d2a506e2c7a71e909b27.nq.gz
    ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
    ├── 02580a0ca285f8e59cb4c6094faad9e7bb3b23f8.nq.gz
    ├── 02c67ab85418eb419b3109a662340e66f25b58d1.nq.gz
    ├── 030cb489008c46d7bafb2a0d15036109e36103ff.nq.gz
    ├── 03a13df6204ea179d325093aa504176eb6856342.nq.gz
    ├── 03a622c50adcfc0efd8dc4ae84bdc66c2a8055ce.nq.gz
    ├── 0433ff7661cc318b4116abfcb2f0a6dfaf1dcf86.nq.gz
    ├── 04ea8efb1367727b081dea87e63818be0a4d02f0.nq.gz
    ├── 06858e6802a34c5c5119eb9074ade415c7e6ba23.nq.gz
    ├── 0a4b3473d92a7cd9555c164ce1fac33cc7b88f34.nq.gz
    ├── 0ae1fe3b626b0981453f9c50f27f7fe622dfe43a.nq.gz
    ├── 0b69d14192e30a81b99862b05edd4eef24aa2f41.nq.gz
    ├── 0c0a530b936e7f0e83e5156a45c975cef3dffd10.nq.gz
    ├── 0d9ae7e1a45b82198c53548383a570d924993371.nq.gz
    ├── 0e02343c55fec206e4db175e73edda4a69e94d6a.nq.gz
    ├── 0e49a6aa333f768324235d293f86e7feb1aac154.nq.gz
    ├── 0f198ceba9e9b468dfa564855da7972908b74eee.nq.gz
    ├── 0f3d0f837d24834b9b5b0a6b735459c56f5e75c3.nq.gz
    ├── 100499365728b1723f21ad7d89d4b317864e76ff.nq.gz
    ├── 1036b2ad9d58a420ffe7b0c5cf94ee95ddfe443e.nq.gz
    ├── 10e84fa9497df93af19e771228fcf3fc380248a9.nq.gz
    ├── 11ae869eeecf9097a32a89621e19202f91c6416e.nq.gz
    ├── 11e3f2a5f0f9b8c7ef6affae8c543d20f7c112be.nq.gz
    ├── 120e4182f07dfedf3880198b2c160754c6689153.nq.gz
    ├── 121c36d4d00fbc5509c1f8df42c47c92b1901b72.nq.gz
    ├── 1286d4853717d66385122f11869804996298a894.nq.gz
    ├── 1330c04480a29c6fb0a78f135d3ab83350fe3f54.nq.gz
    ├── 141d6c08c8ec7248a98ac72c921fc54f823dc75c.nq.gz
    ├── 144589e499457482fadd078c574a4b166985ee90.nq.gz
    ├── 1648d8d1ae84f0b3a353c5894a9a1dfef9a7339c.nq.gz
    ├── 17577e67a930695f0896239d2aab572e9a7daa17.nq.gz
    ├── 178ed63f07658465c6100f1f0d041c97a9b6c7ef.nq.gz
    ├── 18a23ae758d00c34573672ce92ae556ad59b01f2.nq.gz
    ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
    ├── 1bd966fde28f20e277b44661cae3a7e1e4a80ac8.nq.gz
    ├── 1be9cbc1ba4b4b2f572f34f5eb07cfe7b11159e0.nq.gz
    ├── 1bf607d5544ea2cba4674901c070bdb1588671e0.nq.gz
    ├── 1c15151d6d896298dbfa1c6bf998be8db31f4d51.nq.gz
    ├── 1cccd3cb760503dde6a2b98453b589662b03c023.nq.gz
    ├── 1d23c7066e095b5bff2c373d4064dc4f33659783.nq.gz
    ├── 1d3d3d91de7e76a52f29f520231b020187ad6aa7.nq.gz
    ├── 1e42764102fdec5fbb7fbef9ec68cec2cc075eb5.nq.gz
    ├── 1e44ebf44622923e158a191708ddc28ae842c479.nq.gz
    ├── 1e6a2ebd38b68a923fdfecf685fb851572aa64a3.nq.gz
    ├── 1e7a89b847a68e7a6c8d0313574a686510ef4c40.nq.gz
    ├── 1ebacd105f1d2db543422032fe8ee86082185a4e.nq.gz
    ├── 1f40dd3bfaa9f373e1794b59f088945a5e3534da.nq.gz
    ├── 1fddb6ee4a60f30b4a4c4b3ad1f1604043f77981.nq.gz
    ├── 211dd9ccc530f5a3cee0598e097833040495347a.nq.gz
    ├── 2162143c30855eb7ec419b4a8696a37999d50be0.nq.gz
    ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
    ├── 219977cbb53b15ebb1c8894e840f9cd3c93bf04b.nq.gz
    ├── 21bf311e01ba41e2c379689a7eff3e008579add0.nq.gz
    ├── 21d23582194b8490084bcd65b06b6746c1d4beb0.nq.gz
    ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
    ├── 2399d3a7f02296de42be674130063301ad33a2f0.nq.gz
    ├── 23a7d265508b93dc79bae1d04286f2934541daca.nq.gz
    ├── 23eec62091f149de2e2ec784959017ca14213bcd.nq.gz
    ├── 26b1add9d190b2544fff04c507ca6d872d8f85a2.nq.gz
    ├── 26dfb3228b76d7737c02e0f1c791d287c09194ce.nq.gz
    ├── 26f420f059633345749c1b1e42b249f3077a51e1.nq.gz
    ├── 27261e7d5aa4273be40594cf28cdc38c24a03c99.nq.gz
    ├── 276df14df2228bdd676f5ef4256be66c20703aa4.nq.gz
    ├── 286b50c94685e41d6d8c6dd12970a4f080fcdfa4.nq.gz
    ├── 28bb8c07f19a292583b15f8e01d42cf7ee2d7a5e.nq.gz
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
    ├── 2f7ca78a1eb34f0f98feb07ab1231d077b248940.nq.gz
    ├── 30244d3e38072a2e6c97422644b5de359171e901.nq.gz
    ├── 3069174370995aedc6a352a11d9434d7d72c7b2a.nq.gz
    ├── 3076d7d8e9e9af9c660d4ac5ed69f75227489961.nq.gz
    ├── 30a22872e217432d6f0ed80026c0a18cd5e1c8c3.nq.gz
    ├── 317c3dbfc39db022d701cc39f2be67108636bc48.nq.gz
    ├── 323730ae29a3914bd6c4aa8f78c21e62e8bd7fa3.nq.gz
    ├── 3361183a419c188282a8545eaa8d8e298b8ffaab.nq.gz
    ├── 338b24134fea7feb46cd9f779540dc233062b8e4.nq.gz
    ├── 33f2ed7d3c51ba3111d2d9849faee810e3c810a1.nq.gz
    ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
    ├── 34167d9c75673e518ce0124947cf9bec9fd7f0f3.nq.gz
    ├── 344542cf345592b60579a4fd6686ea4eef19e2a0.nq.gz
    ├── 349ea50e7f03afcf0fd42dfdb776bf1b68ba6fae.nq.gz
    ├── 34de86c025284aa644742dc996012aeda8ee863a.nq.gz
    ├── 354d3d0d8dc04f5d1e56811968215ec7dbcca366.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 3602782dcacfa1e2059d9a584a46d5f1576e08b0.nq.gz
    ├── 360a232dd09e43114a50814b999f67351cdf9a24.nq.gz
    ├── 36dd0d268a38675381e75a873f373d8def093f85.nq.gz
    ├── 3705a8144947d4b0dd021f718ce62d5f2c5b83d5.nq.gz
    ├── 372d318097957c567c02fc387c96d81b15a6ba8b.nq.gz
    ├── 379e5c56405e526fa57ad5c4541695a81a32b245.nq.gz
    ├── 37bd721b836c8a90ee6d54c6aa2b03cd1c302739.nq.gz
    ├── 3896d4d38fbdde84e29f9a37ed8c32448553f882.nq.gz
    ├── 391a529e58f38cdda3966a3f056e13a0891e4661.nq.gz
    ├── 3ad6e46b15e25452f952bce448f65c90bc429ba0.nq.gz
    ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
    ├── 3c297568698963b1c04823241f4711ba5d6329d5.nq.gz
    ├── 3c33cef5450e1a6e12a4e33928cf2bdcdc4db2e0.nq.gz
    ├── 3d4154936b42522fac84900c689a901ac12875c0.nq.gz
    ├── 3db297ba8a88a07b5d0918146eae1c8778783ffd.nq.gz
    ├── 3f826421a1d97b09797fad3d781a666a39eb45c9.nq.gz
    ├── 3ff0dce32354ec16aeea5ba6ffeff6b8446ccfc0.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 40ce51fb550209b2a15a35aa8f9ccc8a3eeeda95.nq.gz
    ├── 40eb7fe7911376d90aac7bfed6b66f4479b406e8.nq.gz
    ├── 416a9dbe195acbfcef4a6479670e59f8f6072304.nq.gz
    ├── 41ec49ede535992da5a54e68c6ff0a8b882db8c4.nq.gz
    ├── 42b64340a0dfb441dac1c23068ffcc928776093c.nq.gz
    ├── 4317192d3cfff0454de9d31fbbf5ae453a31d6f7.nq.gz
    ├── 431ac41f6b41b744e2b6d9d6640d0bb678eaf801.nq.gz
    ├── 432594a958884bfafd47f7c5fb3e670ccc24bd63.nq.gz
    ├── 432dc0c03582948d197dbe0ce1273420bf68c4ed.nq.gz
    ├── 4357dbcae696fc141de1870ee07290445b22e25d.nq.gz
    ├── 4415805caeb97da286b945ba5f63b5720e436bfd.nq.gz
    ├── 4436c48fc57565f538256ed0838715d78a84289d.nq.gz
    ├── 44b82f29cc45d856e4b4682365cc218536b590a6.nq.gz
    ├── 458722c86b8f62061fca2a4a5bd161f9e39301ba.nq.gz
    ├── 45fdf33830123533459b17fbbf91735489fd6bd8.nq.gz
    ├── 464d68fe0e5e03f17be6bc67071b2df8db822d62.nq.gz
    ├── 468a42476036c9a706b099beda4715898a87eb32.nq.gz
    ├── 46eb4645321dc45be8fffb2d36e93136adfc4391.nq.gz
    ├── 47553b598140cf2f56607fa88784a0e665a18ff2.nq.gz
    ├── 4795e8612fb1fd46df88e6fc4b578c37848d1225.nq.gz
    ├── 47affdd2cf7cb9ac3fc135328c85c7f46a6d7711.nq.gz
    ├── 47df30e3e340888c1f3d379a2e46c26d6e63970b.nq.gz
    ├── 48a9f06b5b893afd1afca05d880273eb6cbaf941.nq.gz
    ├── 48f22e73332b613d894dd2f41655a1ee791e5e38.nq.gz
    ├── 4914b3ff58f712aa219e34237813c84706a51f0f.nq.gz
    ├── 4aab819e805575c65c8f24588efef4ce27224556.nq.gz
    ├── 4b8a36d249a05a0fe1575dc3d96ef7079dba6b07.nq.gz
    ├── 4bfffb7b1954841930cda063f98fe6b208c49381.nq.gz
    ├── 4c7642e5c591c26a776b81f0e490679c79f5e4d7.nq.gz
    ├── 4c7f6db275f3a24f5b551a07e023cb760aa25e57.nq.gz
    ├── 4cd77967ce2e35de206f61d9bcc950873835f3df.nq.gz
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4e0a5b7577d6e2699701fafc2e2a9f87164cbd0f.nq.gz
    ├── 4e19eea8b1a612f44242c406bd1bd79cd48d5f60.nq.gz
    ├── 4f75e068fe953cea48828ff408d0e36f7485b259.nq.gz
    ├── 504fa642b1eec2b971183c642fc23cf51cf068bd.nq.gz
    ├── 516386007f158662475f1611226e6e88126918db.nq.gz
    ├── 522b986b35140f39de7d739c4983429ae511eb90.nq.gz
    └── 523134e03dc9a7d7b8e6c11a85424e1b5a793486.nq.gz

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
*Parsed on 2026-03-24 by [repolex](https://repolex.ai)*
