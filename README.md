# Repolex Knowledge Graph of TeXitoi/structopt

RDF knowledge graph data for [TeXitoi/structopt](https://github.com/TeXitoi/structopt), parsed by [repolex](https://repolex.ai).

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
rlex download TeXitoi/structopt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 97e92a3755a65f8ea44c994fd403208e7d97f561
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 97e92a3755a65f8ea44c994fd403208e7d97f561.nq.gz
│   └── repolex
│       └── 97e92a3755a65f8ea44c994fd403208e7d97f561
│           └── chunk-001.nq.gz
├── blob
│   ├── 018223c2fbbff1a3a43451d105130ad000694ccf.nq.gz
│   ├── 0230d57da1c782e2ebc4f87436568f81a30214d7.nq.gz
│   ├── 05ceca9d6145857723186feef4ce5aec23f0e232.nq.gz
│   ├── 05de1856ed8b4611c83c6f11af2bde98dd759488.nq.gz
│   ├── 0722140df61004971ee099c0a4b31bee17285669.nq.gz
│   ├── 0838f50458d59f5edb2ce6155668724796a0159f.nq.gz
│   ├── 0b80d481e3bbe80167c42364065d54719918bcba.nq.gz
│   ├── 0c80c2ec2dc246291ba6a3ecc7019aabcefc1baa.nq.gz
│   ├── 0d9337c84e9dc37e96734da92362e9be8a52178e.nq.gz
│   ├── 0da349b324a177f57fc533f7ad635aa090378777.nq.gz
│   ├── 0f1c8b57cae33085ef9a3848a05a0500897d9c67.nq.gz
│   ├── 0f6f0784a7cc3024b60d8a6bdca69e8b9df1dc27.nq.gz
│   ├── 11511a157b17627e83afdf0b422bb452734a0688.nq.gz
│   ├── 1475e2a921aea90bf4accbfce5331559602ee462.nq.gz
│   ├── 16ca366566b5e78c9de60bcc34604824a1113e72.nq.gz
│   ├── 17bffbf11b646ddf13a4ab9a3b1a35dc057676f0.nq.gz
│   ├── 1837ddbfcfefc05ef2ceba755d9ccb3b2c7707a1.nq.gz
│   ├── 19208ec2b59c5e9ecced591d413f880b2462391b.nq.gz
│   ├── 1979e84f7fcc268b7fc30cc267d7def1600fe05a.nq.gz
│   ├── 1c02a8256401af10baa3b65752160007c12cc62c.nq.gz
│   ├── 1d31683a78c3d7a9252e1c4c6035291f517fe2dd.nq.gz
│   ├── 1dd84e54b267ed747c419836a6d31634b4c52691.nq.gz
│   ├── 1e26a2dc93961b2bb7e35b8fb220a90509882061.nq.gz
│   ├── 1f44769fc1d28a74f7ef5ab0bc6239d1489c2c74.nq.gz
│   ├── 1fbd1666f76822fb3e028d4ae5f5984e046d655d.nq.gz
│   ├── 2215497ad0541f0ca5887578f9e76f8be4c38e56.nq.gz
│   ├── 25b37e5fd983bc1133d22862020eb139044f4bb3.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2a08105b1970a70bf125755cc37173366d663bc4.nq.gz
│   ├── 2a720800cd9bac168a37fe633348247212c3b4c3.nq.gz
│   ├── 30353f8aef577b5ec103aa45984b53980efeabac.nq.gz
│   ├── 3317272b5f429f7c9d18552973e8070776236a1a.nq.gz
│   ├── 3345f9270e4ad0b4c4ce28339a6615ce9b86e1e5.nq.gz
│   ├── 33e441550d6d013152e24aa6a43a33fe6e9b570a.nq.gz
│   ├── 34b99a4cfe8cef0aff08211213e49d38e65016a6.nq.gz
│   ├── 373a3b8e15a6ed7a8bd429ee46976501d20c6987.nq.gz
│   ├── 383bd230740ed0ef72d3d96376c4c190f27d3ee4.nq.gz
│   ├── 3847dc2f5c073588fa6a9bc98be93a9b4247e5e3.nq.gz
│   ├── 39a5dc3970000cebaa501335d2ef75364e10367f.nq.gz
│   ├── 3d22152911daa1cf43fe9a627c1cc9cb601a150d.nq.gz
│   ├── 3d9388f2ab2605a3ed12e48f1eb6c22b99fdd4af.nq.gz
│   ├── 3dc9f2491baa42e7ea262378d0b4cdf400c22d89.nq.gz
│   ├── 3f9e1af72219752639e1042bb43df27913f0d9fd.nq.gz
│   ├── 407005650e94b501228e4238c2c11714cd45fdb0.nq.gz
│   ├── 43628e07d4d505531f79ebdfaf2d84ad050b0cc2.nq.gz
│   ├── 437f3c6832698f58d18aa09b6b97792fffdd62f7.nq.gz
│   ├── 438f6f804881e84c7487ff5863a445051b6460e7.nq.gz
│   ├── 4467abb858c746898455bd0f0af57fc96aaec572.nq.gz
│   ├── 47682d8d7e762b159cb0845291b7731e6d415228.nq.gz
│   ├── 4c3a442d322a98e21f1cdcbfa444e1f833e9e879.nq.gz
│   ├── 4dabe14bbc3180d7658f990d1372f4e0fce68b61.nq.gz
│   ├── 4dbf5389ce1cb5bb054058069cae563b48cdeefb.nq.gz
│   ├── 4dfd341209e1e792b13cd211c21924babd3517f6.nq.gz
│   ├── 4ee738b1170b4a991cce30f667bba440767b9689.nq.gz
│   ├── 5518214e5f7f387b7fdeca31ec633558c9fc02a1.nq.gz
│   ├── 5592a1a397314ba3fc3b43d63c6e0e79a0b67a69.nq.gz
│   ├── 5765597d1b8e6a8b64191edb9696cb94e69ba905.nq.gz
│   ├── 5d21426b8fe20e3c1380d11851ded89ab275fe9d.nq.gz
│   ├── 5eebc57f365462ac465628874fbc417b1b9f8c31.nq.gz
│   ├── 5fc6274ea5e626f20765cc0556f4f311eca9ef71.nq.gz
│   ├── 6958c016b7b48d963a56ab54f951cca76e462265.nq.gz
│   ├── 6e4137bda48eb825199b0fd36e1beba6b09bc299.nq.gz
│   ├── 6e99e8b7fb85f871735ca9077f6773a256795337.nq.gz
│   ├── 721204a49e11f209944bad697f9b06ef543cfa5d.nq.gz
│   ├── 730bbce7288115c09be6cb66b4502ee97b8778a3.nq.gz
│   ├── 73c53420cbce30eab4cf2feff6d3c01675f336e7.nq.gz
│   ├── 73f12d28004f4f9f9489df8452bf01185418590b.nq.gz
│   ├── 742ee6d0b68c3be562a9fd6bc99d4504418365eb.nq.gz
│   ├── 74342f74aafda86edeee874309ea2dbe2bea095d.nq.gz
│   ├── 75816c7425bfc1b41b72f28057f3f9f0b5af0d57.nq.gz
│   ├── 76477a3c9b09bd30a1ff1b4814d7d82344ea5c34.nq.gz
│   ├── 768de763d8e7bb407cac87c7b97d3fd7beed1633.nq.gz
│   ├── 77d97ae3b21269859100efb8c88b318692d2480f.nq.gz
│   ├── 7893e78eaeeb54512e5919b9c7d8e2a668cef519.nq.gz
│   ├── 7b4fcc9587dec1633ed7f704b4c2cf38e83d1295.nq.gz
│   ├── 7cf74445d1d5af11a247facb969d39c683c4ef29.nq.gz
│   ├── 803abb4664ab9b00567b589536474b67110a6fa1.nq.gz
│   ├── 814f3d8c252eb7fb889a77552d7f1a2c1f94e95e.nq.gz
│   ├── 8668ec2a952dfc5a344c92631dfb14393a303ce8.nq.gz
│   ├── 872917897c2b9e13b1982f537293b9eae8fe41f0.nq.gz
│   ├── 88b549db276c4e0ff7dbfeff09e55c931909f26a.nq.gz
│   ├── 890f10c5e76580419c9f4629a1ec0d26c2dba039.nq.gz
│   ├── 8e4326f2bc06da7676e97c22fd7bff99746037cd.nq.gz
│   ├── 8fe055be0219e73802b436aeb0b4e6b97e3fdc2f.nq.gz
│   ├── 92acafaa78282b0c771d2698696450853ba38891.nq.gz
│   ├── 92d93ab64d18bffc1e71823ae4122398ba1364c1.nq.gz
│   ├── 93b5e38db56d0ee60c80e427d19668273659a90c.nq.gz
│   ├── 95ed4a525c8709086f6cc19049f9bcf575c35f0d.nq.gz
│   ├── 96a09382569137bf37759da31fb9f3027b49c041.nq.gz
│   ├── 96daf45cc0c7716588c65c8163108c2195a909ba.nq.gz
│   ├── 986261bc46bc31df30423a656e5ff98f28a69c6a.nq.gz
│   ├── 9bdb0c94735b9913b7b1a4c27aa3d4ad4223f760.nq.gz
│   ├── a36071b4b8134e541d90b98920f9f393265d47a8.nq.gz
│   ├── a4eb0028e77263d0b777864cfa988135f448dd97.nq.gz
│   ├── a7fc0b998f2ad794718e5157fc773cbc76761f5a.nq.gz
│   ├── a86bc0ea7996a3a81a943aec252766df2cd735c8.nq.gz
│   ├── a88adc2e5ee575924909f3eab6f437acaefd1103.nq.gz
│   ├── aba2d69f3e3f9b9da2d23657abf7580e058cffc2.nq.gz
│   ├── ac0b1457f5f481891ffaf76e9c2f7eb28c6d23a6.nq.gz
│   ├── ac7d1435616eb847816e927362bf491e017f42e5.nq.gz
│   ├── acfef0b21accbe9e0569d744b5b8a762fa9848e3.nq.gz
│   ├── ad3acd9d50306fdd765edf93c39c5ac576b2d2d7.nq.gz
│   ├── ad62e7337a5161c13baaf8446843d230acb0a2dd.nq.gz
│   ├── ad923857458d79badbe78a3b6353b26c3d1cb0ed.nq.gz
│   ├── af9b1d5c7b348956651307d35b9fdd8efc9792ce.nq.gz
│   ├── b6f125a1ba4a02867893458f5ec02d5bf8dd2205.nq.gz
│   ├── b94f783d7bdb9728b6a07b1c7111b0a62af880aa.nq.gz
│   ├── bc47511f863b6f5869bb7bb8b9624a31ad40c281.nq.gz
│   ├── bd3b3eda41714ebd95bae28b86bf7921afd0749f.nq.gz
│   ├── bff1587b121f9713ac346f12622157e1cd757eb9.nq.gz
│   ├── c00ff669d9731f5b4b0991df4be06a02d186377c.nq.gz
│   ├── c0684a20096fd4718cb88276f7d572cd2548f607.nq.gz
│   ├── c3ed1ad94412ada8fc9e1b6e1a7b681bcbf0fe28.nq.gz
│   ├── c6b343f947dc51334663f581b4b05df608714409.nq.gz
│   ├── cacea5edc3eeed5109f840ecc042721133d1e67c.nq.gz
│   ├── cb9f1728975b8d82f007c982ad1959332a18e1f6.nq.gz
│   ├── cc6eca89f50e82bfadc071540b4bab7459a784f3.nq.gz
│   ├── ccaf28dea0a276b454c107954f3d5cd3aeb72fcb.nq.gz
│   ├── d08be0cc2f634e6e82f1474caf8ba485b7e816f2.nq.gz
│   ├── d74fa85897b4c16602122300999c1fd9c4c63f6a.nq.gz
│   ├── d91afbf29d6f364e93499a8ba0836e678364f254.nq.gz
│   ├── e217a840b962e188ac6d15f24494993274c4045e.nq.gz
│   ├── e3497b27121245b49e83d4c61bcef95441a1d471.nq.gz
│   ├── e428b23f9c5836b602640ba573e09ef50c729631.nq.gz
│   ├── e931b83b643f3919cba7387bb3709d04456f55c2.nq.gz
│   ├── eff7a8611820262b07e9b2dfeee7c73b25bbb5f6.nq.gz
│   ├── f24e4bc79704036bc3df1dad5749f9219d7dc080.nq.gz
│   ├── faf8628b8497216ee785c9426af4cf2e908e8754.nq.gz
│   ├── fb77ef2648ac1335d2451b8d4f4ffa99d535ed95.nq.gz
│   └── ff1af2eeb4d84fdc31475a18c8a3f7826d1f4a80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 97e92a3755a65f8ea44c994fd403208e7d97f561.nq.gz
├── filetree
│   └── 97e92a3755a65f8ea44c994fd403208e7d97f561.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 140 files
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

[TeXitoi/structopt](https://github.com/TeXitoi/structopt)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
