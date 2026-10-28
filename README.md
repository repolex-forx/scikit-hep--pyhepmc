# Repolex Knowledge Graph of scikit-hep/pyhepmc

RDF knowledge graph data for [scikit-hep/pyhepmc](https://github.com/scikit-hep/pyhepmc), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/pyhepmc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7586c18781886906935405479f20f579f571450
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7586c18781886906935405479f20f579f571450
│           └── chunk-001.nq.gz
├── blob
│   ├── 06c077eff45132731859a76fa01101c78e1ae0c5.nq.gz
│   ├── 081941ec32f4d845fe4028b97c3e77bdbb704bbe.nq.gz
│   ├── 083920f0664186d7b4d8b2c0e41ba7e48bd3f7a3.nq.gz
│   ├── 0a0572304399949def31331cfe4aa52cf14aefac.nq.gz
│   ├── 0abf699c04fcad45ef8d5c7818dfd9491021d591.nq.gz
│   ├── 0ddb042d199c84dbc018b0ddf8b9aee996d6adf4.nq.gz
│   ├── 125f048b1621e10cc81663946d6f725edb7ec826.nq.gz
│   ├── 18534ff9e8bec8079c6da702b5c5539d1fb1d00d.nq.gz
│   ├── 1d65b1daaa63e6dda676f7b4df1316916231d635.nq.gz
│   ├── 20c0b15baed3e1c9d65832c7ad81cb46e9ffafe9.nq.gz
│   ├── 22be66fa9f20580e2cb92ef237ae8991d719d467.nq.gz
│   ├── 25ef398530158371c5bbd6b8e3a0ec5b50329e3d.nq.gz
│   ├── 28b3ec7dbb1829a3fae2d74ce5fa6a7134e4995a.nq.gz
│   ├── 2a7d36f8fb6dda224e4d1224821dfc3509a1ca40.nq.gz
│   ├── 2e21988e2ed5961640bb5879c2f771920842b2aa.nq.gz
│   ├── 2e6ea91ff7907b87e139c16c8181b74bad0450af.nq.gz
│   ├── 30eadc65917156fa8082681df9c09bc1d5d07472.nq.gz
│   ├── 312a9bab1843fbedd6de5be112de42b1416666df.nq.gz
│   ├── 318a35733482448e94fb69f115e9101ce4fb86b7.nq.gz
│   ├── 33b88957b23e39f85b1018c1a9409e45badf5dac.nq.gz
│   ├── 35e18fd8d8de34738c7439c1e64089101e25816f.nq.gz
│   ├── 368b2282bdca542dfc4b941effe505d08c0ab563.nq.gz
│   ├── 36a14554b6647db8117cef9a34fd34211fbefa9e.nq.gz
│   ├── 36db10a178f0557a61e8137450100aa5d568716f.nq.gz
│   ├── 3845fab4c4d1911a0d285489ba516bc4bad74db2.nq.gz
│   ├── 3c4475dd0071c5a9d8064a9cb24548f8e3d8b393.nq.gz
│   ├── 3de37cb9be22631ee0593d3f3dbce3bf9f2e686a.nq.gz
│   ├── 3e863005090e42894d518818b8ac17e857bae74b.nq.gz
│   ├── 40e746240a1bf399194546e28c76544f054e840a.nq.gz
│   ├── 416be023b70966f11d21c1afe9248ebd89654ecb.nq.gz
│   ├── 4177070b429a3efb01534fe284a2a717cd468987.nq.gz
│   ├── 41d30312cfe37fa3c40ed08c5c0d8ee8285e5173.nq.gz
│   ├── 42c9a76f6a005f61a7eb7ad91a4e4f48da1f2729.nq.gz
│   ├── 430ddbbadc63b4adfdaef4773b18a6f91131b668.nq.gz
│   ├── 483b3c1dad337b9f61e4da1950563def5f1be010.nq.gz
│   ├── 4a103946380d8d0ffaf13475c1f1a34307cc4745.nq.gz
│   ├── 4a6cc87e73b59778cf9a60c85b82987b81a058f3.nq.gz
│   ├── 4a8b53a360e38a21023970bc7da1998a416fc779.nq.gz
│   ├── 4adb0e4715a967c9fb0ae905d027234a03e864f6.nq.gz
│   ├── 4d08e2e3715a11983a3d37e728bc37bf9fc637a2.nq.gz
│   ├── 4de886ba22c5d508a8bda357340a858ac3f78ea9.nq.gz
│   ├── 510331192ad5c18b74313c2a1993cbf55c2ab29b.nq.gz
│   ├── 54a866504a99a95f1d3be30909cbefa0f0ded766.nq.gz
│   ├── 59e3f5cc2b4eb4b688da21243ebc46259373ec34.nq.gz
│   ├── 5f8a4fbf630b712fd0f25115f920dc21eb02b7de.nq.gz
│   ├── 68136c9e0a3d5482957e7ecc727981e6819ca284.nq.gz
│   ├── 6c9ce5986e9bfa3b725de67ac5017285a978fbec.nq.gz
│   ├── 6fcc413b006deaea3207b4afc58f5ed2ea9f25f7.nq.gz
│   ├── 72929170cc1430a99b28fa6548deae66319bc4a8.nq.gz
│   ├── 74f29e427afba0a070f1dddd74a8793f64758dca.nq.gz
│   ├── 7594bcd68c5a758a619d1858abb1b42455710ce1.nq.gz
│   ├── 7ae3db636470af5eb92cc28b7496537d9ccce613.nq.gz
│   ├── 7c832b8f8f2d4fab8e05ab9565c874829c908ff8.nq.gz
│   ├── 7ce0e069e9c8dd0acb45c5f46a6f4d3769ae6049.nq.gz
│   ├── 7f36bbfbbb18e13599f775055ae7756dc4722a5d.nq.gz
│   ├── 8a95ec2231af1b15ba33aa424130542bf11ce5e3.nq.gz
│   ├── 8b13673c14657c63f5a23c7b514f9fca0725174f.nq.gz
│   ├── 99bf1b1c7cf4f0089dd08265468aa3a7f54fb35f.nq.gz
│   ├── 9e4d5aad4f0af5b2fa07ba4c13235261e13a454d.nq.gz
│   ├── a16c46b0188837a37025b4be3e3f76b9454aa86b.nq.gz
│   ├── a1b0449eb285ff648ca46b5390e4b2fcc8e97a82.nq.gz
│   ├── a541e693ec11de49b736212190bf28526d953e18.nq.gz
│   ├── a88e13554224cbf0df4a8b5f7f5fa7bf89768a68.nq.gz
│   ├── a971abc3820792b063b6de116a00f412ce1db801.nq.gz
│   ├── aa2595704468ff352ba74c55a2c04daa6ca311f7.nq.gz
│   ├── b3f518ca5d229fe4bef51a69562e01512c125dc7.nq.gz
│   ├── bc73c0da2f24507b9a40c8a2ff6d7b2faeafe6f2.nq.gz
│   ├── bcdcf6ac7d636a2fb1c140262ebd3978ab9553fa.nq.gz
│   ├── bd43570d973848d77f399d87b5ab0f759a6b48e3.nq.gz
│   ├── c48d81a399000922888ee14d09885b93b964cf2f.nq.gz
│   ├── c4fddd414bef01c2efff5a7125f83802f6711f84.nq.gz
│   ├── cd67790ba46899c707f3254e74938dc1ff94b157.nq.gz
│   ├── cecb2d1e13c191494876628763028a00eff44ef8.nq.gz
│   ├── d229323b2859d3deb59f8e6b0ed7c30cb6d31aff.nq.gz
│   ├── d506ab9894b018d047c2a719d5a6a69be8d94802.nq.gz
│   ├── d85edfd09822d4e7df3781de8072f1e641aae237.nq.gz
│   ├── dba13bb0c4f96185e03769fb3aeff3e748ea1ace.nq.gz
│   ├── dd1ea929400abdfaeb0b48ff28ca61879bd7bd22.nq.gz
│   ├── dd38f745a7f967eea3fb8a73b93d6e8fd5c7a395.nq.gz
│   ├── df123bbd860f01ae28a65cb9084c4dcabe28b06a.nq.gz
│   ├── e0fce78be6eb041229512dde1a1c3cf799d5c891.nq.gz
│   ├── e43477971b476703472baf9395891c34eaf80bf0.nq.gz
│   ├── f0bb6a3d335e08050d75e4512bb50ad007bced8d.nq.gz
│   ├── f29199cc234960312bfb43b28f730ea5e1aaae58.nq.gz
│   └── f9bb8f870caaaae1c735411efa630a919a90ca1b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a7586c18781886906935405479f20f579f571450.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[scikit-hep/pyhepmc](https://github.com/scikit-hep/pyhepmc)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
