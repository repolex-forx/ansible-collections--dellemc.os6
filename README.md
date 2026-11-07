# Repolex Knowledge Graph of ansible-collections/dellemc.os6

RDF knowledge graph data for [ansible-collections/dellemc.os6](https://github.com/ansible-collections/dellemc.os6), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/dellemc.os6
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eb8fee1d4acebb5186bbfbd56169ff6d51831c1d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eb8fee1d4acebb5186bbfbd56169ff6d51831c1d
│           └── chunk-001.nq.gz
└── blob
    ├── 0022966d9aae4573c6ae8fa3723e1e6a5299611b.nq.gz
    ├── 03697d94d167729b2a18599b1c93cdcd5d817aa5.nq.gz
    ├── 037d378193ea801f53382dca86b4f350bafc748d.nq.gz
    ├── 03cb3b801328fc4f0dcffc71fc68fcfd4c051067.nq.gz
    ├── 03d5fa49b20737bbedb7cd6b5e3d697d4b3bebad.nq.gz
    ├── 0416fab8f4eac1396d0cecf1e92b93c73fffb77d.nq.gz
    ├── 043ee2cc2940548e3abe0174ebcedb4e768a78bb.nq.gz
    ├── 044e7b462dfd468f274b30ee34e6b45472556b8b.nq.gz
    ├── 051ba0340399187b39be0d1820175a1109ff0809.nq.gz
    ├── 0665ae6b672ef2c60f708cd268bacc7b35e1a335.nq.gz
    ├── 076dd792f676eac524a061ab381c1dfb1ab3cd0a.nq.gz
    ├── 0a2a860802647469a1abd613e9d935779143cdc6.nq.gz
    ├── 0b3a1ea86045a104b9ac539e407f3b436a092b47.nq.gz
    ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
    ├── 14475f6d276d4e73082953b61d4ad4bc852de48e.nq.gz
    ├── 1834f7b1e08c928d7c6db5409b7323de198c76ad.nq.gz
    ├── 198d860070b2b9e3d3297e3f2757d146ef99ec31.nq.gz
    ├── 1998b3a751de87ac9276dcfb9b41df6df835e995.nq.gz
    ├── 1b87a8f3ac151f4e1c364716560ff4c5c70ef9c9.nq.gz
    ├── 1c7d628211b681bedaf5cbbd509044019702bc44.nq.gz
    ├── 1cda8da386152307836511fa9f83d3641a52825d.nq.gz
    ├── 1d2f60eb36d468587e25a6992819be43a73969e2.nq.gz
    ├── 1e142f375ab7fcfa5b3488f55363f4915f4c5432.nq.gz
    ├── 2015aaf9aaa0e7178b38eb319c1e321fd8426682.nq.gz
    ├── 20d81a3dfce85b7664f4127938b97d9face1a163.nq.gz
    ├── 2146cff8c157a190e62c7b4ebe6a0baa9a74fe52.nq.gz
    ├── 22d0d344aa87a35099840854e63ae695925088b6.nq.gz
    ├── 22da4f71dc86c1c336aed058c431809ddb8f405e.nq.gz
    ├── 22e0b3d7dd4b203b3d9722f8c4bb5f38c9fd4238.nq.gz
    ├── 287bdb9a32cb946dc0039ae6d2b3ff9c110f728d.nq.gz
    ├── 28defda61e95db54a48d52032fb984336913f93b.nq.gz
    ├── 2980eb659e409fa31b4d72cfc344c402b6796302.nq.gz
    ├── 2a22f444fd35b9c35b97d88d8f36cc84abe39a71.nq.gz
    ├── 2aab9b845244304a98001cfae4919439b665b466.nq.gz
    ├── 2b05877b0900c6312484f582fe87459e0fa3b818.nq.gz
    ├── 2c6b359fa8283041628a47710c806b05c067ad76.nq.gz
    ├── 2c6f482ff1c2dc978f56f26f0b14d4bb0699f1f2.nq.gz
    ├── 2c9b8e1fd96648c398d4320fba406b2ca3171da9.nq.gz
    ├── 2e0b83364be706174b409d9bad1e697f011c62ff.nq.gz
    ├── 2e70b1924f41721ad3a6a5106105c065be8f8153.nq.gz
    ├── 31be2719cb8335484d10cf12219ffe009cd2123a.nq.gz
    ├── 329db6aff336df8e45c38832130bdc0b24209ea7.nq.gz
    ├── 32daca592f8b7ea476f8c4eb82916c5069d26507.nq.gz
    ├── 361ecad5f87fdc42d2c840555ffca737c6185887.nq.gz
    ├── 36a416e3408f140e96ba3578f971f037d2611479.nq.gz
    ├── 36cdb9a41b96642b2932999622213be96c4ea1fd.nq.gz
    ├── 376f0e03d4240b9684ba3de47bd9391e93ac458a.nq.gz
    ├── 37c2c4b2bb0970a94b363acdfe8ca98ce7d01255.nq.gz
    ├── 37c58e8b09f2c3d73d55281ff6765538f20bd77e.nq.gz
    ├── 388cb49000039a4a7b072cd0f85a9ceb4084ca9e.nq.gz
    ├── 38adc0f36a036574cc15633e8b030c61f23d6276.nq.gz
    ├── 39b0a53bd1d83dad99840e5673d84e91edf1adf1.nq.gz
    ├── 3ba29704349b26facf27308b7a6f53f9341ae542.nq.gz
    ├── 3d47c2eb717fd29db527e525de4593f474742b47.nq.gz
    ├── 3f367237a207697d29be1146ee53ea15e267f8ad.nq.gz
    ├── 40a48c74d56744fc4986bf8fabcaae10e2297f82.nq.gz
    ├── 426576938a644bf6e81993600b9f745eb5e4a355.nq.gz
    ├── 43c3f17ce3b4a703eda31c86edda5abc44bf53ab.nq.gz
    ├── 44d0b537fe3f7c35ecf2c0353496e063f8e2934a.nq.gz
    ├── 44ee544eff82baff48c9268414c5bfe64a06001e.nq.gz
    ├── 47fff33e55fd00e0db43c2cec9002a45ad8fc534.nq.gz
    ├── 493196df7283e51f6076862ee5e2738db81032a2.nq.gz
    ├── 4a7a41de977f9b2ba35f4a16750dde0158b50f46.nq.gz
    ├── 4c41e334d6428cf3fbfe7ec7e21a49f26c2dbcea.nq.gz
    ├── 4cf68f174f9d64bb2d4da7dc09a7866867f11a2c.nq.gz
    ├── 4d630fe46a7c49fb613505893deda55d097514e7.nq.gz
    ├── 4dd1019778e7fdeead3ff5b5b4f049a7a613a84b.nq.gz
    ├── 4ec591c953202a5d284fccdd7ee14c6a4326a3a2.nq.gz
    ├── 4efc0f332eb1fc7addfd801cdc15fdf1b9b91aba.nq.gz
    ├── 4f8cb8c9880acc2d36319fecaab8bd604f874124.nq.gz
    ├── 5048d9b491fc12b9b138531346d88428089bca83.nq.gz
    ├── 51049e5e075f95e9f13953b8b86ee221f265f2be.nq.gz
    ├── 518c92a39add59584b23be07f2330dbb077c850d.nq.gz
    ├── 52ff6880cebc02980d42d2c4750991d72b76049b.nq.gz
    ├── 54188456697ce5532bd3d25596716725a005fbef.nq.gz
    ├── 550ed665cbbc5b640e033e97d58e4d4c6c06a3ff.nq.gz
    ├── 5513a7ebcbf40d010affa335bf07933a56006c98.nq.gz
    ├── 58e963bb7aebc01a4a91c1fc231a64e327c6111e.nq.gz
    ├── 59eb0dc809f7df4ed2e2c170f39489b1c408a476.nq.gz
    ├── 59ec49c1991ede939a41dd79143241161a87ec5d.nq.gz
    ├── 59f8399db126296970daaf3ed46ec7561e681146.nq.gz
    ├── 5b0f68cfbb2da7d0b327d8774ab942e9db184749.nq.gz
    ├── 5cc2de16e626af39e14a0acc6d9c8a5e56d76b57.nq.gz
    ├── 5d089cb2107ad36402e7fe91b3d21e7a7b296579.nq.gz
    ├── 5d11b69a9a3570111093cbf0dd59ee47a5a15425.nq.gz
    ├── 5ef09a9f54338b68e7701151207dd59d329c6dbc.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 6224f56a11fdd11c0d8af8cd580e65a8cf390fa9.nq.gz
    ├── 623771fa8e2f708d76fb272e3daa1623a8d58b3f.nq.gz
    ├── 623b207693a821a4770c45c573373841d0bd68bc.nq.gz
    ├── 64a2c5ec954858f220b2595fb29c0b7350042b83.nq.gz
    ├── 660d49b397662e216b5328763a65588c257cf75d.nq.gz
    ├── 6945f1c26adde5674a0266065cbff15372bca0e4.nq.gz
    ├── 69562c9243619a5385cd650d52b5f79fc3fece7e.nq.gz
    ├── 6b8009608fb21b9af95213d12ace75e8d8e10cb4.nq.gz
    ├── 6c26f3d304a998115b015865907e176f03e9286d.nq.gz
    ├── 6ead1fa963df7215401555efc5e560b9ece1ebad.nq.gz
    ├── 6fbdec55c29d334ceda7d17298d4bad2b54a8548.nq.gz
    ├── 70d5f6653e7b5bad9e5dd4455310fba2a6f75b0a.nq.gz
    ├── 7145221d15d04e076488b3d8ac5f5e565ad364df.nq.gz
    ├── 7152815d70aea7cf4e4398d9700009734b55b63e.nq.gz
    ├── 72a07a4d99ce530827040d56dd84e9004a4973db.nq.gz
    ├── 72e72eaadce8b408408076310af60ea3d9d3b637.nq.gz
    ├── 773a895003a15cddf0ece64c56f958e631838c47.nq.gz
    ├── 77728edb581ebc0987b5c4e14df11be0292ca9a4.nq.gz
    ├── 7c8d983ad8eacd9d0860e6ae7821c3db80ccdded.nq.gz
    ├── 7fe379cf86da4d7c41b48e1b807a4a6ccf2b9c20.nq.gz
    ├── 832d5493fa5a8f10a30f6a8606e238160e52a5ec.nq.gz
    ├── 859d5c2bde771c08c210194c3d757c9461c971fa.nq.gz
    ├── 878877b0776c44f55fc4e458f70840f31da5bb01.nq.gz
    ├── 897a47aeed914ce933e260d584b497decfe1c212.nq.gz
    ├── 8a87d5da5b2fab6a9ac0b3d5e54b5e660d360621.nq.gz
    ├── 8a8a2a41907336c0847fae2f92933c3dc71b914c.nq.gz
    ├── 8b1bc5a11479bae282b1d678290cc09145d557b7.nq.gz
    ├── 8b7b6f6ca2a8465ba1a8a6f32b595152103d5a04.nq.gz
    ├── 8b9f345647b64912f40df9b86b87287a6cc05c8d.nq.gz
    ├── 8e3a1b36592206cc2fe5f047641f7fd8f60fbb65.nq.gz
    ├── 91049edcaba9b0ee44999bf90810b5ae0db3d5dc.nq.gz
    ├── 924755044fac99d383dc99dcc4dec96f5740ad72.nq.gz
    ├── 92931d8bfa1c8c088fbfed1516186f5d7df9a235.nq.gz
    ├── 92da22dee4a4b4c0940d1a4c7e47acd1f3b903db.nq.gz
    ├── 93b6adcb513b15d372d2ca358e73fe56597de901.nq.gz
    ├── 94e4561f4fbe174076b4181c9fe24b2db2b0b654.nq.gz
    ├── 95770c6aba9b73590157497242110e3efa787776.nq.gz
    ├── 95a1dc26b1ffa04de2eb5aa71fb92f052b829242.nq.gz
    ├── 976f45a8215b5062ad06aa07dcb60425edef3ca0.nq.gz
    ├── 994291fa1aa7a372afe31fed75c40db5639afa52.nq.gz
    ├── 9969a95166e6bc903ff5caddf6f938aa0f85b346.nq.gz
    ├── 99f52d2e92fa6203113a9354d6ccb927699d3708.nq.gz
    ├── 9cf929174380f1759cc22faa63e32af994978e3e.nq.gz
    ├── 9dbd61736a725c797d6659b3332c40de9d3b9bb6.nq.gz
    ├── 9e1a4c27ae723ec4907e9fea8e203c5e43f64d7b.nq.gz
    ├── 9eb17b5d7cfc5ee529652293c6cf85d788f184e4.nq.gz
    ├── 9f0ff54fbb8e8e538f3dfd6103732fa5cf59b70c.nq.gz
    ├── 9fceb3895a5ad5c6fed3b53f7ac8a710d0bc53c6.nq.gz
    ├── 9fd9f861468d00bad4dbca182617e4b0eb85fab6.nq.gz
    ├── a0318e7fd5d0299a7db6786652394dfb13301eda.nq.gz
    ├── a042201bfce68f9489fad0fd346d5c1564ef6684.nq.gz
    ├── a1a30f2526898ea3f0365e2f45f2aa76d1e1a060.nq.gz
    ├── a24c1a2e84ffcec6b676a4f271b6f21f5d9e21f6.nq.gz
    ├── a46800e06501d5698e09f4760504c87f70ae3190.nq.gz
    ├── a6ba48d3ac6aeb5656ef776d58f487be4e62f2e4.nq.gz
    ├── a7f16df37eafcd13a1494c8029cae241b9477ca3.nq.gz
    ├── a8ed721c86b78f7fa99bf0656169d68567408198.nq.gz
    ├── ab2367becabca899be9f419019d5c24ccb26b260.nq.gz
    ├── ab3e4e4045a66c33cab366f1e7b6727bd79753d6.nq.gz
    ├── ab5dc0abd72dd3dedac6a298db0489b4c145cb97.nq.gz
    ├── ab9d1f82e0995a99d424b8e053162c1632b8145a.nq.gz
    ├── abb9ec7b40db873aa5a7d4745b814fd6381b2617.nq.gz
    ├── abf6975674f3e6ede68d648ec39b2ce6e6bfd295.nq.gz
    ├── acc2257fc65bc4e7361eb2465195bd053732a1d2.nq.gz
    ├── acd743a7ed9faa804895380347b9c8ce41576b9f.nq.gz
    ├── ace3a8a8e58e08bd82a0f57be99cce65d588cb7d.nq.gz
    ├── b07c1dd8f503801ba53a0be53b9cd5bbe97ab7eb.nq.gz
    ├── b0cbe6ff183ec9c9816798e3a2ccdf9ef592e3b2.nq.gz
    ├── b119955243087b649c2dceb9d0945f69f67305bd.nq.gz
    ├── b1f3f23fb56a1a7d867b2aa8e368a6c8f20904a0.nq.gz
    ├── b20d3376744fce2a3c840d7d6b0793111cc42a27.nq.gz
    ├── b2f3b089ea679308be55a3af6c8d634c7cdea4c7.nq.gz
    ├── b3d5783ab9c094ff6b7dd7fbe2c901ddf7809479.nq.gz
    ├── b4321e9fd4b687d167c76af4d1a799cb7fe03139.nq.gz
    ├── b443e046920c8668858e5c9d48354e6bafa9b217.nq.gz
    ├── b589c2968dbcdb525e21d295de0c449b64726412.nq.gz
    ├── b6ca686d79054f952eafa987365a9f066e9b8984.nq.gz
    ├── b92fb6cac6f716268bd4fe94ab147d74e8fc6e71.nq.gz
    ├── b978e8b3b62baa80dc1a44bfc4eb4d050fe92419.nq.gz
    ├── bafe24c59694cca78581cdc711910422fbab4167.nq.gz
    ├── bd62f2a5a7a7c3dceb146697966ffe31fa56c59a.nq.gz
    ├── be89c415b5a7381314507e555a5f6e21a0af0874.nq.gz
    ├── bf13fc37a8777b49e7436a2e792bfdb3fc03b708.nq.gz
    ├── c10a7390e2689869124d2c810b93af847f34facf.nq.gz
    ├── c1d47b7cb0afaebb29f448a695224d25930fc1e7.nq.gz
    ├── c28686f8a6c24817de86c997853df7acc80712af.nq.gz
    ├── c6fc14ad0bb137ac926d2a5d8ae82d91353830f0.nq.gz
    ├── c720d5cc5521f292b6aae5c8c782ba5df7886ce3.nq.gz
    ├── c7625c60bedcc0391b8cbb274361e6660d1d2fa9.nq.gz
    ├── c7abf91b46c95a98b4325dfdad8644def4e1fdcf.nq.gz
    ├── c84ca513df6dd9d8b82507329e15c83cba022eb3.nq.gz
    ├── ca8e0bcfddb133f8762137da87ec9a75989e333c.nq.gz
    ├── cde049b5ac19d32a27df3180ab10cccdcf3afaa0.nq.gz
    ├── d058abfb74f4aeacaff60109d977d2f32d7ec2d4.nq.gz
    ├── d1beaa3ddd761c0c40a65f43d91c32446b99c791.nq.gz
    ├── d24e3b53f6e76f80fc03712475d826dc1c97299e.nq.gz
    ├── d29653b29e292516d7ba49020130bff711d5c091.nq.gz
    ├── d4898c29bc2defc3cafddb4313990da3422d9a03.nq.gz
    ├── d529e8d11a5f091e11e1e041eae437b5cd695f25.nq.gz
    ├── d602eda7cbfc0234e8eddbc9dabb8ef9fa05f6eb.nq.gz
    ├── d7dc1fb2ee5e5c739ce68989fce46e8bb197448e.nq.gz
    ├── d8c4900d7e228178c93aa7df333ecd4dacdad23c.nq.gz
    ├── db47989fa45739eb77010ff536e41b7e4ea118c8.nq.gz
    ├── dd0f7a78f2682c53ace2f2d0617e81e3b5c4d418.nq.gz
    ├── dd1200bea9dd2ab5fab3d5c851e7d62e0ced0d13.nq.gz
    ├── dd6f97f3e59a1b14a88cd02c6b453cedcf004316.nq.gz
    ├── dedb2f7d655db2fa3404a158b7d57969124e8819.nq.gz
    ├── dee2f2b2cca7da49f67466cd8d7030da68a300b6.nq.gz
    ├── e0cf41fc2e397ca389cebaf955111c8315d39790.nq.gz
    ├── e3d581be91ddaaa83269edcb52f740fbf189ec12.nq.gz
    └── e43b3fd03ea74a6de7025d0b231d38569a33d306.nq.gz

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

[ansible-collections/dellemc.os6](https://github.com/ansible-collections/dellemc.os6)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
