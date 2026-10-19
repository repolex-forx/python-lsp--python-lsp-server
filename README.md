# Repolex Knowledge Graph of python-lsp/python-lsp-server

RDF knowledge graph data for [python-lsp/python-lsp-server](https://github.com/python-lsp/python-lsp-server), parsed by [repolex](https://repolex.ai).

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
rlex download python-lsp/python-lsp-server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3620069a607a63ed52569fde188e9301feae93a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3620069a607a63ed52569fde188e9301feae93a
│           └── chunk-001.nq.gz
├── blob
│   ├── 006f95a67ac3cbcb8a7717caeb6e0889d622c057.nq.gz
│   ├── 07be2aa46748e0ad5adbe9cf8d9dd19b09ee8f5a.nq.gz
│   ├── 0936e7833f8c8e0f70bba6cf58169c0678b4fc1d.nq.gz
│   ├── 0ce0e8cbe0761c5924f07e44ffb7d4c32e0b70bc.nq.gz
│   ├── 0e2cba2ed537c6bc8c16f87d3306b4c2b392e516.nq.gz
│   ├── 123ba4a878dcc84e01452c71d3ec6e503d1921a0.nq.gz
│   ├── 173b6005d2a6402e5c1c0e8ad767ec26acdb4c20.nq.gz
│   ├── 1d2568356984cfb98410bc92985bdc02b9fdfc3e.nq.gz
│   ├── 1d9115bf26ff6682288c983d66c7ee67a7eed3ef.nq.gz
│   ├── 1f0d34c895f6bcf012e315fafbd44528bfb57fea.nq.gz
│   ├── 211c4437f2fd596014980a909210d7b99f5c07d9.nq.gz
│   ├── 215258e119e55b6e409fbfcbd224a1c7bdc1b75d.nq.gz
│   ├── 242a38a1cf952ad58feebb753bfca1eb1b1288fc.nq.gz
│   ├── 258781f97c1a32c63f9c7568723b1dacde142a38.nq.gz
│   ├── 25d43a17bc36e342437e53241d859b9b1569b9d3.nq.gz
│   ├── 27b11f4531dcc2de1bb590542cbcda24193852ed.nq.gz
│   ├── 290b95ee6ae1262667d565ad611b85e66172d9e3.nq.gz
│   ├── 2b3491da5a923a33bcc256dfb126bc556801c4da.nq.gz
│   ├── 2c18c08a1707d61c5590f689e19e271627344d08.nq.gz
│   ├── 2d21bbcfa4f39feb03e24f60e334d0fb4102a073.nq.gz
│   ├── 349274be7deb12ae1cba750ca9f250fac500284e.nq.gz
│   ├── 383aaf1fecf156d92baaad56ea3f8447b1743647.nq.gz
│   ├── 3a7beb076b6e1d593912d63cc43a1eec8eff9042.nq.gz
│   ├── 41bac3985c61c24f5c55e34b4c2c37259eb35de8.nq.gz
│   ├── 41c7f54d4fcf01c4242289da3837b88df4020757.nq.gz
│   ├── 4966b89d20da496d5781f050dca484259139c49c.nq.gz
│   ├── 4c0d75e8698f288817b2eb927324aadcd314e397.nq.gz
│   ├── 51c3589ce538962ee024d6d76e470d09e6c793c7.nq.gz
│   ├── 52e7714351af63617a999fcb40faf4fd1167fdaa.nq.gz
│   ├── 58c60e1c7490d51b297cf39ec06b55d23b4266cf.nq.gz
│   ├── 5a24957b136a41cac6e1b47c5500418fb334037b.nq.gz
│   ├── 5a5a228dad14fcc75c3191bcbd193d18160e33a2.nq.gz
│   ├── 5d58dc559cd61ae8af6f4302dec267a2e29b28fe.nq.gz
│   ├── 5e278ee5105f5808c37360232076fd7f10929522.nq.gz
│   ├── 5fe0a8904ce517c7dd34d510bc3e05919db223f4.nq.gz
│   ├── 6dc565b96af324bb98c420c60a1b396b8dad6588.nq.gz
│   ├── 6f6cb19b8e5897f38d529f1924da660445594e04.nq.gz
│   ├── 72aa7404c6aeb55d29951ac713b53371019ee410.nq.gz
│   ├── 74258709295583917fa988989edae2309396b6b4.nq.gz
│   ├── 760f88298e660faaf7444deca2ba1e58fdc09403.nq.gz
│   ├── 762deb8ab646348c1b295be53d3e788c7c486f53.nq.gz
│   ├── 7a514adfd3dcfa43c260438d41634b3d1c5d4f35.nq.gz
│   ├── 7b201824a857880c0871b66eab02ad8d64c0210c.nq.gz
│   ├── 7b3f02ee90e57b786e9400d99deeac542ab37907.nq.gz
│   ├── 827c6271edc6b7505f48b1f2e5a1a5cb4c80e335.nq.gz
│   ├── 82a90fc2b7704faef8271dadab7bbfac616cafee.nq.gz
│   ├── 86987521b17f2435a3a9372ec33a838fcc499e13.nq.gz
│   ├── 893a5e98ea8ae1d2439905f90b9ac61630b187dc.nq.gz
│   ├── 8a04276c2b464efb0633f68f60a1e0902ba6da77.nq.gz
│   ├── 8ab36320b5fdfd6f1f1832d32bcd83fbcc97feb6.nq.gz
│   ├── 8b7bc1c15c6407b34eed6f64bb74669046ce7077.nq.gz
│   ├── 8ebd8e315efd765a3034ab519631ecfcf8f5bfff.nq.gz
│   ├── 8ffc8b71087e1d2a1c892dca3781126a50079f10.nq.gz
│   ├── 9b3621102bd8976f1db7f96d5fff17ca29703947.nq.gz
│   ├── a23d90364e848683c7b5773f84a6845a9b0bcefd.nq.gz
│   ├── a310ac8416675d49d07bc1d1fc8205a51cd1177b.nq.gz
│   ├── a40ffbbd30f57ef2f494126991d9c2c06ee31680.nq.gz
│   ├── a4c61b52453f8290ebb937a2fc95eac5a9b7af64.nq.gz
│   ├── a901051799482a40e0155b6864db185e2c943d91.nq.gz
│   ├── ad1dc4ffe73a24f90bc39db4becc1c3190ef83f8.nq.gz
│   ├── adae18504f3955a53f996df428b75904e8e7c0c0.nq.gz
│   ├── aff334957fc9b9a10576b58fb13f632f9518f389.nq.gz
│   ├── b0a71b88a6a6e22b8c6dc17eba8e80fccdaad634.nq.gz
│   ├── b35e321afd5c003054ac341e164f2d8351c90056.nq.gz
│   ├── b433fc63b2a7e7d2afd985266f029ba71d8b170e.nq.gz
│   ├── b4d511d04770c42edd2a46629e0dd9c8cbf4cd93.nq.gz
│   ├── b7b9daec377912d808b0fa701abfa021c7241d9b.nq.gz
│   ├── bbaeabe02841762d37aff75a3e0fd2a49be7e10c.nq.gz
│   ├── bdc072d4af510d35606ddab4c7d79c7c2f1b0382.nq.gz
│   ├── be51d20e0eccbdc39fd72f0fd6c130b8ac9a082a.nq.gz
│   ├── bf7b7086f262eab4d0f0f2f4c000e055f4c8d095.nq.gz
│   ├── c0a007599b9c0751ba9d1860936e7c07abbbcfa9.nq.gz
│   ├── c42d0fab14a5de86b4a48c52acf181b27ea3c6ec.nq.gz
│   ├── c4c12406e8cf2ae27b074ba9be66a4bfb8028bb1.nq.gz
│   ├── c9a473fee73fcee1b65b5cffe92d4d4f25f72edd.nq.gz
│   ├── cf97c7458bbc34b5d3e4de1bb31db5a635a20d2d.nq.gz
│   ├── d0eae1be0bba2d059567f221cad193cd2e4f3a91.nq.gz
│   ├── dc94ddea6a7dbf32b979bf8d8aed7cfe136862e2.nq.gz
│   ├── dc9cf16342d1d4badabe431adee4e5750b2ab7d0.nq.gz
│   ├── dcfd06abea8c713baa530451e5a6a37e6fb77b5e.nq.gz
│   ├── e14daa207a69e9d55205178ad9d9d888e70ba23b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b40121e93172ab0d2e5314dc255c3bf2a543fd.nq.gz
│   ├── eb5485bbd50ecd7c8565ad80fdccf2ba226b4046.nq.gz
│   ├── eb6e57df8e588ef4df19d9b92d0ccb8a56fd16dc.nq.gz
│   ├── ebcd9adb6697b8c0c777b7a23f4194266562436e.nq.gz
│   ├── ec072f1832bd6e155326ebc98cb7bdf0029e5258.nq.gz
│   ├── ed15a80241f078b470a3afd2b3c0e7926875431f.nq.gz
│   ├── eea0b7de232fb631b00a0b30f2239868c2ed6721.nq.gz
│   ├── f31d446ed80ba4d9837dcb7646d1dade86d5deb1.nq.gz
│   ├── f3415c8a4a6117deff78d7d7abb9b4ab73543332.nq.gz
│   ├── f363ad866e492a72a156da07b3283191b2cc22cd.nq.gz
│   ├── f4df0c2c7f827289889c0427cd3db52c431d5005.nq.gz
│   ├── f51216938caace52eded83e73fc021bed8c131ef.nq.gz
│   ├── f69541a482c13abfe0056cf9db74852f0dce5a2f.nq.gz
│   ├── fe35f067046d5181bd0d8e66cfd44d91dccf086b.nq.gz
│   └── fe36d8cb92b0195ee347a56af3df5aa813cba2a2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a3620069a607a63ed52569fde188e9301feae93a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[python-lsp/python-lsp-server](https://github.com/python-lsp/python-lsp-server)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
