# Repolex Knowledge Graph of sphinx-contrib/restbuilder

RDF knowledge graph data for [sphinx-contrib/restbuilder](https://github.com/sphinx-contrib/restbuilder), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/restbuilder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86c294f2b1b1e36c03a72bdd4062754c60dd005e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 86c294f2b1b1e36c03a72bdd4062754c60dd005e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a16d96229e976848797b0b94b2d1c67f002b73.nq.gz
│   ├── 00baebfe50d9e33dde983789914787be42244a16.nq.gz
│   ├── 01441ca867b515b34ee6e05d7ec93914ad173b6d.nq.gz
│   ├── 02a5632aea10664db93ea33aefd506d7328c5d0d.nq.gz
│   ├── 02d0276f75081c849e90009407b7267eadc1b8f5.nq.gz
│   ├── 0429324dbe7970c37b051c9234100dbed518591a.nq.gz
│   ├── 068dc8fee9f126761921b742774f20bcf110f6da.nq.gz
│   ├── 094be1f7d4be9175e47077dbadc29ca90caf687b.nq.gz
│   ├── 0adddd564a6e1f81a34043c29f18fe61922bedeb.nq.gz
│   ├── 0b50e236b959b275e00e7448917de375cd43baa2.nq.gz
│   ├── 0c043fc75fe0e86b4b190b87245394032aa9c869.nq.gz
│   ├── 0c673083df72a75f64fe625ab4c7ce06a7ee4ecf.nq.gz
│   ├── 0ce18645b28d05b86c8efde55a8e141981f0ada0.nq.gz
│   ├── 10798953a2ecdd0afce2b9401e48b80b82a96866.nq.gz
│   ├── 150a71589a8e7b56a91f02e2165a7269abbcc957.nq.gz
│   ├── 15551eb7d21d83bd57289331d54418bfe073649a.nq.gz
│   ├── 175b65ee04ee88c19140a65e776e98a973c415e6.nq.gz
│   ├── 1a39e4c1507b242445e2c32839c852870f0514b1.nq.gz
│   ├── 1ad6eb404b8978d296471c273b9b8f1e78e39389.nq.gz
│   ├── 1e6b06829c6e60e6808a05d5388346c8405a87b2.nq.gz
│   ├── 1fbab9e04e09b7a89361851c9580ee328a1b7944.nq.gz
│   ├── 1fdf159283e834d7f5e8da6575d0e6baadf68362.nq.gz
│   ├── 21d7cd1f8d7f3627f418ab83d5bb25c56a8449c3.nq.gz
│   ├── 22b229169f17daa1d22ac5c36a7b02ebbf1404d0.nq.gz
│   ├── 248fbedeaca10f30ce4f61fbd842e7a07668db5f.nq.gz
│   ├── 25fe5cb23ea59d1d553ac7376daaea4c053e2663.nq.gz
│   ├── 2a9c8cdc8bfa6c5d6f54f57d8ef18b6955f07bcf.nq.gz
│   ├── 2c5b32bb6bad4d414b755450ff51947090ca08f7.nq.gz
│   ├── 31904e113f86aefefcfee38ac2a8628f4be9ef0f.nq.gz
│   ├── 3250657b4beaeebc689f78dc30655a8a555dd8d3.nq.gz
│   ├── 33930091d443b814635fb2ae55ec1fc3fae75940.nq.gz
│   ├── 344fb344e60c2f5f9d742cf92cbda19de7c86fec.nq.gz
│   ├── 3501aa744efd704f2ec5e682d865493ac19eed32.nq.gz
│   ├── 367c1fe78514b01973cfd3e02c34d796665f997a.nq.gz
│   ├── 3685d339ed87043703ef42600854d315320a84ae.nq.gz
│   ├── 373c2373f69c0978555a1bab9344e0c62f1c5bf6.nq.gz
│   ├── 3a910f7a222634dd16203b0672c4d9289983b32c.nq.gz
│   ├── 3cebcd1d5edfa12148aef60054bcaee6ee7787f4.nq.gz
│   ├── 3d054df57b91c1219c9a2ca62a464ec128fda2e7.nq.gz
│   ├── 3d56493dd21d017520609aa283c3c65a11bbd534.nq.gz
│   ├── 3f5b719e8fca0c6f3443addd4b25ed1557b49bad.nq.gz
│   ├── 400666c800e019831e89d34f87252063c0f312cd.nq.gz
│   ├── 408e4d73d14e9baf1ca157306e79b6a5353420d4.nq.gz
│   ├── 43902c1d76dc7d34bf0c2c8bb74fb7e07c792199.nq.gz
│   ├── 49c6b89d8ab5f0ddbc00594fe06c2f0c84512e0f.nq.gz
│   ├── 4d132a21b05f64f04ffe2cf605bd7eb20eb14541.nq.gz
│   ├── 4f3bcc35b7f742e235fec01f4631abe5350d18dd.nq.gz
│   ├── 51c1486ab9e24d44f37bc38fa1c2aac1d74669fd.nq.gz
│   ├── 51fdbfb3996b29849d6da705a3f138b751e81f72.nq.gz
│   ├── 5332b6051f7ee4f187f93214f3cf4229b42527da.nq.gz
│   ├── 5477b42ad1d4ee34b0546fc3f14274609066d359.nq.gz
│   ├── 57b2b12ac653a66437d3ad3404a367e2a5b6eba4.nq.gz
│   ├── 58314ce964a18cb08022838c1bb8936fb67b93c6.nq.gz
│   ├── 5a0afbfbd587aaa6af063a5b706489a46a40fc0b.nq.gz
│   ├── 5aefb6722b7457c9875660f6f45832124d5d5247.nq.gz
│   ├── 5b14cc9315bae24a54e5ea1e6acf1d6fbdc90691.nq.gz
│   ├── 5b8bd2ea4796f2c13677d4dbfb4b39fb3af0382b.nq.gz
│   ├── 60fae8d120d6694f2c30661742dd2b1080e32a2c.nq.gz
│   ├── 631729b3b6708ec7bb8c5637b4f1a57a9b7d382d.nq.gz
│   ├── 68db97dd6ea3c9bf5f658412502ab67af3b0fb42.nq.gz
│   ├── 6951dd25ae90bc2b862000bb52439db9b6f2f967.nq.gz
│   ├── 6d7119c068ce4ce13aa5b0d2e0dca387940e99eb.nq.gz
│   ├── 6eb535b1bd40e455cd955167a2df5bc89d477ab7.nq.gz
│   ├── 6f2e509d449c39d7e70b28d7576331ce313ef782.nq.gz
│   ├── 70ace5a02f8d214f378ae84da001fbd43b4d4053.nq.gz
│   ├── 712e99ecc7246fd4767d02c9738a16b5296a31a0.nq.gz
│   ├── 72b2362d5098b0fbd80d66b22472754fff848897.nq.gz
│   ├── 75dfa541071c9f0a3f834eb68f0c9f53e57e32dd.nq.gz
│   ├── 75f8b779a9f35ae17e5e22f921762e9067f74f81.nq.gz
│   ├── 7669d5b8013d0189b51e160e2400e34f77b9f1ba.nq.gz
│   ├── 7739cb6bb514dcd6c37f8f277e76c4ae60535998.nq.gz
│   ├── 78c6f2f3edf8c04362cb276a79957923a5948eab.nq.gz
│   ├── 798bcedfecec39752bf6f4a909a1c3443046bb6b.nq.gz
│   ├── 7e9b56befd985536c29de0bce34620ae9b64bc6a.nq.gz
│   ├── 7ea8365b8e4d297299a23db67cd377bd87a02d66.nq.gz
│   ├── 82b116ae59fd341323af4af74615c5c4afdd64ab.nq.gz
│   ├── 82d37bdcfdcbbeb353ff8fbd42f2c92c960b1438.nq.gz
│   ├── 84f5b169e400dd4707557254548c630fd45ba7cb.nq.gz
│   ├── 855181319e5e393baacc8aaf144c2b959172633e.nq.gz
│   ├── 85d709c5346fcc0108aae5d1f656a64ee23d8e25.nq.gz
│   ├── 8851ac346b16fb4d02f75e71c7a299c533d6a88b.nq.gz
│   ├── 88d2e59a109c4a3ff9cead57db70a9ce0e2c9f67.nq.gz
│   ├── 8b8d4ab8194b7cadaf0254bf30f8e7d4d8ac535c.nq.gz
│   ├── 8c282f7a67423d5e4bae80c26fbf027fd87faf0f.nq.gz
│   ├── 90f7af7dd620e6799b924254dcfedbb55abda520.nq.gz
│   ├── 949904dac6631835fe88f303a61b5bd9f82d5c39.nq.gz
│   ├── 9ee512fdf36abfd955e01d76a2d6f6e76e53800d.nq.gz
│   ├── 9f89c33d8b63e7bf2f5fc79923edbcabc0434e17.nq.gz
│   ├── 9fb38c7999b6319098b75c0709c8b20df9886b78.nq.gz
│   ├── a07069ecfcaaee7edb7a0fac85fd1ae0f2b4fc3d.nq.gz
│   ├── a3085ed83e48285fe5c67a955528664be18ec30e.nq.gz
│   ├── b241f79a3eafddaf25aa33bc2bb8e57d1b614175.nq.gz
│   ├── b2bb8758ae02b46cfdf6109c98e3b1f7eb49339e.nq.gz
│   ├── b5a7dc29ef0f7f3593b1c61cfc5dfe8a17d3918c.nq.gz
│   ├── b622c9e44ee764fceaeaaa9f9f8e41da1e7baa48.nq.gz
│   ├── b7a7d245087404245eb39aac86fd317318b0a1bc.nq.gz
│   ├── b7d39f879b1a9b9d697f63636d07686a6fc33504.nq.gz
│   ├── b86e4a8f43c1f2dacb89baff57450ce301e68a14.nq.gz
│   ├── b8a2e458c20feff52b5fd7d5ffe1ebfae3e9ae2e.nq.gz
│   ├── b931ad91d2a573aaf289411503b9bfa49d6a3880.nq.gz
│   ├── bd31d835b63f2b2ab19fa2c31405603e1b89a0c1.nq.gz
│   ├── bf6ee7326d3f6ac51128ba19d8ef5f856e793fa4.nq.gz
│   ├── c2db7db78c37f75e84308e85650665f96a9ca284.nq.gz
│   ├── c44b897e47a81813ebd9231a3bd71cef22537e87.nq.gz
│   ├── c51b94a51684db41be031082381cbd96a1e5a644.nq.gz
│   ├── c551f6a305293e25a1296bcc21f9fcdba0ecbd3c.nq.gz
│   ├── c708b5c4dd984369ba57128ef8e868c5a334d8c7.nq.gz
│   ├── c7693e270764f021123a41aab3193fece13f52df.nq.gz
│   ├── caf8f6315a065b057dc8c6423b4e1300bf8af02c.nq.gz
│   ├── d194804532ec78748392027decf48db8045482e2.nq.gz
│   ├── d2812e5b19df135044665bd9b7f71e2f0e690b82.nq.gz
│   ├── d38dc36edeb0df9b80cd313c55a9caff5a3d5cab.nq.gz
│   ├── d64ce3d5f61cfad3431d7364543c97e8786f4b6d.nq.gz
│   ├── d8e25c5d291e13cd703a759e1e2713da8acc4c4e.nq.gz
│   ├── d984002ae4d257e35e7ba90b7a6aa15f703195de.nq.gz
│   ├── daa1a58fc6a2bd553100b97615e46ed4f3d051d2.nq.gz
│   ├── dc1958662754d18e01d136be7e73077ce5d3a398.nq.gz
│   ├── dc7430658a2ad6690db5356d169e1dfed7933ae2.nq.gz
│   ├── dcb22bfb628bb957d3eef7287b4652473c43af1d.nq.gz
│   ├── de09cb236aaf6457cee44c2a4245e1170cce2b75.nq.gz
│   ├── e00f0450ea6e31c674c2e6d0b8b16025a003928c.nq.gz
│   ├── e141d53aebf904ec827b863d5fca48a03fd532e1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8258300d98075abf8055c2611df482cab2285f1.nq.gz
│   ├── ee085be881695ce2b55a3676872dc5bae8396c32.nq.gz
│   ├── eee1ca62ed3e46f1f7a9eddaca1012607e0c3754.nq.gz
│   ├── f31a6707fdb1aacf8340f650b9126a147b1e1e62.nq.gz
│   ├── f3e35178aa9151bd30aff7866c8fc88a4b78fdb7.nq.gz
│   ├── f44d646dd766a9f8fb30c530fd3576c5eec9cbd5.nq.gz
│   ├── f55024d4846861f1ef91d0846acd0248771eec6a.nq.gz
│   ├── f63b31bc722a3135744e7e9c392dc2f0da1fdc8b.nq.gz
│   ├── f82cc147b3a2c96bb53d31a75dd73014baa5fe25.nq.gz
│   ├── f8859fcd2718cbc9ec38b3f28af9e45498d11f53.nq.gz
│   ├── faaba8c179b7b79759d177a1973c09ece3d66d8b.nq.gz
│   ├── face6d4cbc5a834b80634a869441dbfdc3056172.nq.gz
│   ├── fbf4930e53dd43970c50532db7716d9289a188b4.nq.gz
│   └── fce14e6754bf5c2d52fed782c9bb6348eddc7923.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 86c294f2b1b1e36c03a72bdd4062754c60dd005e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 145 files
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

[sphinx-contrib/restbuilder](https://github.com/sphinx-contrib/restbuilder)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
