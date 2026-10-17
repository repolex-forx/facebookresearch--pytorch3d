# Repolex Knowledge Graph of facebookresearch/pytorch3d

RDF knowledge graph data for [facebookresearch/pytorch3d](https://github.com/facebookresearch/pytorch3d), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/pytorch3d
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 88e182f989c80836f4bd744e0d9cb1852762ce01
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 88e182f989c80836f4bd744e0d9cb1852762ce01
│           └── chunk-001.nq.gz
└── blob
    ├── 02291ed0d1d10fadead34c5bd10e1c47e0971ceb.nq.gz
    ├── 0234ee5124017d74e07f0f29907df663f5bb86c2.nq.gz
    ├── 02830204a6874b8223bde1615fa9ef8ffa4d318c.nq.gz
    ├── 039b1646773a7f113a65efcc7ed22399d5c4297b.nq.gz
    ├── 0486c2ccb4f8b70b63a57d77873c162af487fc35.nq.gz
    ├── 05054f201644d30cd40a8028460a6bae9e0cd547.nq.gz
    ├── 064c518ff317227eca4fd54f16752dc143246422.nq.gz
    ├── 084b59e8dd6ea555d66f07d663f3767ad095c9f6.nq.gz
    ├── 094d22e37b52a1bdeb2ad67a05279c5448c58e73.nq.gz
    ├── 099c20b2b17920c72a638939aabd560a9c36b6d2.nq.gz
    ├── 09ba1d7878df1067ec98db1b8a874a1c095fae9d.nq.gz
    ├── 0a6531a389189ad13c63d1712ef08d499ba1584c.nq.gz
    ├── 0af0bd471b752a1da5519643408107696eb7f074.nq.gz
    ├── 0b554d84b19b8dc58c49e438bc6a8950d27a9e42.nq.gz
    ├── 0c62f18f3f42501fce422feab56ff00361c66c35.nq.gz
    ├── 0c76373dda4a47fc3ffe445a4b0b2136954dc140.nq.gz
    ├── 0cb7382c1650150a190e2e9f253f676ff444cbf6.nq.gz
    ├── 0d46b6a02f6c8005cae0d1d9c83e7b1b5b037ac9.nq.gz
    ├── 0db407585afdb1cec64869311b75f13c135d4030.nq.gz
    ├── 0e9bdf8844f78ef01d467155de87df18c53cdb1d.nq.gz
    ├── 0ef4049e32ed2b28f713e156c807c18923353597.nq.gz
    ├── 0f4c8595c89f878051bff25d5fbe540626acf615.nq.gz
    ├── 10220248a5923ff567cf88a5568859533717f8ce.nq.gz
    ├── 1121a2014ad25d2b4beffee748307472940ac098.nq.gz
    ├── 1175949d46aa77b63a9377bb7f0156d6f99168a8.nq.gz
    ├── 11b29a0779731df0b34c5cd3cb231f4282ea56f4.nq.gz
    ├── 11d1be46c19c0e923c60f7165ac8d032680f834c.nq.gz
    ├── 11ed3d3204b77539a9f02e917412f3aaea79071d.nq.gz
    ├── 1210848f94dd85a73d516c55e969b963e880c689.nq.gz
    ├── 1213ff2625c83b0cf9307df6ececca1f2f279300.nq.gz
    ├── 130b70dd9df439598b348c9a38c3ae3f70efd9ec.nq.gz
    ├── 132d948e1ed26dcc49011f42aafb6646432336b2.nq.gz
    ├── 14187eee279c330ce5291cfd6ddcc7db8a598841.nq.gz
    ├── 14310ada2c094e29ac39cf3a74ef812a57faa696.nq.gz
    ├── 144f38e3686038e4183303d53bec84525ab09b71.nq.gz
    ├── 1467bfd08c190e0527683b4ff3ea01ee211e61ef.nq.gz
    ├── 152b52fc57edf5dba39d4ec179a94e46b24b6430.nq.gz
    ├── 157d04a2328c9f76d459c565aa38878892f9b181.nq.gz
    ├── 1596babb47228068cc3aed6f3ef3b6beab14b330.nq.gz
    ├── 15f199af69ccabfd3da4e6cddbdbe3c036f1be83.nq.gz
    ├── 16505e5478aea0d56fe2755dfd60691b49f5598a.nq.gz
    ├── 17795ae1eb4b6bceb8a9960bc6d7523eb3c2acb6.nq.gz
    ├── 17d90b629b33302b2b8d5aae7989fc0fa55e7170.nq.gz
    ├── 1929a4671ad4f2abe28bf8f2fbc725d5b0d98cc9.nq.gz
    ├── 1a027325e8812159fe34a82abe17d8748fd02f32.nq.gz
    ├── 1a221580a614c2cdffd4b564902e9b9cca38386f.nq.gz
    ├── 1b4a2ef2d17d5a7a2d868b1603c996e2fb3ad7b2.nq.gz
    ├── 1b4a43730db08abb41ce93c58dca5461414514a7.nq.gz
    ├── 1b9b5a0a436643fa705ab35bf83a07ff0767d45c.nq.gz
    ├── 1c842cfe350db46f09c9ac79dcd3bc22965d3315.nq.gz
    ├── 1c9b08bea9e0a4efac7770c872a7aa2b6023e307.nq.gz
    ├── 1d4086ceb6612c6d70d8d79076ef7f5154b0772e.nq.gz
    ├── 1d7f976f41613a24ad7ee5e1a92d30ecf7b66011.nq.gz
    ├── 1df48bee6d404f9f0e4a4f32f0f987272e3a8ef3.nq.gz
    ├── 1e948d930790ada04c78ff2497628f854bd57f44.nq.gz
    ├── 1f3f3649184a00a5711a661a77b722174618d71d.nq.gz
    ├── 1f60f0b9480348a6660b90244600e7d59622470a.nq.gz
    ├── 1f8e3d5d97fef870e819ad897c238cc4376233d4.nq.gz
    ├── 211f46b27a454c5ecc060bc0ae33230df0d3bb14.nq.gz
    ├── 211ff515259c49e7d06bccc2c3e6352ed7ee172d.nq.gz
    ├── 219566128185aac8ca8bd51786703671878223ce.nq.gz
    ├── 21d5f7b15f2651d20050702c071da5c5d081f449.nq.gz
    ├── 224cb550167173c8aebd03324df85a1b8e69022e.nq.gz
    ├── 23459149a756d598f58acf47e4c78266710d2f13.nq.gz
    ├── 2380a7b1879d9b0619743e1dc4d9e6ccff0d2ded.nq.gz
    ├── 23f9e409d2332740ab958ae16f81881400341c91.nq.gz
    ├── 24e7dde7a356123711bf53ce92da87c905d4254e.nq.gz
    ├── 2567cc1d21180add06923c92cfb35fdc7ea02026.nq.gz
    ├── 2798b634ec4fa6c4336289ea3bf887d20512ec2b.nq.gz
    ├── 289233ac08cc748aeafc1cfd721077ce81bfb1f2.nq.gz
    ├── 28cb526e656dea293b12803fc83ae4af42a008e0.nq.gz
    ├── 28cf96462f6cc23fb869d8f30ed09a4f9e684018.nq.gz
    ├── 2944ba84eb6a9dc2a9f33a612305c45a73056e2f.nq.gz
    ├── 296a560d7aa9ec3a13c8da763977c96650610e62.nq.gz
    ├── 29b9441fff2631a0ec7a4e74cbeab9e27e3c0631.nq.gz
    ├── 29cac4b218d9277c23885f7521628fcdfac89441.nq.gz
    ├── 29da4c497b89b2fe3e2e2d5b2563adbbcd6ef326.nq.gz
    ├── 2a0e3e3856895f1c14061d270d1d4fb777a427f8.nq.gz
    ├── 2b510d0fa25cb3d71974c62cfb51dedf820ba5c1.nq.gz
    ├── 2bfe79dc95b240b1565aa6cd0988965660b91eff.nq.gz
    ├── 2c160f97e6524b6eca9d8fad0cb48d5e9f4b977b.nq.gz
    ├── 2c93a46101bc90b859d22f482d1e3c45ac1e3880.nq.gz
    ├── 2d8ea3b2bb10d14175b1f8d87a4cebffa0210410.nq.gz
    ├── 2d9836cf5e0fea6db6562fd867102aa7c8ac5f78.nq.gz
    ├── 2e41cd717f6a439a9c08d76a9d0e4a54e190fc5a.nq.gz
    ├── 2eb454d2f407b6113d7b02cb9c7a6a5baba14722.nq.gz
    ├── 2f2821058bc16a02a1185f9cfe46701064524e56.nq.gz
    ├── 2f349d0dac3994869486bdac7f15892f5acb2508.nq.gz
    ├── 307478fadf02a651ea205c4c70c28c4ff5a7c65c.nq.gz
    ├── 314824ded61747a63bd23f32ba4fcab9044d1995.nq.gz
    ├── 31d0564dfadbcfc79c8cba5f4a68a7d1ad43e654.nq.gz
    ├── 328a124dc12ec2fbf7e0e39e589d111414f32a2a.nq.gz
    ├── 32e726a84fd65bd420cde3db7275539a1a489308.nq.gz
    ├── 34c15cfdc9e26040b97136f753efadcf641438d2.nq.gz
    ├── 34f4860ba850120f59f3f499e21e2a4b429e03cc.nq.gz
    ├── 35c0b8ce7ef8adbd5d66ca401b438b1d5eded3cc.nq.gz
    ├── 37155fae34691442d4f1acb0e47a1563f0746ba6.nq.gz
    ├── 37b18a5f54db09c37da037b878af14b1339d106b.nq.gz
    ├── 38c487c69016e23df223c1a3f5d8ce8f078cd70a.nq.gz
    ├── 39472e179248364adc94bf002fa2f38778b51de9.nq.gz
    ├── 396132e168d609e2b802c53cc47ee9c8dcf16dbe.nq.gz
    ├── 3973792ba318b99246a983cec44aa66957945ca3.nq.gz
    ├── 39b1b3d603ed0cf6b7f94c9c08067f148f35613f.nq.gz
    ├── 39f43a3a9f565ca450fcc7e0bcb976ab40d0f6eb.nq.gz
    ├── 3ae9fdcbdbaed5f9935893953b1bc930fe69d1aa.nq.gz
    ├── 3aed147d30e204078732b3c0788ef378f36cad56.nq.gz
    ├── 3aff617c53e5ba963c014cabd7beb1c2cd61a053.nq.gz
    ├── 3bfa4d147cd91fa6f0a2324e29ecaeac87871539.nq.gz
    ├── 3e5cefc78cbca14945740e135f3f5cdcd17dd291.nq.gz
    ├── 3f0412f576de4dd77b3f2be6a27ff8ddb144ca74.nq.gz
    ├── 3f46d3a7bae20f5bf4fed5df69e751af64e66107.nq.gz
    ├── 3f48a20ed8fc68364eb684ac656356f9d3d5d6b0.nq.gz
    ├── 3f7605553377b66155077531a28daa108e6c6d0c.nq.gz
    ├── 41ccc89ac4d8c3c678989225029674a9f1f47253.nq.gz
    ├── 41f8ecdf008ad72e30ebf7f99bb8db3fdb1edcdb.nq.gz
    ├── 42329dca845bfdcd209896511c16b3dfb3eb9785.nq.gz
    ├── 43211c99d7bbc2fd2d56715489be25f1c5d032b2.nq.gz
    ├── 4382be4f64d58e3c1bdab50e023258f91290c9ba.nq.gz
    ├── 440aafbae75bc917aaea13f7e096d3a5fb73a92c.nq.gz
    ├── 457c16abe10ec24b41fc8de58a454ddfda412bc8.nq.gz
    ├── 463dd2f0702c040fdb34a051cc789b14422528a0.nq.gz
    ├── 46e9754c2a37befb80dd8dd26704dc2a537d8b8a.nq.gz
    ├── 479e692cadd748fa193f974bb3b942522183055d.nq.gz
    ├── 47f8852be662f6233e9c2dac4b9cdb91d82a0b7c.nq.gz
    ├── 4868e6bf2aa202fb5fd77ccb21f7e4699ea49db8.nq.gz
    ├── 48738ca44a3764e66f5661d8f91f5eb4ef12feb6.nq.gz
    ├── 496f9ed15d10877d34b4489a032487bf28eba6e4.nq.gz
    ├── 4a03f95cd09abd3bbe52a7442f851da90eb320c3.nq.gz
    ├── 4a37fbebb6c10fdf3c48fcc30ba069f64d2bc63c.nq.gz
    ├── 4a72c32621d063276a2b765d34e1edd707c87eac.nq.gz
    ├── 4b73e40797d30f70420e213588fa46f110895cde.nq.gz
    ├── 4b91b68f4f000f602a8f23226e035406afac2af7.nq.gz
    ├── 4bf88166e1d36204a9f495437e3141245447e14b.nq.gz
    ├── 4c5b4f5ad5eda1f16d37ad2289fc194157f3ddc4.nq.gz
    ├── 4d8a295417a668b1ef8687f9f15826160dde23fa.nq.gz
    ├── 4f2d4cba34202965c2659d8a6fd373affad0e81d.nq.gz
    ├── 4fc3b6612ab08ecfe064a13478bccc24795f6600.nq.gz
    ├── 509b7241800a49d83369ad83a20a1b72610086f8.nq.gz
    ├── 5104bd71415beeccb70589a4cf1e52cdef6b27e8.nq.gz
    ├── 510589a0c048f1f915da6b0e4c57dfbc3f8f29b5.nq.gz
    ├── 511439cc488d145bda3f3dc87b3764a9bcff31f2.nq.gz
    ├── 516e74848261afe00177186c8deed4966feb15d0.nq.gz
    ├── 5188bb0ebecf72aefb1c2e779458998216e4d479.nq.gz
    ├── 525550bd1c6d8744256b6a070dd220892923af7e.nq.gz
    ├── 52e265bcb2ab8ca9e4d08d90d1dc4fef75294520.nq.gz
    ├── 539cbeaf4f0ee0dc6c6088eb0a4873f4a358001a.nq.gz
    ├── 54550d8aca317d6b6950e8a63ef9a74091623027.nq.gz
    ├── 5466df30d19a62bd90984acdb91847f3c412eeab.nq.gz
    ├── 548d67811cdcc91c30ef12858a6ccda4952c3b87.nq.gz
    ├── 54b5682c97e88774b95f343005bd95f80d8a4462.nq.gz
    ├── 551e94de7fc4d6f7066a1ede176ed6aed8c0aeb9.nq.gz
    ├── 55928c1e141f12753275a8c7f1768fdc0432780a.nq.gz
    ├── 56093a9417fe17aaca9d5b54bed35cf975e88be5.nq.gz
    ├── 5687bc401d83e2e3ed72c02673a6c4e62cbedae3.nq.gz
    ├── 56d3490101455270e11ce1e60ca1a96ccc1e6b78.nq.gz
    ├── 57146d9fd9688cf94012f069aaf34da8a2b25f47.nq.gz
    ├── 574800946c2251fc360828049707b5aae408b2c5.nq.gz
    ├── 576aaa641179e9de9270fca0d6195dfb0486b23b.nq.gz
    ├── 57e9fd30613c58ece2d1c17bba0ecac042429ea7.nq.gz
    ├── 58aeb20fcfd2e5d51ab93054f176f9a2e4962ca4.nq.gz
    ├── 59bb62b8ac83f445c352366e269226cb73fb41c8.nq.gz
    ├── 59bba0de107a9c720681df5abb26fc6f7eed9203.nq.gz
    ├── 59f04d550a416d8aadd194308c34244ee4f0fa4d.nq.gz
    ├── 5a7a1ba1f8e56df0a5ff212e7eb769a0564e7f60.nq.gz
    ├── 5a8870a7f6e7754843706f79663c8187f227b7f4.nq.gz
    ├── 5b24581180c1a06767c9f42aad15ea3319560e9c.nq.gz
    ├── 5b788629d5d73622b6ca45538a5b94eb275a29ba.nq.gz
    ├── 5c35f789f9286b4d9e434763f77953fc282fc495.nq.gz
    ├── 5c638abe0e82ad5d6b5b76b6f5353c057bd2bd00.nq.gz
    ├── 5ec795251ee05bb3bff9425f9d9a965e4d9abffa.nq.gz
    ├── 5ec9b06cc6b4b3928b871f364b8e2f45dee04c53.nq.gz
    ├── 600d7a1afff8a5089ad2d8d8023e195bcaab480c.nq.gz
    ├── 615fe5072b4411405c0f8e3fbf1b78ea9814d6c9.nq.gz
    ├── 616c13031aaa4d6adc312f9f329c0fc0540c2c25.nq.gz
    ├── 625728310174eb5c2f4ad488d3e1705b8565ac98.nq.gz
    ├── 6267ddbf92b36f9ebed9b194fd0eab924ad35556.nq.gz
    ├── 62ac896730cb10ecf0e616b43986a4b9e5c4faec.nq.gz
    ├── 630944877af378f0816781a41f0a8f1020c123aa.nq.gz
    ├── 64a8660912f1215b0ad545b65278f02a266bd7b5.nq.gz
    ├── 64c1e70aa94bbd9e01fd57b790e8bf0e642fa718.nq.gz
    ├── 656e8a830570fd4a1d9c844fbd4ad297b58f2fa5.nq.gz
    ├── 663adeb6a1c070476061a49bc8e0a7b73e4fdef5.nq.gz
    ├── 66b1877ba61cad860677971650815244ffe3e8b6.nq.gz
    ├── 67583511aec2a6bd4dd8670aeb809939a3d2e19c.nq.gz
    ├── 67692817108483d2aa449c8461f7b4adfd9d739d.nq.gz
    ├── 67ad3661ee5253d2d19c22cf46c149af0de10764.nq.gz
    ├── 67b3b27bbff83205fc68de4e08cadfff70aafa75.nq.gz
    ├── 67c79fc5788f1069094bb499726b9c2ae85fd02f.nq.gz
    ├── 6855dc8fad357bfa994df7162e99e6a22f3cffc9.nq.gz
    ├── 6858e7d4eaa4017ad281c2221eb17d2143e3b212.nq.gz
    ├── 6895e1ea5dd0759e4e01c1cbd1956159f9faaaea.nq.gz
    ├── 6923d3a240901501f3b2380d54575979a724b5ed.nq.gz
    ├── 694e3df26de1bdbc82aae29d559d8b074d667547.nq.gz
    ├── 6980afc4a49962760283c46ac415faa5ab76ce8e.nq.gz
    ├── 69e99b9ad9340207bc9bb72e6cc7bbb36b1c2d67.nq.gz
    ├── 6a4513d19f95c7e0107f07c008217c7d1de35e2a.nq.gz
    ├── 6aa472368ab3776444748140ed9d1d78fada9f08.nq.gz
    └── 6ac1a72bde66f104691245d2de4e83c6863718d5.nq.gz

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

[facebookresearch/pytorch3d](https://github.com/facebookresearch/pytorch3d)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
