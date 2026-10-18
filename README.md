# Repolex Knowledge Graph of sigstore/sigstore-python

RDF knowledge graph data for [sigstore/sigstore-python](https://github.com/sigstore/sigstore-python), parsed by [repolex](https://repolex.ai).

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
rlex download sigstore/sigstore-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ee385ac8be192771bff1cc553434b11282ecce6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7ee385ac8be192771bff1cc553434b11282ecce6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00225acb8a344bb16015f9c172c21f3faa557f19.nq.gz
│   ├── 0285be8f8e3cd877402ba537e41015efe3934466.nq.gz
│   ├── 050104c5d7069aaed0c68f673d595dacf9f0b492.nq.gz
│   ├── 058f791bd324a3a06d1736a7ae857579b35d55fd.nq.gz
│   ├── 0669b4beb7774906d197d64f9070de603e28b810.nq.gz
│   ├── 0b242b00fb481e7dbd38602af749332d3c0ae7a3.nq.gz
│   ├── 0b6d133b08884ac1d44684bb310eb97e90f0141b.nq.gz
│   ├── 0f5eb0db6f00902b47ee94252e01e695e40b7278.nq.gz
│   ├── 0f5eb8637aaa299cbd1370b9c5960448d146cda4.nq.gz
│   ├── 0f93b630a8f013e4a67037d74d98e50c87ba1adc.nq.gz
│   ├── 0f9eaa66496d20e5af5c23b3ec5a43b8c6728c8f.nq.gz
│   ├── 0fc5b322ae009605739ca219a636f9fc6f066f99.nq.gz
│   ├── 122945b1532788996604836350260d6519745069.nq.gz
│   ├── 1455cc90f397a8833c8d0464c35c74da18423087.nq.gz
│   ├── 1895b2228f40117ee8fae0b6871dc80948092a37.nq.gz
│   ├── 190c76a6535c9af52f67a6a4b96719689a9187ab.nq.gz
│   ├── 1b6569e764400274cd4e18bd380293925d2b34ca.nq.gz
│   ├── 1e383848135c6a48b8a02dd46866cf3b601cf607.nq.gz
│   ├── 1e563ef094c0c56f7fb39ee21219359a1b4a2b0d.nq.gz
│   ├── 1eab29807fa60a7d3f7ccd740104b32997298758.nq.gz
│   ├── 1f5f2d0b972a5b565cc31845ba9600b50d6c236c.nq.gz
│   ├── 2036e48076e433f3af721cce3aac1f2fc0ae8d17.nq.gz
│   ├── 2237b772ea54b49bfd89b8893c2baca126a8f5d7.nq.gz
│   ├── 224af561a72889470faab49cefd51ff1cd98092a.nq.gz
│   ├── 22ce8c75461f37ed75a37d209540260c30a0f7cd.nq.gz
│   ├── 2376c6708800d1dda2e16be4fb92bd086fec771b.nq.gz
│   ├── 238a8e3efce9a09442c5158abf2800737e28e368.nq.gz
│   ├── 23c7e0e03b530ac9b9e46de6b340063a45544539.nq.gz
│   ├── 24cc58eb22d70706a2054c84f39affda41ac6b49.nq.gz
│   ├── 257799502145bd1d396f68bd6408f00caa3175ae.nq.gz
│   ├── 2b9fa7daa9c8664696ec94d0cc15d4dc5245db86.nq.gz
│   ├── 2dcf2e9347770dd764e8659d4f5cfe702748e080.nq.gz
│   ├── 2ef2bfd02375bad107e089c9f6ff8520a4c75dfc.nq.gz
│   ├── 35f74a572261ce578b8210f12f14baec220ab700.nq.gz
│   ├── 36f49f8ddfc12cd9f47e802ce7533c57a9a17ac3.nq.gz
│   ├── 36fa375ca4caac319da0e8141ed109863111f552.nq.gz
│   ├── 37452281f0bc3f331898730226937a6b70d15e1f.nq.gz
│   ├── 383dabff272c58b2430b7465cf9fd183f7c51f56.nq.gz
│   ├── 3882b9291ac0f878bb5184ad2fc853b9b4202ffb.nq.gz
│   ├── 38a74a9afb312aee2726b63e949f5614600049ec.nq.gz
│   ├── 39275ba82bba43cb9835ee6711f6c3a8b4f40a09.nq.gz
│   ├── 3a816e48dfb55649879838d6e5db7d6a9cf606ed.nq.gz
│   ├── 3abca867a67362c63645fb12da247482c8bd7083.nq.gz
│   ├── 3ddba1455f53e4192dc920ae07135bc909ce0f68.nq.gz
│   ├── 4234e16c33abe295fed969e0b112890780700068.nq.gz
│   ├── 42af3d639d2cc0afc0671a77ef22b029dc2fe822.nq.gz
│   ├── 42f25dbd1e98a1e14f2e5e0f9794cf573d89bcf3.nq.gz
│   ├── 4340ee0076a5dc803a75c85be8fab75551b72cca.nq.gz
│   ├── 464f4e4d3c6eac39eea6b77506a0b1071a26c2b0.nq.gz
│   ├── 4681dafcd8a72e8a1d326c0fa1d7eed823aa7d8c.nq.gz
│   ├── 46cf78e8db73d7d0a9d0b7248a30dac91f2a8ccf.nq.gz
│   ├── 47a5becff7e8c549bbace982fd234d166ad87531.nq.gz
│   ├── 487b05b4999561ce4c150307da3d1ee8310b2ea3.nq.gz
│   ├── 49afb5c35a24b6d0fbe3fd158e8f615b31058fae.nq.gz
│   ├── 49e389bbf57ae488b9281beb345fc569bea2457e.nq.gz
│   ├── 4a23c7e6577e1b12f00a61f072bc380f88ea07c6.nq.gz
│   ├── 4ac2ecef5ce13381596e607f73a81fff79a5b4bf.nq.gz
│   ├── 4e79be8f2da29d3a36f26ebe8a984abcb8594833.nq.gz
│   ├── 4fc6b1c6ad8702db361e41df3722ac64d25abb9a.nq.gz
│   ├── 50551154f92bc58ee546d8663c62a922cc2b2b56.nq.gz
│   ├── 50bdad7689e2333bcd8793cbfff2f6de7bd31a70.nq.gz
│   ├── 51154f1929dc869155d21f6028fa53ebe9199ae1.nq.gz
│   ├── 51c9c73f20798dede878e9b28751a5ad4cd2fcac.nq.gz
│   ├── 5228cc0be594d88ae105843e16ebcb77b087965a.nq.gz
│   ├── 522eac7e15b2ce28bd2325930b00f461740bde35.nq.gz
│   ├── 5389ba242ccc768410822f3bf6b139191bed4943.nq.gz
│   ├── 539ce32275916a83aa2f25a394b859171fa53791.nq.gz
│   ├── 548303b3f693ed363b7e0f645d596ef2dd74c93f.nq.gz
│   ├── 54a8a72fa8d8bcc623e39a9e591b450991d6bea2.nq.gz
│   ├── 54b1edf84b594c09a221b750516fadb88b0d0e6a.nq.gz
│   ├── 55115df1025e64a6be12548bb1a1fa09451fc7f4.nq.gz
│   ├── 5519b417cfd70bc97b2c8106e4e0258b467bb67b.nq.gz
│   ├── 56e686fe626c5e2484ed864f4cd5db27e95631c1.nq.gz
│   ├── 585b0e4c6f11ae4e82820a4792cf1b12aaddb877.nq.gz
│   ├── 589d16fd434ccf7824cba9af16d3d40e5970ca0e.nq.gz
│   ├── 5a3487b59f927c4cde72ba50cdb2e2d318f5f922.nq.gz
│   ├── 5a97fd42ca9cb686d718f2112ef8e2a117fd1f72.nq.gz
│   ├── 5b5e0f2fdfd3fcd6d6461e13511d1bf775f66ee7.nq.gz
│   ├── 5d9167671627fd65e0df43c0c59e635c34cf1d83.nq.gz
│   ├── 5e897d322eb5954495fbe9c329de2dd399323fa6.nq.gz
│   ├── 5f2c003d6d169bf7351c8368da9172aa978e5e21.nq.gz
│   ├── 5f422581f0ab0dc48a046809d0914c31057c7d22.nq.gz
│   ├── 615ec05aa7644abfce7eb13ae01680a619e3f395.nq.gz
│   ├── 617fb8f03b3a51769bb55bec129402cd80a07eff.nq.gz
│   ├── 628fce2c63d05ceb02fad350e9e7fc8d437179a9.nq.gz
│   ├── 6335b31e793fb1f7f3dea6a456136a65081350fa.nq.gz
│   ├── 636e03deb6e5482461b1e33dde0808a4c3fec437.nq.gz
│   ├── 64d291e93ddd7ff663e83e8442d33bbdaa293df7.nq.gz
│   ├── 6510f1bcd8fe5a628ab5f90f23c3bfc5268fbe9f.nq.gz
│   ├── 66ae2b79fe26168969de3ce24d7e185292b1c935.nq.gz
│   ├── 673ccc2dbac99ce47995bdbf113b1ab241ff81ca.nq.gz
│   ├── 6746354f05552bb36ce9dfc2d19a90f1bd379093.nq.gz
│   ├── 68c41a690031f3e686d02d7ed5e152426daa6d12.nq.gz
│   ├── 6e03bf7e4652f3f912c6a26003f2c6784d1ea188.nq.gz
│   ├── 6e5366882fbb3a1947574d85da01e318acbbf5fd.nq.gz
│   ├── 712655c360f45232c95efc4b0d8ed15613f15b61.nq.gz
│   ├── 7573b6436e819af0b81b32b9b7bb9a6a170578d9.nq.gz
│   ├── 757566245b5ae241fcd588254bd73d6b4775e55b.nq.gz
│   ├── 75da5114f782f4c229bcdd61eb0fea36cd89a88b.nq.gz
│   ├── 780a1d89553826c07eaebd304b7c6243e261ef3a.nq.gz
│   ├── 7992807df7d84df28ba6b1a7e7fa20280c85cbac.nq.gz
│   ├── 7a30ccc096efed1b697530c32f84437e1f145318.nq.gz
│   ├── 7b9948df90e28b37e8c6bbf911e9180bf8f93b01.nq.gz
│   ├── 7cac971c2814c01e784d090d914caa990ddf906e.nq.gz
│   ├── 7cec954d0856eca0ceeefbfc756feb9aad48a588.nq.gz
│   ├── 7dccb6670be977cbafee71087176dad6cd87e826.nq.gz
│   ├── 7e34d5cbe860213249aa166c7d8d3cfe473d0ce4.nq.gz
│   ├── 80c3255340b6c5788b0f3886df6889caad45e2d5.nq.gz
│   ├── 81a2bab9625d2fdf7eadbe54e72db3c3ab7b3341.nq.gz
│   ├── 824c0cb6267adf2fbdbff075cd2c8a4b1a3f57be.nq.gz
│   ├── 8267f8ff94fdef01b5b5e34689fc57e2c0635738.nq.gz
│   ├── 88b5addd0ed06c1652b2bbd9bf40f3d830820a3d.nq.gz
│   ├── 88cb71fa9e400e62c1b904a0d332ffea2d7ee1c6.nq.gz
│   ├── 891d7f87a61a300c684ff7f8e7e054e5c5e2af7a.nq.gz
│   ├── 8d0585ac780eb51469215bf8b74611b4ff892d86.nq.gz
│   ├── 8d1b244d13555428eb4b56017d8a54545a20c0bd.nq.gz
│   ├── 8fd8ab5c64f693618b453363ad6f7edadeab2203.nq.gz
│   ├── 90d5a0f1cf1f55b14040c5a8aa27d9ca046caaf9.nq.gz
│   ├── 92e9fbd8ef1aa16ecc05eac8c87d983a98234ace.nq.gz
│   ├── 93f327f57fd1986c7e5a43645de0db2deed5c66a.nq.gz
│   ├── 95c8fad88ab61dc6927d7c96d96960bd32f52699.nq.gz
│   ├── 96ad56d54b3995b96697d0b19cca9de32463b51c.nq.gz
│   ├── 9a7064093507b51097f2f2e9540378084c9f93bb.nq.gz
│   ├── 9a75e028e2de8c2eb31c068899253ab2ab631751.nq.gz
│   ├── 9c8b1df08c542b68bad9b6b4a45f5cf29c1a7158.nq.gz
│   ├── a06a30ccd03138859f9438863e492894b84bbba3.nq.gz
│   ├── a21ef7ff9533b33e1078f8fb0baad990eb3edec8.nq.gz
│   ├── a29710fc7ee8c4b5422b8164f7d196f2927f94ba.nq.gz
│   ├── a4ce0e005595d72dab5767b2800c3353c6539920.nq.gz
│   ├── a5fd3ecd1fbe17d238d32c42d13d6f5bc060cd35.nq.gz
│   ├── a7d3cdb9b61f66ca13f69a2cebcf211aba77656c.nq.gz
│   ├── a901a4f182804e77434ba33ca5dbb6e1f5d66050.nq.gz
│   ├── abb1234f613f1f2287b640f2a329e6ea39b594f1.nq.gz
│   ├── abe0617c70d7cbc27338fbe9a2bc092fd96b2ee3.nq.gz
│   ├── acca7405a7be15037aa82e7ddf3a56e3effd4b10.nq.gz
│   ├── ad1ddbf040d77f95c899fc8c535d8d1d34004715.nq.gz
│   ├── aeabfd373a4cd19baea8b09ca5c2db64a5f33863.nq.gz
│   ├── b1f05e42a2d8abf19a61c07bfd0807a26f5b0bfa.nq.gz
│   ├── b22f0a809cc99fcdc825d6f7c4aefa101460950c.nq.gz
│   ├── b5680adc247eb55431e020dd222e24aa64ceea6d.nq.gz
│   ├── b5cad65280605a4dc2ca27c518f6952e962774c0.nq.gz
│   ├── beaadec8d8e704f29aea5a63c885e57c67802906.nq.gz
│   ├── bec1fa036ac5668850d63528d094d9577589771a.nq.gz
│   ├── bf00a7f61fbacdcfe94fc3c95b05b75f25c886fd.nq.gz
│   ├── c077037876ea827430b9a64ec5ab0d5ddc35611f.nq.gz
│   ├── c0d1db384c9f78aaada682ee5a008e2a51321768.nq.gz
│   ├── c1a94328be3f277b7df824d0a3211cc0101df483.nq.gz
│   ├── c2e2cc89f8666da9a58f72a754386daa42ef3989.nq.gz
│   ├── c60b72bb2c212fc2a28bfbc2f4ec980dee8645ba.nq.gz
│   ├── c858754612d797656e22d18b79de98e2210b5a98.nq.gz
│   ├── c9d54afceb4c972ce9e7bd39cee04d1b8d907202.nq.gz
│   ├── ca0da328fd3d772038e62a8995fc4f7ec2044637.nq.gz
│   ├── cb52646dc60c07a05f72f8dff93d0623a5409579.nq.gz
│   ├── d0e0a6af82382d855c34dfbca0aa2a143b5483f9.nq.gz
│   ├── d256a3911a498123c5ad8724134a63779307f6c2.nq.gz
│   ├── d272c54144cb4f47f29787cb1a274c53e56481fa.nq.gz
│   ├── d388112b6da28a582f3d0db3c0d52405ce5e5709.nq.gz
│   ├── d388216b8ce3d07865b689758728f15db41b6ba0.nq.gz
│   ├── d565b63e903591cdd586ad74f04bf5fd72d5fb3a.nq.gz
│   ├── d5cfb644be7be8ebc56d5417373d4c57494dda93.nq.gz
│   ├── d629f753cd3433625213e8c527518d2f7096663e.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d70a32f28963baf195d40a4ec33208513be5a6e4.nq.gz
│   ├── d7867033eaf73af298a2b001e7c0605c0c8be644.nq.gz
│   ├── d791082abcc104fb080e9d33b735bdc72cd0da13.nq.gz
│   ├── d7e77e7a078a2fcea3f3524f45325df38b30f479.nq.gz
│   ├── d805add5b4eb4d6b59e1d097e3abcd72c5a57a58.nq.gz
│   ├── d94a2aa408baf301a023d73fe238a8927c59c9f5.nq.gz
│   ├── db2191a8adb03f2328f6fca03a7bf2fdb00fa5aa.nq.gz
│   ├── db5b5c709bce5f28e24d064972dcb758b506694b.nq.gz
│   ├── dbcffe6d1ece3671b5cc3437535d97105539b989.nq.gz
│   ├── de4de1a3c8dc9470b0610b4bcb610ded64d810e4.nq.gz
│   ├── e27c8fd00fa3bbca13ff77f4c7be7c9f0135eae4.nq.gz
│   ├── e2a7fa30c56a6a3005c27c0887dfd07a2c26af82.nq.gz
│   ├── e67a882c05fd8d421d2201939602afd403a96605.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eae0123defaaeac2026ae65adeebbd2ce447e895.nq.gz
│   ├── ebabaddb6cb686ad0ddb813cba072741f8083be4.nq.gz
│   ├── edee261b0a946718a79e8974e7cf3ba4930ad76b.nq.gz
│   ├── eefd1c10bc58aad477ea7d43e488b3fbba2049e8.nq.gz
│   ├── effb0a19e6a0b3f69b3f0a2c72b5c2a02a0ddeea.nq.gz
│   ├── effc0a99e18c88a362a026df1bbeb2dbe80b692c.nq.gz
│   ├── f0e3555a23065619b783f81a6ff26cf4dc52dbb5.nq.gz
│   ├── f1d260a0f4372dd42bf228069dceb44f4618f16f.nq.gz
│   ├── f204c2ae2150428dc3fede095961a627e204f96e.nq.gz
│   ├── f22bf81a8d8d70f8247de4248566fd90ccf97750.nq.gz
│   ├── f31de9a35f02fb4a8873a522d9c4575d8066d1a0.nq.gz
│   ├── f4e0b6d018989a4b7d23079baf15743d6fb71516.nq.gz
│   ├── f68bebe29ac3b607897514747513d156a34b43b3.nq.gz
│   ├── f8bd2433ea3f3f19f0825b2707e9795036d61bd4.nq.gz
│   ├── f975e948762c99feefb20772573f723c416431cb.nq.gz
│   ├── f9e7d89bfa5f9582cfcfd1fe38fa517eaf1e59cb.nq.gz
│   ├── fb3f3e64b9c5154b5eb2394f91e9468a0a90c547.nq.gz
│   ├── fc002d8bac2020aabe93ba7806fc640373e3e72c.nq.gz
│   ├── fc59b8fcfef74f2349678d55fa1ee065aa74b6f0.nq.gz
│   ├── fd2c8cdcd77dc24eda97bd19ce81e52cf8eb58c3.nq.gz
│   └── ff86d27d8bb137438b797eaee0115fc6d34e8b8c.nq.gz
└── branch
    └── branch.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[sigstore/sigstore-python](https://github.com/sigstore/sigstore-python)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
