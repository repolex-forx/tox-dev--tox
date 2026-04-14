# Repolex Knowledge Graph of tox-dev/tox

RDF knowledge graph data for [tox-dev/tox](https://github.com/tox-dev/tox), parsed by [repolex](https://repolex.ai).

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
lexq download tox-dev/tox
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 71ef9bf8257667485badbb92042e2705db4bbf89
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 71ef9bf8257667485badbb92042e2705db4bbf89.nq.gz
│   └── repolex
│       └── 71ef9bf8257667485badbb92042e2705db4bbf89
│           └── chunk-001.nq.gz
└── blob
    ├── 032857dbf15c87fa252f1e583e9b0757d86aee5f.nq.gz
    ├── 04336dc1375b5eaf6ac0498a8c4a8df27db87d1e.nq.gz
    ├── 0a18d5146709c5eb65874252a59f77f7908a8b6d.nq.gz
    ├── 0b27ae67e23dc154a70d2c1e4fec322a2643234a.nq.gz
    ├── 0b88e785e01a2dba19342a4ee37be4c10d60739f.nq.gz
    ├── 0c06369a1a878b6dbde4d335b627beac10d55ce0.nq.gz
    ├── 0d285817104413bd6aa1fa565deef3c3fc0b7eb3.nq.gz
    ├── 0d2d23ce4c91c2b0778c64c77de1b64a00534079.nq.gz
    ├── 0da46bc06ba75a62994559dc2826851867ca9c95.nq.gz
    ├── 0dfbaccd709fbadbafdeeecf11b5ef674320cde9.nq.gz
    ├── 0e6edc1622a4296b090f347030ca192499f332d3.nq.gz
    ├── 0f15fa3b6f349f44777dc2d529c0329ade4d27d2.nq.gz
    ├── 0f7745a886fdb20be1e76ff55610093f4f14b772.nq.gz
    ├── 12a1b5174cf81b97113261a202438af352758ece.nq.gz
    ├── 14993633d3ddf9be01005a6ceb32e25e2340b8c0.nq.gz
    ├── 1594b436b12789ecdc7462bcae6482c7f7a227d5.nq.gz
    ├── 15964ce42eb72c37d480106d27011b9003293796.nq.gz
    ├── 15e725b07d4903f022c304a84b5a922d93f68219.nq.gz
    ├── 16b0fe0a6bfc05c03fe1a1424bb2d2b502290609.nq.gz
    ├── 183e45a7e61dafd44af488520d0e3b071f0355d4.nq.gz
    ├── 18c949f983f9dc08b04f8566c304656b66503c36.nq.gz
    ├── 1bb8bf6d7fd4c8d09aea89b47de20fb8bbb61626.nq.gz
    ├── 1ceab431ea9a9adf68d8e9417ae5cb6200d03495.nq.gz
    ├── 200d7e45d66a9b450d06213d0541c897f6e08d6c.nq.gz
    ├── 20f267957c2f4697de5edb0a6d95e7838f034b88.nq.gz
    ├── 21dbee83cc03a8978d24b4adf6acf2cc155b4acf.nq.gz
    ├── 21e90de6a371142e6aa15deff9592c7b2acc1ad0.nq.gz
    ├── 2263cd8f716a635802389ad27ba54cc3278ca308.nq.gz
    ├── 227a1407d33f0122c56299fbd567eb2455ff0124.nq.gz
    ├── 228689a2f301d90caa5486b7a74a45b816e92cb0.nq.gz
    ├── 22d83a3eba9e2d5af1ad6e1c08ec7a9f5d113378.nq.gz
    ├── 255c77a69b51c11bdd40ad1d24d3660eb396eacc.nq.gz
    ├── 25e665b95886763ea5e9d55254ecb9eb688dde64.nq.gz
    ├── 26578212c0c42685acc5103e8918972c8d47dd1d.nq.gz
    ├── 2675747fc3bb731c9784777fd8af66026ec8dba6.nq.gz
    ├── 26eae75bb09ae532f8806ab58c4eade8b0f66457.nq.gz
    ├── 27cf40a19c16cbd2cdf126dbb1acb8dccee75c04.nq.gz
    ├── 28c64381634343da938b53e51276e53bf0cd2d03.nq.gz
    ├── 2a78523601c9e6a23d22fc7c0be1e5594d35339d.nq.gz
    ├── 2ad02c71a27b86cc4cf81dff03546a26b3d6aa2e.nq.gz
    ├── 2b7b85ab474be3e40ecf8b2298d23b1ae3e48b42.nq.gz
    ├── 2b8b5fd1e281bf8906111aa2065da3896235b42b.nq.gz
    ├── 2b9be967b3e4fec33b17d9438448685a70a0bd81.nq.gz
    ├── 2c1087709e640a021ab8fea4d03383b98b4a7881.nq.gz
    ├── 2c3f8a9a1a4e4884a1f2edab96521ffed1db4e71.nq.gz
    ├── 2cc8b39bb80ce9b50d5f305e27d0b01c622b2a89.nq.gz
    ├── 2d7ab6f3fbaaed64860a7e16be5b2a44e49c0092.nq.gz
    ├── 2dd195cd27c0b94b6b226a20ef2d234363867b20.nq.gz
    ├── 3060ffe1f84b2b35f4bbc69e93a8eb79517d836d.nq.gz
    ├── 311997c25706aa1dc8440c927eea25e3d4771488.nq.gz
    ├── 327dfe7b2e7c388f5f02fba4bfa6613370021fb5.nq.gz
    ├── 32ce76caf4db64829c0902a502374f4dd715113c.nq.gz
    ├── 333ac21adc48af9feee206f3f2ac37f35090437b.nq.gz
    ├── 34024822143f374b943565c9692cce72d94ad5c7.nq.gz
    ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
    ├── 36aa2f6a0965e36abd71e5a2f29837844f883386.nq.gz
    ├── 373fd111d3382e8dcc133766dab270a457002cd5.nq.gz
    ├── 37bd7c9cedcf8da0a8a5158dca5826b6cdcc89e3.nq.gz
    ├── 37c30522e1d8d3a1a6b84d458293c56726597d95.nq.gz
    ├── 3892fc46dab6ae640937991ff848d571070140e8.nq.gz
    ├── 38d2606d5ad56e3a9fe5c5d63eb3ca7a8ff366a5.nq.gz
    ├── 39338aa085e2844772a255446a50dca918901a5c.nq.gz
    ├── 39eb4236c12849c2e706fb2afb2a053bfff0f808.nq.gz
    ├── 3c97340e03b4f3822825e793cc8dea6adb7c4458.nq.gz
    ├── 3d05f0bca28210d85ab1da4650a96bca65da9c1a.nq.gz
    ├── 3d20b7c4750aa550618f8ec2de9eeb480acd59df.nq.gz
    ├── 3d35f697d7e88dc1ade357ae0fbb45177bf3b2d0.nq.gz
    ├── 3d55329fa8a7337d4bea0fc01231770a781ecdd9.nq.gz
    ├── 4042e90dfd55a6e04153a5705ad8d88750d47c6b.nq.gz
    ├── 42c223d36faa4364f50e2cf50c54d1842d27f5c8.nq.gz
    ├── 430e6c001a266da5d0431fe427d0da8f9ffae50d.nq.gz
    ├── 431bb7c66c0f20ab1aafc4697f60cfd046235d97.nq.gz
    ├── 435c5e4e1a54869c571bb9ae72c35effec283325.nq.gz
    ├── 4411a8f91dc065920d97e225b9267a62a6928e6d.nq.gz
    ├── 450c1460a4c1829a656539dba8102a4bf43804aa.nq.gz
    ├── 450edf940456dd4f89867eacda8b403d13e682ed.nq.gz
    ├── 45b339c01de8c8f059b77872f32d3e918ecd155c.nq.gz
    ├── 475d523bca44c73eae6abf71c03cdfdc7a2c54a4.nq.gz
    ├── 48086a6d7b1b0bb648665209bbe4116f0bf28662.nq.gz
    ├── 4889def08ba8efb97e3f3b669e251086f308c642.nq.gz
    ├── 494ebec32eaea7003f1c71d7af80658161219d4e.nq.gz
    ├── 4976c5e4cb3bc48cfcf75429302a2f78253619b1.nq.gz
    ├── 4af4846d52b08a49f5c9132e228ede78425b3094.nq.gz
    ├── 4b7a01e9ba64b3a7081e0ed1d5b7f98976d8fe31.nq.gz
    ├── 4c834cea5e8e32d2327713b1958c877d997b5c3e.nq.gz
    ├── 4e15ed3f1ae64ec9b1c0d4fb8582216a735eb5f3.nq.gz
    ├── 4f054afd679b288e64627181430d8da33cd8af80.nq.gz
    ├── 4fecea8ec884f57f0d6f4b4959cf1a0deb41097e.nq.gz
    ├── 4ffd9dfe57273093de14035fc963b04b5bdec4e3.nq.gz
    ├── 50ad5a270c2821cfc0a76666e051c5273bebd0c5.nq.gz
    ├── 50e41879584f86eb3c7647ffed0e665a480be576.nq.gz
    ├── 524f22cdee81059a71a90de7643442f7acdf5d82.nq.gz
    ├── 5288234ba3606fe7b3d4d2d5a6820ebce5e0279e.nq.gz
    ├── 52a9c3483a0b69998558e40edd80c6b3ed1368f6.nq.gz
    ├── 53483e5a1794d74220350a2ba4ad4de8520e3a79.nq.gz
    ├── 53e12a58611838561092fbe59164b7ba619f6ed1.nq.gz
    ├── 544da5d86a1a78e14df37ea3eb9c861b96f5d95c.nq.gz
    ├── 5483894d305ecab7a571232a9470c9c5bd1f637c.nq.gz
    ├── 551e3395c0ed302e913a4005c7478df7e3346018.nq.gz
    ├── 5681d3949a281409d0437f7afb2cd05b95983944.nq.gz
    ├── 57ecac53090d4313cc0f7dea80bd0ea6658d036c.nq.gz
    ├── 57f0ca0a2db0a7bee68a4127c0561b7add58575f.nq.gz
    ├── 58930139e8e9fdd17d0a1c2421bae39325538532.nq.gz
    ├── 590738b7c77e480f079a738584c495a6f213e11b.nq.gz
    ├── 59fd836170d5d59f304d1dd598db4fe794687021.nq.gz
    ├── 5b08311561e9121f7f50ac6a251d57e2de7cb5bd.nq.gz
    ├── 5b3274c09b7ba8421e03b93f04b4113cc7af9daf.nq.gz
    ├── 5ba28660c71fa6fadafb118e812faf431b770a48.nq.gz
    ├── 5c0fc91818527f3d0a181c1c3ee42e1158e2fbdb.nq.gz
    ├── 5cfc9f8664509aa308516e24b4c10a02e714bcc2.nq.gz
    ├── 5d11b9d94e80ed86be8302b46243eafbe7601550.nq.gz
    ├── 5df4a1acff2fe8fc88ba7834277104a9d2007ff9.nq.gz
    ├── 5e4251f206bc9cbe7c602962ce69f3e69ed8c431.nq.gz
    ├── 5f0ad5ad66644919b2ae6a73de72ab00a85f0576.nq.gz
    ├── 5f135739e5206e58ddba45bfb1432793f891ef1c.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 6046eb2761cd59ab68b8f225dba94d402f0090db.nq.gz
    ├── 60c21efcb80718ec13488f57d3df349b488ff26c.nq.gz
    ├── 625f252bc87801f22781a843cdafcd0c2723f120.nq.gz
    ├── 6300426558859ad4046eb36b2d11473efb6444d1.nq.gz
    ├── 6499e45c50022b063a06ec756b310f91a4453e8b.nq.gz
    ├── 662943f197287d6a8e0f6b0a5156a41a9f8b34b8.nq.gz
    ├── 6631c1135c62ce6e9c14c218b342cae9744ea784.nq.gz
    ├── 68a85c51984b9e6e29e59ebb90e5f51de44b1279.nq.gz
    ├── 6a8577176e44c142139fabd7638d7df8f4fbc27e.nq.gz
    ├── 6b8a01133a3192446c5a0272043537417929990c.nq.gz
    ├── 6bcfddf70ecad4e04c1009207a6f53249a89e862.nq.gz
    ├── 6c5f6f6419ce4cee09f0a51779a8060b47c37090.nq.gz
    ├── 6d2ed197bce4f872c50e1952628816b72eb59cf8.nq.gz
    ├── 6d8faf442a017ba32fd367c23917eff2a90a8c50.nq.gz
    ├── 6e57481614a38c5ae375d6f8f43653e12573669e.nq.gz
    ├── 6e8fceadbf6168ad9e37840b7c6c2243dde1cb29.nq.gz
    ├── 6f575b273ac4fb04e9cd05dfcbeaa9b6e3ba702e.nq.gz
    ├── 6f780c673df397571c543ed57f92e4f8ecc33dd0.nq.gz
    ├── 6fa6748e514f935bb264d807f4844930eb5f310b.nq.gz
    ├── 70c8dc484c25466ba73c57a9cd24fdc2b38bb7f8.nq.gz
    ├── 71361f388a01bdad9d96ae28ed7cd977e51abe16.nq.gz
    ├── 720562f81510794ad4a01d39b251a37fd6914a23.nq.gz
    ├── 728af2e69336c3db4747a73e0a8f6cf5a91ab700.nq.gz
    ├── 72b18aa2f77e8166c1134c798b083e109f70443f.nq.gz
    ├── 743a7cce48f357c3593e396251c7931fd4b1b435.nq.gz
    ├── 74c27b9a349a60bf57e5afd932302f55188d9bdd.nq.gz
    ├── 74f9b2c571e128bac559546057677341b6885a05.nq.gz
    ├── 7522dfc8fe3aecbac2a5b6e529fe461b5ef03bdc.nq.gz
    ├── 755aea25093dd0048c9bb251429d1efd7cb4062c.nq.gz
    ├── 75b96a50f9b4e58f7915444f161034b464569ae2.nq.gz
    ├── 760da1e808891aa6a8b2c73759e2f2420d822f10.nq.gz
    ├── 77325a15a3f1716d4f2418063dd75bb9dd915aee.nq.gz
    ├── 77b5a4966e10540ee68ae4dc7764fe587e870d66.nq.gz
    ├── 77c1ab1e2a5bd40ede125c74fcf6242794adfa95.nq.gz
    ├── 78353d685a0c03892a5db77734228ac280cf594d.nq.gz
    ├── 78ae67585809d7e415c61ead50fbb5c963bbf61a.nq.gz
    ├── 78de7a518e0e96387c37b2f16a6da28cfbc8d4f2.nq.gz
    ├── 78e9de9913bc5e9086b264c1252892d59844790e.nq.gz
    ├── 793147ab3a2f9e441e35b5deb62047c5906c346a.nq.gz
    ├── 79fdfba09fec61be06fa061d3bc17e6f8f57e63b.nq.gz
    ├── 7c78421401206ef83d9ac5289f1ad986da169d5e.nq.gz
    ├── 7cfd9b69109207566510e136a6d1906b54f43960.nq.gz
    ├── 7d8df6425980e740991feed41c43013f5e24162b.nq.gz
    ├── 7ee379767c3c6c6336c7dfb14425b3d676ffbd54.nq.gz
    ├── 7ef7f21e11b26fa32325995df587d0c3a17c1790.nq.gz
    ├── 7fad41c523f6a90269e950b8ed89480b3a66e499.nq.gz
    ├── 7ff72c27829e081880b1f41c34e0f713598697f5.nq.gz
    ├── 7ffb13595512f0083391a0e418fc75e462a4c472.nq.gz
    ├── 8059c8a83b90e6c33e19dbfa0c1f3fcdb64593a9.nq.gz
    ├── 80985c48e39880d6a5e6ca29bb2d43b5f372cd26.nq.gz
    ├── 80e425487141275d6c6490100fa0528a2f27ece7.nq.gz
    ├── 81f5f113b9d2edc37572b3fe3a9c4bdfc37df1ef.nq.gz
    ├── 826adc2e3c8c5e8cd016c31eddba59b82ac0c6f3.nq.gz
    ├── 8287d3ab18c57bdbc3455d930fc52b64f8ff8aa7.nq.gz
    ├── 82c29c5a9686c3a2b0ae15d154af5b9e88118fff.nq.gz
    ├── 83a6c3c48f0e21bad4d28cfccb22ccf4c77a4f46.nq.gz
    ├── 83af45ea1b095620121e7784c6795ddd724fcd36.nq.gz
    ├── 84991f1a50b37844c12cda4af2b556f3e9ad7fa2.nq.gz
    ├── 84a8bcef124a4d92ef41d59a96c085fa8eedacb2.nq.gz
    ├── 84d149370c9e5f6466ba1c805e8e086a241e3a26.nq.gz
    ├── 84e613e6489a0ec32b124e5444856acbf74eb214.nq.gz
    ├── 8529c3002836f52258a472cbeec5df2bfa55d76c.nq.gz
    ├── 85ebd4a955e6a134776dbd48a249f209f9c9f47c.nq.gz
    ├── 85ee056a34b933aba9a3c058b8c6e297ae17e38f.nq.gz
    ├── 8654da708de638c98d6d165ff39ec90af35db982.nq.gz
    ├── 867c86605a9a5f09bbceb7031bc89fd22791ba66.nq.gz
    ├── 8ad3b56680a18d6c92717337b26357a9037714ac.nq.gz
    ├── 8cdc9ce19a8f81ec2a868b8bd74e71691e7acbe6.nq.gz
    ├── 8e6677718b7be5aab745fc8b24633e370958ff24.nq.gz
    ├── 91d8939a041c82be7d1925be0bcd19c9786f6523.nq.gz
    ├── 96f8b00d911a721dcdf09b9b717832a640f478aa.nq.gz
    ├── 98b6b61ec77b7f4425bb391a6ed39b75e8158b9e.nq.gz
    ├── 9e5a7887df4d8c28c741d8930b4fde7f716d7799.nq.gz
    ├── 9ee0d0fe930a8f6038c1300a7fa2ed3ddc3427e6.nq.gz
    ├── a1979c8b04d74fae466ac738674e244220755e97.nq.gz
    ├── a2254acb681b90ca2d335271e0f12f5125ff6220.nq.gz
    ├── a2e2d1ab7a26cc72ee102d6f19cfdb08f3d3a207.nq.gz
    ├── a362df5641e8be0e3fab5caee9cba8d88e1f0197.nq.gz
    ├── a3b915330eaaa5bf62eed03d9041c3259361b88b.nq.gz
    ├── a52697b47de175e31b5de15447872e7454b0a28e.nq.gz
    └── a54fc0ee94e540849d80296f816cdbdb14bfe906.nq.gz

8 directories, 200 files
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

[tox-dev/tox](https://github.com/tox-dev/tox)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
