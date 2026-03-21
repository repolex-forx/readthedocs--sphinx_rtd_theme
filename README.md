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
│   │   └── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   ├── lsp
│   │   └── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
│   └── repolex
│       └── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
├── blob
│   ├── 013e8a7d5d64eb788ebf1edd16046adda6c79a03.nq.gz
│   ├── 04ea8efb1367727b081dea87e63818be0a4d02f0.nq.gz
│   ├── 06858e6802a34c5c5119eb9074ade415c7e6ba23.nq.gz
│   ├── 0f3d0f837d24834b9b5b0a6b735459c56f5e75c3.nq.gz
│   ├── 100499365728b1723f21ad7d89d4b317864e76ff.nq.gz
│   ├── 1af45c81dea98e49c1603cf864ff227395b9a678.nq.gz
│   ├── 1c15151d6d896298dbfa1c6bf998be8db31f4d51.nq.gz
│   ├── 1d23c7066e095b5bff2c373d4064dc4f33659783.nq.gz
│   ├── 1ebacd105f1d2db543422032fe8ee86082185a4e.nq.gz
│   ├── 218fc996dceed50f74ec05fde23d7b259e847b27.nq.gz
│   ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
│   ├── 27261e7d5aa4273be40594cf28cdc38c24a03c99.nq.gz
│   ├── 276df14df2228bdd676f5ef4256be66c20703aa4.nq.gz
│   ├── 286b50c94685e41d6d8c6dd12970a4f080fcdfa4.nq.gz
│   ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
│   ├── 2d27e31f09ea5a66813aab1a75aa7c2a23d51a87.nq.gz
│   ├── 3076d7d8e9e9af9c660d4ac5ed69f75227489961.nq.gz
│   ├── 317c3dbfc39db022d701cc39f2be67108636bc48.nq.gz
│   ├── 354d3d0d8dc04f5d1e56811968215ec7dbcca366.nq.gz
│   ├── 3896d4d38fbdde84e29f9a37ed8c32448553f882.nq.gz
│   ├── 416a9dbe195acbfcef4a6479670e59f8f6072304.nq.gz
│   ├── 432dc0c03582948d197dbe0ce1273420bf68c4ed.nq.gz
│   ├── 46eb4645321dc45be8fffb2d36e93136adfc4391.nq.gz
│   ├── 47affdd2cf7cb9ac3fc135328c85c7f46a6d7711.nq.gz
│   ├── 47df30e3e340888c1f3d379a2e46c26d6e63970b.nq.gz
│   ├── 48a9f06b5b893afd1afca05d880273eb6cbaf941.nq.gz
│   ├── 4914b3ff58f712aa219e34237813c84706a51f0f.nq.gz
│   ├── 4aab819e805575c65c8f24588efef4ce27224556.nq.gz
│   ├── 4e0a5b7577d6e2699701fafc2e2a9f87164cbd0f.nq.gz
│   ├── 523dc2b8b868fa53e3b960d7017908dae486eecb.nq.gz
│   ├── 58579568545aafeae29905732d2774518401754a.nq.gz
│   ├── 58c9fef3a01c899867e280f49283fbb8e57d631d.nq.gz
│   ├── 5ad3e5063b0df9e659aeb587fd15b328bc282165.nq.gz
│   ├── 5e9db1660aef98a0499ec33426e41efb94826ffd.nq.gz
│   ├── 628b6a52a87e62c6f22426e17c01f6a303aa194e.nq.gz
│   ├── 6caa5d51b751612808b48b06b2e6780c61700636.nq.gz
│   ├── 6e7483cf61b490c08ed644d6ef802c69472eb247.nq.gz
│   ├── 74343694e2b2114272f38b1124813b972cb592e5.nq.gz
│   ├── 779c7db77c901fae68e23c700ecfa7b2f16bd976.nq.gz
│   ├── 7ba4d5257e258cb820c48f7bd8af0c68787ad865.nq.gz
│   ├── 7be93399a4f530da7eb43e2c214ec42cea89a6c3.nq.gz
│   ├── 7e17fb148c63fa9780c3dd65cef5b7593927ef62.nq.gz
│   ├── 7e7d0409b8237739c6f649fa9fed59bf3c2ec2ae.nq.gz
│   ├── 7eb74fd127ee5eddf3b95fee6a20dc1684b0963b.nq.gz
│   ├── 809c1f5828f86235347019a50e78b4b486a6a045.nq.gz
│   ├── 81c9ad949b47f64afeca5642ee2494b6e3147f44.nq.gz
│   ├── 84677bc0c5f37f1fac9d87548c4554b5c91717cf.nq.gz
│   ├── 86b378ae0395bddfa6faebd68a31d022506e607c.nq.gz
│   ├── 88ddcce25cef361552426e7288e24197b29a89ea.nq.gz
│   ├── 8b66187fe067c3aa389ce8c98108f349ceae159c.nq.gz
│   ├── 8c907fd422a22c2f016346a4e92561c0406be987.nq.gz
│   ├── 91d1754f6cb1b088f399458541ce3b1276c6fc91.nq.gz
│   ├── 921f0738833c4c1d3d7657bf2e1918d3cc5a21a5.nq.gz
│   ├── 96a3639cdde5e8ab459c6380e3b9524ee81641dc.nq.gz
│   ├── 96cc9d242954183002544136115365e032c7e49a.nq.gz
│   ├── 9bb8215b94b7a71cc80415d16b3635ff901f6210.nq.gz
│   ├── 9d07b87a9fbabf33346b4a3e5c580bc00ab0635d.nq.gz
│   ├── 9f2165c761a7ef39413fa5ea8f957475b2b05326.nq.gz
│   ├── 9fe5f191ecc8ba4ff80dc8618180c88ffa4b3d7d.nq.gz
│   ├── a2d7c0f133a8a0bff8b3951b25c252fcb13f7faa.nq.gz
│   ├── a2e633fc3483081fa5b985a1dead1ae9f16c82a4.nq.gz
│   ├── a4c48b301e1d3a694cb8be082ef13dfbb46ae80f.nq.gz
│   ├── a60876538bbc964d1e1d6e88f118d6f026471824.nq.gz
│   ├── a87ffba6bef48195c8cf4e3ccb42ea77034f7cbc.nq.gz
│   ├── ac708862f724da85c83667452d2c008b86db1be7.nq.gz
│   ├── ae73950a7cbf26705d78ed03b995e41b9d3875b3.nq.gz
│   ├── aeaf7b1748db577c8665238218a2073322eabf50.nq.gz
│   ├── af661a92365ad3372f06255b49ebea173a643c56.nq.gz
│   ├── b1f0c1b9fc04f0bbc99c35295e941b1b90e14554.nq.gz
│   ├── b8cdac3ac140b5129682573d4b5ca5f8e5a3c8f5.nq.gz
│   ├── bde7092786d5ef66320e02eebf1bb0ecfec7fcca.nq.gz
│   ├── c7322b749fba6e2e346c491d6ea889d105133db6.nq.gz
│   ├── c765d1e955d729a1c3421a50b17ebd97e67bc266.nq.gz
│   ├── c7b00d2ba8896fd29de846b19f89fcf0d56ad152.nq.gz
│   ├── d21228d1d0668d9073d57f8fba9828c7379db64b.nq.gz
│   ├── d4de13e832d567ff29c5b4e9561b8c370348cc9c.nq.gz
│   ├── d907b25ae60ec7e3d32e4027aa6e6b7595de97af.nq.gz
│   ├── d97a55eb3f6c60191425ae4b5a0c6b3373b17508.nq.gz
│   ├── dae4585e56fc3258ae312f50778c44e247e520ad.nq.gz
│   ├── df5d1df2730433013f41bf2698cbe249b075aa02.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ad0f39a4f6d33cd71e111544cc377da4df876f.nq.gz
│   ├── eaca81d8501054ae782443b743952660307e350f.nq.gz
│   ├── eb52a7907362cc3392eb74892883f5d9e260b638.nq.gz
│   ├── f221e50a2ef60738ba30932d834530cdfe55cb3e.nq.gz
│   ├── f265a80bdb08bfb1e58c0b4d7a05645f8cb81db3.nq.gz
│   ├── f65d47974786ee51c258f680bd9be621629244f5.nq.gz
│   ├── f700ffe0b88e23db3f224d83ba9272ab9b4cf8f5.nq.gz
│   ├── f7fcbdf46534e255d8a6e1fe74236cdc5168c6ae.nq.gz
│   ├── fc981ce7ad6c42d2384f0ef74b73174b9302ee65.nq.gz
│   ├── ffc84a7a309a1c23d80c95b99113518c5c73f977.nq.gz
│   └── fffdc6e0c4c6a82b34b69fac8354b4518e006e95.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
├── filetree
│   ├── 7a5b3f86d653fc68d40f037431a692aa26ee607c.nq.gz
│   ├── 84b5075f5b8a272b9a6d2689c551a947383bfda7.nq.gz
│   └── 9c5cee8529b87be298e6e8f2647a04fbbb94be53.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
