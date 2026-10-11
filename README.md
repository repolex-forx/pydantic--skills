# Repolex Knowledge Graph of pydantic/skills

RDF knowledge graph data for [pydantic/skills](https://github.com/pydantic/skills), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/skills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 238d97102650c1caa51f35027aee13c469c59542
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 238d97102650c1caa51f35027aee13c469c59542
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a6231d60e20008fc468ffccebb3f8568c7e6db.nq.gz
│   ├── 01422c658f6bf592ab8255d3947751a3f42ef829.nq.gz
│   ├── 01877e9534dca8b062a759e86445c0cd86794396.nq.gz
│   ├── 01fa584b29ab1509f6d657c494557eea9b581c97.nq.gz
│   ├── 033ec35e01eb0f8aa3dd04d0b474eb0b3249da5b.nq.gz
│   ├── 058bca6f52afa8cffd029e3873291907b9d384ba.nq.gz
│   ├── 0f0e98729356fcf61f4bd55debe5192bbc0bc05b.nq.gz
│   ├── 121292b34d0791d177f307e8b2e208807383863b.nq.gz
│   ├── 121a8623515a78493d54b4b720333c221cf5a893.nq.gz
│   ├── 12c38483e6eee15d49c5dffcc66007b56e816d8f.nq.gz
│   ├── 1662f21df9af8c52198f2418d49355eae6eccab2.nq.gz
│   ├── 178bb37fbeb7995abd4363f2cc421a56e39906b5.nq.gz
│   ├── 192f9f2fc1bce826df18a63f5d7758fa8c33e798.nq.gz
│   ├── 1ac376458340227751c2c98f1a9ed9299e6987f0.nq.gz
│   ├── 1c0f108a572f077e84eb1b8872beba2b26bc6856.nq.gz
│   ├── 1c16343f5478e927e839625d97721fb5d04005a4.nq.gz
│   ├── 204bba5459914319277a25d9009f5faaddf77f1b.nq.gz
│   ├── 2250cb9428144ece73cde50f907cc52ec90c4bf4.nq.gz
│   ├── 225cfc5c8aa89b6f6278d87f9324d55fe7dcac4b.nq.gz
│   ├── 274167c7ff77e47d119a77c6cdb332715c72ffca.nq.gz
│   ├── 2785333ace3c0e01ff0701e10ea6980a72d769f6.nq.gz
│   ├── 2979708fd7c818e38e3ec89ca8b31efb34410599.nq.gz
│   ├── 29f9d1d98d4835b0096f3b798358c3ea2ddf3a63.nq.gz
│   ├── 2be3d91f5f135120ef48998c707c2eb19fd2474f.nq.gz
│   ├── 2f38f6270daadfccfa9ae5227a44850bf0eeff12.nq.gz
│   ├── 30830232ba6d020cab8e8f401d0ab63bf9b4f2db.nq.gz
│   ├── 32214ab9f95df7bcc6716cb735b4d990751f54ee.nq.gz
│   ├── 3ba43244b067e1f157f8bbad088e760fc2a36c73.nq.gz
│   ├── 3c9fcad5442e31e07a797ad5ae5bc649d0fa0396.nq.gz
│   ├── 3eb7088a5bf27ce9921d959ca8d53e0a0899e8c8.nq.gz
│   ├── 3ef1a8fc73e727263c1263e62e838c97363c6b37.nq.gz
│   ├── 40435a64216eba94b50e099ae97721141354e953.nq.gz
│   ├── 4238085e5ba0144099e63f23326929ce2599a50a.nq.gz
│   ├── 438f8077c77c982316609738af9faf071b1af7d5.nq.gz
│   ├── 442bcd610bcc03937e54a98ca1affa3680d5b162.nq.gz
│   ├── 44412a6eabbb023cdaad51a6bb6387a234fda7d5.nq.gz
│   ├── 44cd406d161b25efe3f0bd96d16c5a952be303cf.nq.gz
│   ├── 4533bd5de92f69aa23512545c8f210a9f672a5c8.nq.gz
│   ├── 4621a4e490cc67a2b60e5ada5fb22c1efcc81865.nq.gz
│   ├── 47767d61b62c844561120b748946a9671f504b1e.nq.gz
│   ├── 47bae6eb051574f9636b8b92b1b6358dd3a614d5.nq.gz
│   ├── 4c7237c6441d6b16e6b871d127bbbe97f3eec52a.nq.gz
│   ├── 4ea7b21a25bad24d6416bad9326482423bc47f0b.nq.gz
│   ├── 50a669d4c6ac3e442cdcd4ebf05050f1bc038557.nq.gz
│   ├── 581597a44242d2f46ad53c2931b3d3dbe631e928.nq.gz
│   ├── 595ae3fc2f3bb49671b23d8a240dd9f1b0df940c.nq.gz
│   ├── 5e3bc7dc4b9da474e93aae6d7e04762db8ee664a.nq.gz
│   ├── 5f86bcfb4979e9bf40f0179957fee60ba7512714.nq.gz
│   ├── 6285dabd88e896901a1e7f43f29376d9842240ae.nq.gz
│   ├── 641a0b71b95e285ede0546f3657cc6d278ace665.nq.gz
│   ├── 653541372d7136bd7d3781bf00ee3148f7019f96.nq.gz
│   ├── 68626d69fbb46408f3023cf0fc1331ac9814cc03.nq.gz
│   ├── 6a21bd4079575bf897ca946f089c726906b8c790.nq.gz
│   ├── 6c1ad878733fad7f19ed2c7567fa19ded839d71e.nq.gz
│   ├── 6ce5d270d223fb7b541f0038c7661bde0b6218e9.nq.gz
│   ├── 6de2fe01d820dc08fafb1993a636639b1b4d090f.nq.gz
│   ├── 6e9623e4718b85eac53058cf63ba45e2b5ac69f6.nq.gz
│   ├── 6f74ae5b14c24f1b1124b4bb6e3c42dbddcc90b1.nq.gz
│   ├── 76fedaebb32a244459ad425a3c320cc0b4ca2f9d.nq.gz
│   ├── 7a150ec61c819d6b8553948cfb87bfb97c134b41.nq.gz
│   ├── 7a66aa6b1f528e431eb75ebeb0b237b7c07d93a6.nq.gz
│   ├── 7ab9a5f13823f65dfd721f84b41e45aa1b4070ab.nq.gz
│   ├── 7bbd55efab2dd91572b515e4285e77489a7d313a.nq.gz
│   ├── 83a654810557e9420b95a134ef2e4b1aee647f7d.nq.gz
│   ├── 85ad67dfc39eca8b22fb0e9b2c2a318ec9eee3f7.nq.gz
│   ├── 85fb9dce15f9e58fdd18b370ee1916bc764ec9bf.nq.gz
│   ├── 8a72392d5e9f54759ddb29589f5d7b416b1f5a53.nq.gz
│   ├── 8aedf2c5c573ea35db12fa9414cca4629222df73.nq.gz
│   ├── 8c92e69eca6bc34880f8e4b152aa887dcafdaf04.nq.gz
│   ├── 8fac60cc6793e11e3e49910d79b71ce1f920e82f.nq.gz
│   ├── 91ba34ae2a8bcc2113f6c2e6d834b24ad9e2c102.nq.gz
│   ├── 9795f4e4b97bc695bed0781ca0448e0c6afc2cca.nq.gz
│   ├── 9a9a2d9d3b87729ef7ec4d268bdf6f7f2cb5e39a.nq.gz
│   ├── 9b5d39ec84f3f649b74e42c0daff97e606761899.nq.gz
│   ├── 9fb65f4cac6bf724b8d34ab53daaa7f408520432.nq.gz
│   ├── a01ba999e263408f37e3d17fe51fa9f54eec44da.nq.gz
│   ├── a0c37f6248498567aa66905980a44483f01ce410.nq.gz
│   ├── a266b17847d4cdb914e2263df172e9cec21d01b7.nq.gz
│   ├── a33e0c84bf58e1f7dfdca650619802a36eb3fdbd.nq.gz
│   ├── a3fe0c3a62ee42b06b19c3259cd58101595a715c.nq.gz
│   ├── a533aa8ab616bb60be656f13498d26f1fa2911a2.nq.gz
│   ├── a9a771fb336c2317e1162d530ca6a60feaa71269.nq.gz
│   ├── ab374f9d5f2fb9a18e10f6c893d3ed4b6f8461c2.nq.gz
│   ├── ad7b80db74aace495a1626e4be50832fa5a05c3f.nq.gz
│   ├── ad94194b1405650922f06855769d926154e440a6.nq.gz
│   ├── b1fbf3fadae55b40ee71cc5d298735269d3943ae.nq.gz
│   ├── b43d12b0fc005ebe1f384b5e29549e06c9dce725.nq.gz
│   ├── b62080ff46e20d72fb51acbcacb80902c135de72.nq.gz
│   ├── b9a76ce8a4ec8a9ec630f32d9a051fbc3c246d82.nq.gz
│   ├── b9a7e8e62b830f81138c1ba880e62880ec216adc.nq.gz
│   ├── b9ef057feb40915847c7147b1090a1da5c0832e8.nq.gz
│   ├── bb5985731f219d0ef2f68ecc4b05ac86c626e6f6.nq.gz
│   ├── c511acb2821c4149810daccc217ea4555c14de18.nq.gz
│   ├── c5e5b749ee3220915cb3bd324e3902208fa07bc5.nq.gz
│   ├── c6b7d4dee6c5b2e25a06e171fb8ee4fbfca3e490.nq.gz
│   ├── cb017d4af6b853f70c8b03503a7163e6aef0ec34.nq.gz
│   ├── cee1fd322c73dac92def4102349ad98faf55de9f.nq.gz
│   ├── d10f0c2c78cde50535801b919c2cb08b89067601.nq.gz
│   ├── d14cabe2cfdfb3d952c3dfc7b0c45c05817cb450.nq.gz
│   ├── d270ace0a67e1329898f3eb74a771da1159e664c.nq.gz
│   ├── d3a050ade29ed33402cd209a7b332e1e6f5a2c2f.nq.gz
│   ├── d8b2f98a47bd9100e27c49b7fc0a03e198806b97.nq.gz
│   ├── da958eb88f5c954b55caf193011f1bfa59b28261.nq.gz
│   ├── daaa1f6168e9f621563be18d04a3a93dcfae7b2e.nq.gz
│   ├── db17cc476f3735b4bc2941e37fe8d43ec0ed55ac.nq.gz
│   ├── de228dcb693f3e98dfdf45bf5fcbee99a4a4f6ee.nq.gz
│   ├── e14db30ed8695c2e3ec15b3304694cf6101e81a2.nq.gz
│   ├── e1de1b4929c5ad820ec16ca7e10c5278294d8548.nq.gz
│   ├── e3e8de347646b5901f77cad3fab2000eded05d4e.nq.gz
│   ├── e73d1e6f0df1097cdbf2f6bfcf4bc013a9a20d55.nq.gz
│   ├── e7bc1085f7c88056a0376b36bbfda6cb6f0d98d0.nq.gz
│   ├── e96ac1d9665346cb8f3729b75b73497abdcccc17.nq.gz
│   ├── ec68f2c14e4902a7f6513da58c0b81c21de84332.nq.gz
│   ├── ee824cdd41018f5425e8b6f7580ee9a7ee7a7874.nq.gz
│   ├── f04a636e166f4dd680255f1bd8d60c108ffa1ba1.nq.gz
│   ├── f735720c95d6b390841da5c5077d30ebd5fbc1f5.nq.gz
│   ├── fc47ff9d25bda74d4313c5f85dd8f353af4414e8.nq.gz
│   ├── fc861d63c4fd2c2494916f0d1f70e6034a599549.nq.gz
│   └── ffefb1373c6747940be781b54818f812f21fde93.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 238d97102650c1caa51f35027aee13c469c59542.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 127 files
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

[pydantic/skills](https://github.com/pydantic/skills)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
