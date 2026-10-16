# Repolex Knowledge Graph of pysal/giddy

RDF knowledge graph data for [pysal/giddy](https://github.com/pysal/giddy), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/giddy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f853d8569ccc5a8a17fc9c11e5c2cb925a89c1a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f853d8569ccc5a8a17fc9c11e5c2cb925a89c1a6
│           └── chunk-001.nq.gz
├── blob
│   ├── 025d8a428c5228089689a085538e0113579386d6.nq.gz
│   ├── 037421ee8782810b38fd922605b5632bf1a21655.nq.gz
│   ├── 045f6cd0eef95c589c95790890eb65ee4968670d.nq.gz
│   ├── 066b2d920a28db73b4ba3a0b35e6905eeeef5772.nq.gz
│   ├── 06df047895cf7b1605a381f37ea63aa51e35f6b5.nq.gz
│   ├── 071f1ab4185aefc4ef0cd62ac790d3944ff00603.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0a76da84aabd1bb7b9dc12279744a94eda1b8b1b.nq.gz
│   ├── 0cee9111042aaeac667efdd449284f728c230750.nq.gz
│   ├── 13d1037db8b8ae5544984c6e4fa85bbfcf830d32.nq.gz
│   ├── 14ced838804fe29f1b57815a250030d262915d28.nq.gz
│   ├── 203fe2bfeb1e3d4e3c358e4c93af78e76f0cf567.nq.gz
│   ├── 2141baf2e26a850b816bcf41b34b9eb9c76b6c08.nq.gz
│   ├── 244f19650fd5e1097cc6d1aeb95d8cc9681bd7df.nq.gz
│   ├── 29f9af8d122a8f1dccacb61b98d0e9c02efdbfc5.nq.gz
│   ├── 2b560782af7a8a53b189987c3318c31e1ae76744.nq.gz
│   ├── 2fede5a966e166dd1e6d4c953a6f48aae1f91568.nq.gz
│   ├── 32a62ebc83cd8560c3ea4033055df02f1af4e429.nq.gz
│   ├── 348f97bc40a481c8ba990eb80f120a3a8693cb34.nq.gz
│   ├── 3a307710b8c9cd3c0cf588d773122da5da1f8dec.nq.gz
│   ├── 3fb3721b26389e06059ea3d5f1c519d821fa3d26.nq.gz
│   ├── 4b49ff94cbd2471b2d8f16b3a8ddf9d3ac664dc9.nq.gz
│   ├── 6547ade38843438f55eb58ac715cde8374687ac9.nq.gz
│   ├── 656ded01ca30bf10ea879618405188eff1598dbb.nq.gz
│   ├── 6efc99e2da5dcdc4ea14ff06ce9320f8dd767a0e.nq.gz
│   ├── 71fd0580ae69f02f08e7d7e9115525d268079682.nq.gz
│   ├── 7640976c1be2c65f90503131b26c49a7916ce784.nq.gz
│   ├── 8370f5df78ab4d366509f0dfcbe723e60abf3a8f.nq.gz
│   ├── 893dac6954bf488a33f662feb49dbafeb218240e.nq.gz
│   ├── 895c81c66927b0588e49d77f590df16c339e2ee8.nq.gz
│   ├── 8d1c8b69c3fce7bea45c73efd06983e3c419a92f.nq.gz
│   ├── 8f02a35a73a134273da1eecc21f865e284ea3876.nq.gz
│   ├── 8f46c1b167d87a53df49a0354861e832bdc9526b.nq.gz
│   ├── 943996eb545d802de3a08ab6253f12c23cf4f465.nq.gz
│   ├── 94cfcf1fa888ee9444853d035bea493f127bef5c.nq.gz
│   ├── 95fdd5d049c529ebf50b5de9c59d91d103610f95.nq.gz
│   ├── 992739248c037bf6d808d6719d7361ba1d8b9e02.nq.gz
│   ├── 99d4723b101e3e107b7e4293b03ae07670e95ff0.nq.gz
│   ├── 9a49157cdafa3d4be4117900bda6568ec694a42b.nq.gz
│   ├── 9b43b7e079db38886133ef5fda6bbb85292c307c.nq.gz
│   ├── a7c3d1edbad0647a230d62dd66c5c09cd105aabb.nq.gz
│   ├── b6aeec647b6b87662b7d79a8c52c0feb2de56591.nq.gz
│   ├── b735373365bc7172f141853a93d0a5eea3733440.nq.gz
│   ├── bd5070fc49e975586ace0b67f113047a72b09093.nq.gz
│   ├── c04777285f62ea1d4d9ff51ea59fbab73484b679.nq.gz
│   ├── c20e20c07677ee4daf20697ebea00a29b679a131.nq.gz
│   ├── c41bdca1c452539d0039582cb5af13d227514d17.nq.gz
│   ├── c74d59b00547641d3391091fde8233dcc4761ded.nq.gz
│   ├── c894f931047dd8e4184a9b71a7c855e2bfcb8210.nq.gz
│   ├── ca95f4bec6808df71a7ea52ad9d313fa7dc8d681.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── d277b62231643bc3966de8489f830a9043ddf27f.nq.gz
│   ├── de1d4f99c785a5e36120bcfd8b2a698d2e00156e.nq.gz
│   ├── e202294c5d0924b9e6605f9075869a19f6a43ed3.nq.gz
│   ├── e4ecbc3c0397e09e3c5ec4017514faceb048e6eb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7778691eae98fe2f2df1424958884de3a3d5b2b.nq.gz
│   ├── e81b5981f2210914f65915d741276740f11e8e5e.nq.gz
│   ├── efb343cba2f80444dc1946e2f69b7b4f8e41e33f.nq.gz
│   ├── f54354496e0c4488ad7b8721987907d94374858f.nq.gz
│   └── f5b6579d1fa4e310c33407c3a6ac83f5cbc2582a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f853d8569ccc5a8a17fc9c11e5c2cb925a89c1a6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[pysal/giddy](https://github.com/pysal/giddy)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
