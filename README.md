# Repolex Knowledge Graph of lululxvi/deepxde

RDF knowledge graph data for [lululxvi/deepxde](https://github.com/lululxvi/deepxde), parsed by [repolex](https://repolex.ai).

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
rlex download lululxvi/deepxde
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 99b6620386d18cefb1549dddb7b7fe468cfad607
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 99b6620386d18cefb1549dddb7b7fe468cfad607
│           └── chunk-001.nq.gz
└── blob
    ├── 006c2328638cf9e69725b2f32e591827777088de.nq.gz
    ├── 0098e4098c1df61b009137c60e3a506f8ccd27e2.nq.gz
    ├── 00a92321c118d330b95c8db4a4b36e005adbfa88.nq.gz
    ├── 014f450572bc09f9276c51d97598d950fb5c8b26.nq.gz
    ├── 01c382159a87a34b330d192dc08f4967bc63f729.nq.gz
    ├── 01fb20efac25311d7361388cccd1d524829a16fc.nq.gz
    ├── 0303979288c6b14659ec9dd64b6e50155ccf0bbc.nq.gz
    ├── 03069a9d23b38e2c018c9f8e2f2c77a503270790.nq.gz
    ├── 0460e48eca95bb47bb162e470234718354767338.nq.gz
    ├── 04810ee7dae07b60e320976b6d27ec8ccee79cfb.nq.gz
    ├── 04fc984ef18cda074c6c04edfd84b3e842b716df.nq.gz
    ├── 08e56b38ae398864250f7b4caa7d26a321e4f451.nq.gz
    ├── 0a3dc2777acb7e770903c2f8b2efe4caa8472ecb.nq.gz
    ├── 0be809e9291bce2f68cf540c7b8d85dca69a2731.nq.gz
    ├── 0e4365ad980760e89a52f992557e37774194dfe2.nq.gz
    ├── 0ee871b6c398b7cfd15e78edcbfd047d6fba8489.nq.gz
    ├── 0f407beebd4d387fa4a37b4ab06858fee3676417.nq.gz
    ├── 0f98d886488a544ad0e1178c0c415254064b7ff2.nq.gz
    ├── 10cf42f3717a1b1d0e129b18e88e17459b9a1973.nq.gz
    ├── 12657782ee1d5ce8b669dafde41fa9400bd12b49.nq.gz
    ├── 1290a274a5b28a832ee66801284c95356a4cb6c2.nq.gz
    ├── 13b21cfbc45e45a18e709b17b7d1a8e77188e6d2.nq.gz
    ├── 13dad9a0c95c3ef9b6804ceead6d147ca52fdc66.nq.gz
    ├── 14cea776452619bb172d256ce48ae99c4099108b.nq.gz
    ├── 1578d95faac98f875d9736a72c6d638c13099a56.nq.gz
    ├── 15dccd679ea1e5d7ef89b5350fa531729a3a5c0a.nq.gz
    ├── 194f7b42fc89c17f90036cbd8893bf4de40a08db.nq.gz
    ├── 1b14fa035b4e55f537e0f88ed524de8a77411840.nq.gz
    ├── 1bd9db137ac7b07c2fcbebca36e8d1aaaae3e665.nq.gz
    ├── 1ceb2fd7a282809fe2f11782ea439b1233553ed2.nq.gz
    ├── 1cf6c9989c953e04aef92fa07fd90bb1ce7e9057.nq.gz
    ├── 1ee1f1c8d377a4148687a7543d455985f71cf0f0.nq.gz
    ├── 20e4afbd681e6a2493479e0ab3e0a75261267338.nq.gz
    ├── 2491c62f2f7ef30bb591e850fd50eb39cee97d38.nq.gz
    ├── 2617d4be2746ea1689e04b9d29f0217ac1899a5f.nq.gz
    ├── 266c174117f45a9469f0742e445a9b93df04dfa0.nq.gz
    ├── 280b1b3f7fde10700b513bcd24e30418d6419462.nq.gz
    ├── 28373a7c4636817cb7d33cb5b9c44e57bab11944.nq.gz
    ├── 2960d7f9c592d63811304c55d59c09dbaaeb76b5.nq.gz
    ├── 2a36e7fe8522f9696c1ee43229f0543c15481144.nq.gz
    ├── 2a81b32d731526899c53c072a0977225185a33fb.nq.gz
    ├── 2ab0433c06b2415ed73be8897c822102cceeeafe.nq.gz
    ├── 2cc1f01d107499263a4930ed5dd7c7e0a201fbb6.nq.gz
    ├── 2d9bcdf35b54fb8e146a43d2fa470ed868bf6f38.nq.gz
    ├── 2e7c76b92da07e06eb9eea5adb2f566c237d3bb5.nq.gz
    ├── 2fde047125e893a6dc90ba7d72242d3a8f58c6ba.nq.gz
    ├── 3024174d17c18c535735e6bc48ca73097fa03303.nq.gz
    ├── 314bc902678809b4134fee96f7165ca35dcb8fb8.nq.gz
    ├── 314d54d7ba0e50eb09f649512deb37be2a8b41ef.nq.gz
    ├── 3184fbca3ec03766e4cc221b57762d21378d4b0e.nq.gz
    ├── 31e191b7f2779912e8e333f9c4c7bcd3df00a0db.nq.gz
    ├── 32e39d0ae0fe79fbce130e33764bdd81fc6a8822.nq.gz
    ├── 32ed2ed910fc6cba89630e398fdf2616170e193f.nq.gz
    ├── 352f4db0b5375d35521e8e560c806e11a868e525.nq.gz
    ├── 355306afdfceed6675b486cded0b32cc01ec8a45.nq.gz
    ├── 35ab88d2473fffc75d0279a40eb1af3a12a074e5.nq.gz
    ├── 36559707542c30d24cd26be7548abf2915eddf90.nq.gz
    ├── 371d4ed0d9bb4e83aa59317564b044b33bf540f3.nq.gz
    ├── 372a145bc676f034a02d09e1db58bbda341db123.nq.gz
    ├── 374038e8fb0e50529366957577291eb7dec07468.nq.gz
    ├── 3859d7df492bed7bb3f965ed0d55676d0b71ffb7.nq.gz
    ├── 38ae2806c627005bd1560028cef9a234376f46c5.nq.gz
    ├── 3a52a1bfd6322c69d4232c69ff07c371b5dbb809.nq.gz
    ├── 3ba744f2aa68d5c0784e3a0c3e825878db868b38.nq.gz
    ├── 3d42ab3e5df15e023661111c2c425c2b66503d5b.nq.gz
    ├── 3f2933edd1cc1763ff8ffdde21579960a288db05.nq.gz
    ├── 3f2e5b3cc28ed0dcb87d380716630c96ae2d044f.nq.gz
    ├── 40d955878db34db797d0285dc21d48a24c38364c.nq.gz
    ├── 41a109b43c5bb1e6e0372cb30714e10796919d99.nq.gz
    ├── 41bb19b86e868062f8d448048ac663fe97716bc3.nq.gz
    ├── 42797a3d151ba74330fb8cb7d2697975fa1de797.nq.gz
    ├── 4350e44dfe6d9cdd193beaaceb053bb7e8267302.nq.gz
    ├── 4386bb781000ff418f808f582ba6306bfa540449.nq.gz
    ├── 43a190aba2dcdd88c4e572789a50d52e0a7ebd4d.nq.gz
    ├── 443d02306c9d8f31afad01bdce26d5e645ac2f4b.nq.gz
    ├── 44d72aca2557ef0d69ccef9b2df5f0223376617f.nq.gz
    ├── 45f73db1513ef599c8a236d26faf72815c3700e0.nq.gz
    ├── 4607754ccd4611d57de3105f6e5c7e065c5e55fb.nq.gz
    ├── 461eb2ffbae35d29f3e00025b7e44e349b044db5.nq.gz
    ├── 46efc84a5fc0a603bd63adeaf5d50c81a42cfcb2.nq.gz
    ├── 4725dda05b60c3e6baae24baa3b0356474dfebbe.nq.gz
    ├── 47396af55c0a96cb8ad1c9d16b5616020fd9cbc2.nq.gz
    ├── 4741413c81e8f01250745f20f70c13bd48a89a7c.nq.gz
    ├── 47922b920a925e1c1cd51483ffaac7b9ca2f07e7.nq.gz
    ├── 4854187e8d55e0345fadc46fff5f8899b9977e45.nq.gz
    ├── 49d4dc65bda25bf1af7ee8a9f9a1ab3cae6bb0fb.nq.gz
    ├── 4a4384a8b22e2fe09696f590c8a4f0110f818560.nq.gz
    ├── 4a6484dea2cd90368bc809b2078256ece3069907.nq.gz
    ├── 4a85d3bffe51223832481c27fa72665dd03e8ba1.nq.gz
    ├── 4bbfbdb9bd05afbb5c164233d40c67cc5cb64cbc.nq.gz
    ├── 4c290bc9eddb7eb33b15927cf6cc617b152f230a.nq.gz
    ├── 4c9689dd38667285263cbcc6c9982f09c2b84a70.nq.gz
    ├── 4d94e44bcc4e196076d8b12522a4bb65a709d529.nq.gz
    ├── 4daedc401efe57c0f58efd91bc95ab47dfa2365f.nq.gz
    ├── 4dcbe8c2efbe51e000931e95ad288cde2ce340b2.nq.gz
    ├── 50ac09242e8151279a4fa6fd44e0ed42624b53ce.nq.gz
    ├── 50b1d0064d12b12c76c794a90e96c1461d5f36e8.nq.gz
    ├── 5221e478c362541c60397bbbd6baaec64afed74f.nq.gz
    ├── 52270260b1c6bb9c303a125a7e006316c14459ff.nq.gz
    ├── 528eccdb5e72e3ee2e8dc35420d1193548c682b1.nq.gz
    ├── 52ff68e13999fb7b55af45104a8d1f6f3b0e52be.nq.gz
    ├── 549fae1e0205431cddd3642b74c2d97ba8f662f3.nq.gz
    ├── 5500254bbe33ce07e2bb7a3bb09e90adb9aea98d.nq.gz
    ├── 554044ca8998311a5526dd13c480aeff67bdbf3b.nq.gz
    ├── 556a152db0ae7858712a6eef1c1eb99bea03893b.nq.gz
    ├── 55a91684a7efbecf425362e253d2f06e94cda791.nq.gz
    ├── 5861b23d40c7dcab28c0354d0e5ed0334e2f6b43.nq.gz
    ├── 596af4191f08de8e677c6663295bdaa84b502162.nq.gz
    ├── 5bb34f9bac50990ae0a23f6df5bbb21fcd22bb00.nq.gz
    ├── 5c72604df629f5cc9a728da210d3f0e1d923c2bb.nq.gz
    ├── 5dc9770896c3936db5b5d84b32cc18f63d0cc265.nq.gz
    ├── 5e47b6d82fd2c3a2817602c9577535c9377a234b.nq.gz
    ├── 5f15c79923acc8b8c6d33b70e4357b86162d3f7b.nq.gz
    ├── 5f97fcf2ed1dab66f4a0bc191d66ab1132c7f1fb.nq.gz
    ├── 6001f5ffb04da9e3167df344fb8081ecd32aedc0.nq.gz
    ├── 607a7a4ce6f592b18e3f4e91e6ca793ce6329542.nq.gz
    ├── 60bd6f7bb940bd1f0ffb2696531c9fffcfb4ff44.nq.gz
    ├── 60f2c20c5a24a662537584f29e5f20f1565be214.nq.gz
    ├── 6164d7af08733ae2775166f32295821352f0de91.nq.gz
    ├── 62acf3dc5ae848fc0459c308f639edab3d219cd7.nq.gz
    ├── 699afcc750304fd6c309e50fbe2a90df6daa68d7.nq.gz
    ├── 6a8b6b77eecbff67929f66b44e8c7ab2ba425d96.nq.gz
    ├── 6b4a937e37aa7417f9e341de40f67eed455e04d6.nq.gz
    ├── 6d502b938826d51fedc03530f4e2eae1326d46d6.nq.gz
    ├── 6dfc22e373380af4270b0dd05ee45d9e43d23e0c.nq.gz
    ├── 6f01b0f925ea02e00292fba37d3a5dddc36d4d27.nq.gz
    ├── 701709fbd9f597139f35b12361b7bdf44f3cbc19.nq.gz
    ├── 7057488d465c8cb443fe57414f8b1d6db0b1e5c6.nq.gz
    ├── 713ac9f58cfee89c348501b78c76693f6717c070.nq.gz
    ├── 722f2004750e84859998352308d460f4dd656c06.nq.gz
    ├── 72f122aa07726e0abee2af88867f6f1b3455f4dd.nq.gz
    ├── 735cea8793ff936384ddb088b7219eb0b090da33.nq.gz
    ├── 73d2d56b8cad00d7b915dbd1806ee4073535deb6.nq.gz
    ├── 73e448d1fb16b3f866d70615f2adbe63df35a6c9.nq.gz
    ├── 7451e28060dd54dbf2e3b0b2c393a08cd2010b6b.nq.gz
    ├── 74e6e5723c3eb275ef293600affda4c2e70df8c8.nq.gz
    ├── 7564921bdad06c4837219fd545f99b00358ef1e2.nq.gz
    ├── 777e4d8eae4d5929ced01ea235a4106cc9f76259.nq.gz
    ├── 787f7298f20870a31fed7bf3a0eeb41e129842b0.nq.gz
    ├── 78a805ebafbb83feb89ee045e77e22f35d476827.nq.gz
    ├── 7b384eddc0d3763cc3663eed627dfba006665759.nq.gz
    ├── 7b6883ed1cb45af621381c84acd5a1c73cf3d77b.nq.gz
    ├── 7bbcf7b4411944b71692c31f0ae49a92d3577bbb.nq.gz
    ├── 7c05b50d0e7684f969c1744e75dd7831d536cb73.nq.gz
    ├── 7dd6c89d569c8ea0f71532d653f96232d7052a0d.nq.gz
    ├── 7e20b863df527a46205c1c2277da6d52119978dd.nq.gz
    ├── 7e8db4f41e8791ab15e88421806a61bbd96a2d0d.nq.gz
    ├── 8000a6faacf471c537530805ab29523c7732e11a.nq.gz
    ├── 80b596d5ffd8c20f50012c118feb23664a9e2ebd.nq.gz
    ├── 81de7568a1b7576f7d2e4ccce7da647e0410181f.nq.gz
    ├── 81fd10e74b6e3ba2243e1611664771b5797cfae2.nq.gz
    ├── 847ff272b928540f16e7d18b614b5607c9717381.nq.gz
    ├── 85174215b09202cb033e447b2e37099942adde9e.nq.gz
    ├── 852a6a292def83c982689e63ce8ec54f1398cc4a.nq.gz
    ├── 857788a6d201e1111afb4b69ea4a3955af710862.nq.gz
    ├── 85c24ede9da5e68e6a4f79d8b201cb4c04fbd323.nq.gz
    ├── 873e8372c4ac067a760f10c22089ba963e4bbdf1.nq.gz
    ├── 8af11d62beafcac599a321829ad76b21b77e4f8d.nq.gz
    ├── 8b46d9986d9c9d59a9ec32741154768c892e9dbe.nq.gz
    ├── 8b95347612ce43676b83d5e16073cb9c46d5d310.nq.gz
    ├── 8dbdc7259125036cc10735dd477e58a52919ff6b.nq.gz
    ├── 8ec09fd3238e667808808bb03d2dc275d8ab10f8.nq.gz
    ├── 8f57c3961d149379bead0cb7a97f6cb399e187ea.nq.gz
    ├── 8fc385912fbd12539d99903bb22b71209e4d97c6.nq.gz
    ├── 90c5e8c6a0dc9f2b305f0ad8c6a3ed7534d33bbb.nq.gz
    ├── 9181584d1715a89f16446387b194cbccc8a63a66.nq.gz
    ├── 91b8ceef08a5377697ca31da7375dee332d072be.nq.gz
    ├── 924ce65b75e1f9723f3d7a5123700f06a0115e39.nq.gz
    ├── 925d19b7fc1826693c7568c0b54383909095d90d.nq.gz
    ├── 932032d1e6fbde4f3ccc0d324a2a1f228d007a15.nq.gz
    ├── 93704ec9d011a6007929be2ba94bab2af0e2bffc.nq.gz
    ├── 940e6a6e6daacbfd941bc59513532dda6fd0b3c2.nq.gz
    ├── 9530915a8462c9e95da28f37080b92803f5c3e0d.nq.gz
    ├── 95b4de7ac4d4e2e2c515110447cd9c20213a4cae.nq.gz
    ├── 965b4defd8deae0a7142e4e244e68daf2166cd3a.nq.gz
    ├── 96c5bb2ca406a190a61c38abcd1ea563fb5f9c45.nq.gz
    ├── 98b39bbb3e78bd660b6e0f560d5c4a80ae8fffd2.nq.gz
    ├── 98e0eccd19806fd048dee09c5e11d47dc34a5e1f.nq.gz
    ├── 98e78af3d29b0ec2473f5babedb80e71c623325b.nq.gz
    ├── 9a36dbe02df2cd7e074196ef36e6d93a99f5bb53.nq.gz
    ├── 9ae6a51b9ff5ec80189e0842152e95bef2fe9c26.nq.gz
    ├── 9b88f67d46acfe8b2b230176d459ab99456fd7e5.nq.gz
    ├── 9c4a1f59115e73fecbd3647637ecf3133955b08f.nq.gz
    ├── 9e90b5bc8f5bc4aa60f9f6db34554508755a4eec.nq.gz
    ├── a009f22003e86b86c05705513656885c278803b4.nq.gz
    ├── a110ce8e1478e03839faf5e856e85604a9e631a6.nq.gz
    ├── a14ba796107e1d8776dbc11d51dfd33cf5469cea.nq.gz
    ├── a2223aa1969d21bdc6203360bb35cd0c3a9dc09a.nq.gz
    ├── a28025d59aa51d1de8ae10747f47cda28d7dff03.nq.gz
    ├── a2d7506779ff51334827f5394ea1ea0e9acf1cd5.nq.gz
    ├── a3ac7d0ee16320812f00fc7cc8629586e6aac583.nq.gz
    ├── a4addf14361071eb15d47eb974700ac17642180a.nq.gz
    ├── a4bb4a1edf6d4c0f5f2037d6bef9dcd933e91a06.nq.gz
    ├── a5b5cbbd60abeac68a0bdff14578ce991cb770eb.nq.gz
    ├── a62b567c0e33ec5f2f8f51d7f216cb8532bf544b.nq.gz
    ├── a7b1b39f2df7c672657dd7c72191aeae77162e15.nq.gz
    ├── a7ca57f2f1c05f800475cd4cd0007b963f716bbf.nq.gz
    └── a7e8383e140547b2b5f8cf3893104b3de8ebcb4d.nq.gz

7 directories, 200 files
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

[lululxvi/deepxde](https://github.com/lululxvi/deepxde)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
