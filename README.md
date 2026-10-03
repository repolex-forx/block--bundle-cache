# Repolex Knowledge Graph of block/bundle-cache

RDF knowledge graph data for [block/bundle-cache](https://github.com/block/bundle-cache), parsed by [repolex](https://repolex.ai).

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
rlex download block/bundle-cache
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd4f7350c97faae6e8eeb998997a97b17488542c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dd4f7350c97faae6e8eeb998997a97b17488542c.nq.gz
│   └── repolex
│       └── dd4f7350c97faae6e8eeb998997a97b17488542c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0086358db1eb971c0cfa8739c27518bbc18a5ff4.nq.gz
│   ├── 0100217cad89db265f838706f4ddc769c85f40db.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 1161bcd4eb72b8b523a17a488a021c1df69a5b85.nq.gz
│   ├── 117352d4c4f19f09b4959c5df0865381c42cddc2.nq.gz
│   ├── 179d9105212ac60e9bfafb7624c81f6f404afb2f.nq.gz
│   ├── 1d5b2d6c0eab0078062e250c84772ed98e85d6f7.nq.gz
│   ├── 20980a3e13b61d941613f8c1016701afff95b436.nq.gz
│   ├── 292ff9dcab73810581b0fb1673ba69e68acbcbda.nq.gz
│   ├── 2a8eb5e00130c540c00c9d860ebb12efbcb9905d.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 3179eb0d2ece21ee33c37e8f0dc0815fdf992020.nq.gz
│   ├── 351cabb93541aef793ed4b673809105bec7308b0.nq.gz
│   ├── 3734635e8ad42ed99c452dd9f073b777d1bdc5fa.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3b2eb7496ab0f67b1e158d3ed6c690f55642b5bf.nq.gz
│   ├── 3ecb94ec7893750525b7c92a9cca6fa40236357f.nq.gz
│   ├── 42ff52183328bd09a101a628e51b3bcd34438838.nq.gz
│   ├── 4312b6a0b753acc7edc4b1129b86fa3b3984ea2a.nq.gz
│   ├── 438b9d870de198535bdb083e88a45462e9de37d7.nq.gz
│   ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
│   ├── 4f906e0c811fc9e230eb44819f509cd0627f2600.nq.gz
│   ├── 535b059b6bcc45616e0b350f51768f73f1c82ed3.nq.gz
│   ├── 5d416c3e02a39779c72dc6a0e43b7d98f4b4b5e4.nq.gz
│   ├── 68adc5eaf5a110512c60335096c37509fc0eb0f2.nq.gz
│   ├── 6948f16229090833bfe4265c12076291ae15807b.nq.gz
│   ├── 6dd43083b648336aa71a9cf5d3df0cdef5d6ecf5.nq.gz
│   ├── 6eaf93cde83e114555c4ad3955ae8dd13204d114.nq.gz
│   ├── 6ef2ba8769ab0be409ded10b3bc525fe6b147f95.nq.gz
│   ├── 72c20d22bd24acacd1d7957682454176a6d5d061.nq.gz
│   ├── 739907dfd15937f032b5a46390e9d63709e87f7a.nq.gz
│   ├── 743a029c67b6b5c028213c099017af053a8bc788.nq.gz
│   ├── 7b1232070d4f13481ecf894ceb7993ce2f906a24.nq.gz
│   ├── 7fbbd448ef1a445fda0a0d70e76b386313a77b81.nq.gz
│   ├── 7fe8e48f70e6387e2ebd28911c7d2290dd9d27d0.nq.gz
│   ├── 811ac2ef02ced229bb92d4682de9d5e171011cc4.nq.gz
│   ├── 816066f4755caecbea428ebfe33fecd477e0bb7e.nq.gz
│   ├── 89b188cf43b851f8836b5a940179113c44bc7838.nq.gz
│   ├── 8e72a5b30fecd7b97bdc2760d1ceb00a24ab822a.nq.gz
│   ├── 947d139800ebaf98255de7fa1b47ad3eaa96a026.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 96dffa57e9104ad338f2bfd6bd3c977015b6a85e.nq.gz
│   ├── 972da331afe0494f899f7a3b84cf07656f598a4b.nq.gz
│   ├── 9c7e3506910d240a2056d4d180ff8ef632aa2c99.nq.gz
│   ├── 9d23a21242a8cecefdbc9eee65a1a3957a861e9e.nq.gz
│   ├── a423609a332b5eec52c101bde2b803c5701094c2.nq.gz
│   ├── a57b89f5de2aa9c8aed69729d0a0ac5e5a5f8554.nq.gz
│   ├── a6bef1b63042b0ccbe35c2c8c51f55273bc3ac3b.nq.gz
│   ├── aec52bd9c19139838d7e41b035845fa13d03382a.nq.gz
│   ├── b9693180c343146c65d533a524db671bf4d0c92e.nq.gz
│   ├── c2658d7d1b31848c3b71960543cb0368e56cd4c7.nq.gz
│   ├── c42672d95b9c4a11188537e817661db8534a33aa.nq.gz
│   ├── caef296b58ce4e14fc41877274ae223a4c5610cc.nq.gz
│   ├── cbf3ed9b4efa6f181e9562c5a45d8c8c08f0e8eb.nq.gz
│   ├── cf73c011fbaf45f7b99468516c30e6fafa79197c.nq.gz
│   ├── d56e8750cedfe174a6ad1a741c889ba8f9d06079.nq.gz
│   ├── d997cfc60f4cff0e7451d19d49a82fa986695d07.nq.gz
│   ├── dae12db6000f61b834a30e777e1b8ef58fbed727.nq.gz
│   ├── de26aad3533f0dc787537974464ea860942defa0.nq.gz
│   ├── df69f7b5671597e81684059ed2c036a39478cc8b.nq.gz
│   ├── e708b1c023ec8b20f512888fe07c5bd3ff77bb8f.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e8fe89bffd6a8e54977d3192fa8300e778387e08.nq.gz
│   ├── eb12ac847446791a97ea0a724bdd6f9265052c44.nq.gz
│   ├── ef83497478e18c32b7d25c8185f57d11a809fdfa.nq.gz
│   ├── f0df0e82391e22ee5ec477226fe8c4cee0ebf246.nq.gz
│   ├── f0e42af466b703cc22812c5a3ed7caeaaef22b47.nq.gz
│   ├── f41124dfb026f231b4abcd85b20328e0237119b9.nq.gz
│   ├── f50dbaea8f2536d541f5c7628cc6ee3d41b7a011.nq.gz
│   ├── f59e6aa462ae714c671c5c4c71c75bff933705f7.nq.gz
│   ├── f8ed57db789d7e7ec50fa40af0d3a4c265b47f64.nq.gz
│   ├── f96d538800ab49a074533964fb30332fc76e4a9e.nq.gz
│   ├── fd228a19fe64caa7906c435549c87eb9cab4d396.nq.gz
│   ├── fe0d7b7605e045778d23d8f5ae23f428e341304e.nq.gz
│   ├── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
│   ├── fe638999ccb97a7dfd11952cd172a18b80dde71d.nq.gz
│   └── ffb66e1165edfb6b3db0934842aa78484fa8d097.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dd4f7350c97faae6e8eeb998997a97b17488542c.nq.gz
├── filetree
│   └── dd4f7350c97faae6e8eeb998997a97b17488542c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 87 files
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

[block/bundle-cache](https://github.com/block/bundle-cache)

---
*Parsed on 2026-10-03 by [repolex](https://repolex.ai)*
