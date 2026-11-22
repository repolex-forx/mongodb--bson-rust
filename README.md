# Repolex Knowledge Graph of mongodb/bson-rust

RDF knowledge graph data for [mongodb/bson-rust](https://github.com/mongodb/bson-rust), parsed by [repolex](https://repolex.ai).

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
rlex download mongodb/bson-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8b8bdd3ea4d8e22cdb68169d762d8facb1b12e73
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8b8bdd3ea4d8e22cdb68169d762d8facb1b12e73.nq.gz
│   └── repolex
│       └── 8b8bdd3ea4d8e22cdb68169d762d8facb1b12e73
│           └── chunk-001.nq.gz
├── blob
│   ├── 019c649c23da52094def23493d3b7a92380a667c.nq.gz
│   ├── 090d132f00e8b52f7bfd4252e3ca2de17fb8c731.nq.gz
│   ├── 0cc9900cf91f3ab833de3079343c54e89295f11e.nq.gz
│   ├── 0cd190b12bf48570fbfe5f2d71555afb410a7d26.nq.gz
│   ├── 113f5fdf3d1161f54a5b42688e70caada7ecfc54.nq.gz
│   ├── 1223a9bc03b61862430dd7cec4a9cc0092c06cbc.nq.gz
│   ├── 1743a4cb232937d7cd4ae81beec02cad6b700cca.nq.gz
│   ├── 17efdbf615d939ae2170925b501193d0dacfd9fe.nq.gz
│   ├── 18db60da4eb286ed62f1d58e22b2168175cb52c2.nq.gz
│   ├── 1feb373b1ae6b3dcdcd15eab3c4e5815fde8e4b3.nq.gz
│   ├── 26b59b2786e0f50e6e7bc0bc7be09d2cbd128775.nq.gz
│   ├── 27a01ff34b0266a769b2f6c51637d16b27ffeeda.nq.gz
│   ├── 28210a599dead0eccba5e17fdfe581ed836f51b4.nq.gz
│   ├── 29825ef6db955395e0edac0489c159fb3f4d401a.nq.gz
│   ├── 29891474804d3bf8bb78a742f81b206b6fa3b2c2.nq.gz
│   ├── 3037c4f5f5ca2da5f697842d52470398813b8deb.nq.gz
│   ├── 31230f12a31285894ec611d8b2052ea618bf6057.nq.gz
│   ├── 323dbd1840f459089db78008f298c77ba84c99c9.nq.gz
│   ├── 3506b96e0cc2207d1113a543395b88b06c7af87d.nq.gz
│   ├── 365138f5beb46fe393e23439389b4f0e67b574e0.nq.gz
│   ├── 37963dd271f556152dcd894b623f7ee6a9a9b7f1.nq.gz
│   ├── 3902aa10c9390973b7a0b10e66e4558abf87accd.nq.gz
│   ├── 3b11a6bebf1143be96a524d885630d902420aaa3.nq.gz
│   ├── 3c0d6c953a801323900b05203cf3f89b5eeff6de.nq.gz
│   ├── 3dc1b3345b85102dcb7b01b3a1d0cb4b71f3b49b.nq.gz
│   ├── 3e7e8e1824c363b0bdbece90f30e481c2adf35b1.nq.gz
│   ├── 3fd0db9524a2fc1013bdb3ca2ab08d2dcd33e693.nq.gz
│   ├── 40d6ec535163504590987bcbfa43782f132ed53c.nq.gz
│   ├── 40dc03fb92b17c43e4703bfab069007b39fd3bc0.nq.gz
│   ├── 4685b592701435895f795275eb88a87474432646.nq.gz
│   ├── 470ce15f0047ebe8e17e9fa68fb2b615ca6d5291.nq.gz
│   ├── 4995394d46b0eb03a64c9778e5cdd97d81141168.nq.gz
│   ├── 4a5ddd033e9a76efefbd6db6b0fd8b75619eabc5.nq.gz
│   ├── 4b5918ffb56d9b29998a0e5bcdd4fa0d5e11cddc.nq.gz
│   ├── 4bf1c6eecd121b82992054d7b6a0b55d9383a876.nq.gz
│   ├── 4c587e094a4c7757608014c5619a3b220fa4b4e9.nq.gz
│   ├── 4dd91d4c80dab2fc15c8fff34ed5df58fa66bb98.nq.gz
│   ├── 4de53932130d7a14d922f4bb4f8333087a0b5f7d.nq.gz
│   ├── 4f7d8666fb688cb4e3d8644ab53d676eca9699a7.nq.gz
│   ├── 534ffa4b4f27533e3f062e1cb19517d480b97539.nq.gz
│   ├── 55051b35f2752907083f1230ad0937946bb2d962.nq.gz
│   ├── 57c3c978710023ecbb5560931deb1b01dd328123.nq.gz
│   ├── 5ae88d996677d03943221077eab71cfd2fc6e835.nq.gz
│   ├── 5e0d79a20eba0c1a839378801c67d5f336b3e3a5.nq.gz
│   ├── 5ecba080e1649c342d5d72a2659c0bc6839f6b6f.nq.gz
│   ├── 6002f07d3357d735985622fbfca7afef0b52baa5.nq.gz
│   ├── 6174aea0e3aa2769bf67571f5b0f6e738e00b6fe.nq.gz
│   ├── 69b884783654e1c574e553312fe479f29c9b9eb4.nq.gz
│   ├── 6a88f3bd1b985fe8d5e9aea3cdda302d04197f05.nq.gz
│   ├── 6bc066c0ef36e27916443b831963aa9673b6eedd.nq.gz
│   ├── 6bd7bccd017cd7f8e1af0d40242162f183c2cd80.nq.gz
│   ├── 6c0124064b3cbf7d105a83605ec87985798ddc70.nq.gz
│   ├── 6c770d88730993d05b354c234e1ee2da5fc14244.nq.gz
│   ├── 6eadf15208fba5a9379ea59581306384e23c99bf.nq.gz
│   ├── 6f6115df5b51acfe3ed5e65b64b8d23d9c3d979a.nq.gz
│   ├── 71f2d7143750794fc9bfa7fe8afa42384a431929.nq.gz
│   ├── 724644b8b8e2bab4ee2c13e28c09296d175b2421.nq.gz
│   ├── 7381a2febf40c6ebc5b31d783713fd0017e662f4.nq.gz
│   ├── 7dece7ca2285f0a7984a3dd53e02c2f1397a87b7.nq.gz
│   ├── 85b3bed102de0a12a62d402b9d81256792e79844.nq.gz
│   ├── 8703effa34c71685639aa84bf2f153829002be10.nq.gz
│   ├── 8db13fcc9b7ae45b0c5692e9ea5ccdae8bdcf505.nq.gz
│   ├── 8ec2deada10d5bbbcc9868e2e4a21e615b15059a.nq.gz
│   ├── 92311d1db9f9debfc96684cce9e985dabd3fa7dd.nq.gz
│   ├── 92c37de6f0866f442aac58859e34b6d174927573.nq.gz
│   ├── 970e13afde33d65c9695a8206098075cde173a05.nq.gz
│   ├── 99063b2c290ae7b672a9fcdbe7aff16905863c9d.nq.gz
│   ├── 990b69097efcb312b7d74f46d093d2a57459d513.nq.gz
│   ├── 9a3e8c272b4db8b1b349e30ce67262f96d6396c8.nq.gz
│   ├── 9dc473b1f9ea325643739ca6b777236fddd43281.nq.gz
│   ├── 9e443d685a14d47326248f26162a952a08960ee6.nq.gz
│   ├── a53fbbe4e00f1350f86b824b9f017e2db828821a.nq.gz
│   ├── ab40eed140da624c6473b8b11b519153b27a3bb8.nq.gz
│   ├── ae773d9f13874adccec0988288ad943e4d220db5.nq.gz
│   ├── afe300f382701cf2e0f6627f928f3bdceeaa3657.nq.gz
│   ├── b53bfdc193fca2a3650737d82d0a1704deeb43e5.nq.gz
│   ├── b5aa383887474966c95a871d30635ce64bb99568.nq.gz
│   ├── b803fc87e66a27940ec5cf39c625cfd035d7bfd7.nq.gz
│   ├── b8516cf832d02098464cdd8acd228b7dd1540c0d.nq.gz
│   ├── bcf5ec1f7b0427956cabce569e2c4e4b50265967.nq.gz
│   ├── bd2c55920781d6199b3f4026b27a6b0975cd6aab.nq.gz
│   ├── bf9c8cb74d0518fcd71c6dfef3365ca01ee01648.nq.gz
│   ├── c37da5afaf83d07357fa7d5e5478edf5dc953767.nq.gz
│   ├── c38ed3b2e2121693b40561dd7d00a9ec4302706c.nq.gz
│   ├── c391e7f7b254ae2da228231f4519aa34ed389c8f.nq.gz
│   ├── cf4b82ed48002f88e21c1d73412e2f1c2f708e0e.nq.gz
│   ├── d5c3b8329eabb46297907fbdf7ba260b71c94e7e.nq.gz
│   ├── d67530dac5060c98f083e8e922bd18225f3b06f7.nq.gz
│   ├── d6a7f70f8661041deaa65b333843298a5756c323.nq.gz
│   ├── d6f79298f87713ca92b8c627449e518baa952878.nq.gz
│   ├── d8cd8ff8edeae9ac93f37a53b206cbaf5865271f.nq.gz
│   ├── db3930a0d6b8dfd32629b39092e36748454ca75e.nq.gz
│   ├── e39062c7445292ae365ac08224473c6cee081e32.nq.gz
│   ├── e44d1f7b889f266dec26f4bb147cb5db7fc723b0.nq.gz
│   ├── e62526ec61d42ee210cd3db4d6266ecb83ab7542.nq.gz
│   ├── e649519b265c1081be25c4360e29c8e0c942f416.nq.gz
│   ├── e69c24c8164cefda8cf7ef3ce5d8fd26c711b0ea.nq.gz
│   ├── e7611029cd8fd9f5f0283cf1851743cc6a8d1d65.nq.gz
│   ├── ea7060cfd696dfcb2a81a5a461225f122f08792b.nq.gz
│   ├── eb3da8b01e02916f7fbd23341ca2e40efef18d79.nq.gz
│   ├── ec5ec667053cba86ee867b74c2894c8b9aa80689.nq.gz
│   ├── ed6336842a6f1a99a56d453505d13ba2a3848795.nq.gz
│   ├── ef54d558349670f2605fdda33e8c6ac59dd864b0.nq.gz
│   ├── f4201c28f3f17dde1b0d2b2b5de0493f42f8fc75.nq.gz
│   ├── f52b0def120cd3781cd8ae0a073b1bdf7a1f12d8.nq.gz
│   ├── f579a59b59b1b0ce2c795603badae486b2e1e6e8.nq.gz
│   ├── f661cf4aa0d92d04f88fe18f637d4f58fb2b995f.nq.gz
│   ├── f6b0ae9566bfac01f5ed18311322f653843af595.nq.gz
│   ├── fa995ebe126877bf3a325e7a92fab00f5e7251ee.nq.gz
│   ├── fb53c2a7f06a0380ca4239a76895e8e81176856d.nq.gz
│   ├── fc5ef6dcdee9e9b8e8330edd616d3ca63dfd8de4.nq.gz
│   └── ffc82f4d4ed852ef6bd6618a6162f76f4bb2a4f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8b8bdd3ea4d8e22cdb68169d762d8facb1b12e73.nq.gz
├── filetree
│   └── 8b8bdd3ea4d8e22cdb68169d762d8facb1b12e73.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 122 files
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

[mongodb/bson-rust](https://github.com/mongodb/bson-rust)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
