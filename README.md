# Repolex Knowledge Graph of canonical/netplan

RDF knowledge graph data for [canonical/netplan](https://github.com/canonical/netplan), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/netplan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 241306a711258aaa8667bbc011db9662f605e491
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 241306a711258aaa8667bbc011db9662f605e491
│           └── chunk-001.nq.gz
└── blob
    ├── 00e3834422c8e1cc82c8d341a295c2c3dff30772.nq.gz
    ├── 01965e7a213e10f016b134339428d49ff9638136.nq.gz
    ├── 01bc1c6f3241f35ad20a6fb100212efb69664aac.nq.gz
    ├── 02990dc6b46f49b5574705f69f112dd964f8e303.nq.gz
    ├── 03435bf796f802f57a31882b277fe4ffc3ad1626.nq.gz
    ├── 03e843691673af981b27f274a1e62b736e74e234.nq.gz
    ├── 0433a020cd44c2b5b1ed5b7877d8ba6fd79bcb03.nq.gz
    ├── 043d74a1ae229bb859131b9d40863e52f2cb4c92.nq.gz
    ├── 0602e21096f4387e378d56127af97005f68d1bcf.nq.gz
    ├── 061e81a8138d71686e1cf0b822db9fc65b96d9db.nq.gz
    ├── 07bd1d8c489d1e2d103e169255e8c54af347eabb.nq.gz
    ├── 08ad7f47b4bf3497e62c535b44db9144591e28d7.nq.gz
    ├── 096c6d9557cb228f4301a6aa742b6e0b3f396c8e.nq.gz
    ├── 0a9ca6e1504d8890878b34fe4f2795d6bc53a483.nq.gz
    ├── 0b3e767e754882000dac70903662dc682a455ad0.nq.gz
    ├── 0b9440903df50d64a169ed0ee28a572543e9fa59.nq.gz
    ├── 0c6c049fc84e721bbccee8ee71de8e5ff0cc5bfd.nq.gz
    ├── 0cec00e439c1fce8631390013f6436e785864015.nq.gz
    ├── 0d430cb81b8d9b9b1da537bb092577ae50f304a2.nq.gz
    ├── 0d4ace0d00b161be6ffa7764783dbcfe9e4df665.nq.gz
    ├── 0d9e125bbd1c6dea0ec066149c894cc53baac8ba.nq.gz
    ├── 0db5cbdf5eca35499c459f769c73cdae619f163e.nq.gz
    ├── 0dfb541412ab7a53f8d3974a6596648496f57bb8.nq.gz
    ├── 0e1e4d15a499c598e7f704be92b08a45ff6696c6.nq.gz
    ├── 0e2ef9cd70d65e6fceffc8ad67c41323b7e89c94.nq.gz
    ├── 0e3ad0d5df53fa3d8dfe36828073276d87bda7ef.nq.gz
    ├── 0e84a757175046354fb156abcb0455f0f2621e84.nq.gz
    ├── 12658cb6a94f1adcb4a504b334b8eb8794021998.nq.gz
    ├── 133ab9878dfd5c3ca68a1b7be2b2a7ac0174ed97.nq.gz
    ├── 13ab91bb134c8abf3304c4cfef75d97afec8c411.nq.gz
    ├── 1416e40d595208d5fd0b62e11f28e981f7be5a0e.nq.gz
    ├── 14f906bc46ba3ab8788a9b8118507d1082b4c1bd.nq.gz
    ├── 154b42f09e734334a595fd1d60642c35e161d0e0.nq.gz
    ├── 1558de39d28b8a0aae2a68b5a787a8667adcd206.nq.gz
    ├── 16fede88fd833f131d35b64f31abdc37969b255b.nq.gz
    ├── 171acf10935d3f4eaad94d4f83f6714908e9d980.nq.gz
    ├── 17b661405adb2f1ea17145e25b80a3fd33b1894a.nq.gz
    ├── 18b8b939da31dca6a951c76b678fdcf55e8ef0cd.nq.gz
    ├── 18cdd82bc401f8317fb614a5a44b8281e3fcdff7.nq.gz
    ├── 194d32fc0b824983dbc6d901eaabc86c2499bd07.nq.gz
    ├── 1b7ddb51be9d9d3ebb7cd79d38e52a10595ffcc5.nq.gz
    ├── 1c4e05a9d59312c0560bba108f22172819f1921c.nq.gz
    ├── 1e5ec469d379a6cd6e5b2f575f91d6c93c2d091c.nq.gz
    ├── 1ec8f3fdc8ad2216c7aa4e0dad9d1a91d63c01ee.nq.gz
    ├── 20bf48c8057b9149d2833e65373cbd09bd9347d2.nq.gz
    ├── 21951f011cf57de9d32cbf3dc40adf4dd2c02523.nq.gz
    ├── 222691b5abefe8a5104c64d175a64365c0ac8322.nq.gz
    ├── 23bed60868dbfdb9191f5481d722d5ef25371913.nq.gz
    ├── 2446c5d646e308ac43d4619a1c9fa81be4ecb876.nq.gz
    ├── 24af0b26fe4d7181705c3a68ec99e0a48c4033eb.nq.gz
    ├── 252109e588d4ab5626a6ac34bee7a935263c936d.nq.gz
    ├── 2543d0052a30278f758fd4276948a1e9a66bcbd6.nq.gz
    ├── 25532bafc33845729feb995548a7f60707be998f.nq.gz
    ├── 25a12ea65f7e38031bafd63ed5508b6645a3dc03.nq.gz
    ├── 25d315be2dfaddfe3a72065aaa2ab62392f0da07.nq.gz
    ├── 2612d2e96735bcc67585eb50d28abc84fcc04f61.nq.gz
    ├── 264f1238a64a8bb21cea47365d029f76cd32e343.nq.gz
    ├── 26b2961d5131e5a59b10a81e5f9a87351a87bfa8.nq.gz
    ├── 28b2e81598947506e157c3b7263589bd06292d08.nq.gz
    ├── 28bfad3d5d8aee5d762b13d58844fd68169154ef.nq.gz
    ├── 29b11874675e1b5e4c30c780cc1788c70a6bbbf7.nq.gz
    ├── 2a9e0dd59d163d1fee1350b0f75e80e7a2917819.nq.gz
    ├── 2ac6003219f6906ad1fdb10f6451faac41cdece1.nq.gz
    ├── 2accb0a08828fad51bc5d6ce868914c488ad5533.nq.gz
    ├── 2c664d7cc42ea9ef40b71b705ca4ae072571da2a.nq.gz
    ├── 2c722ae7fe41f479738f50f2569dd3297854ad8b.nq.gz
    ├── 2cda89efb6db86a43ca7b5cefd6e344648b6195b.nq.gz
    ├── 2d2b12bbe18dcb6ed10f2c9602f7ed593f94b985.nq.gz
    ├── 2d9b66d08fd015717957bdcc2627c7de3278c062.nq.gz
    ├── 2e06d63d6b5f4145184ecd1d76ea3e74ad51e258.nq.gz
    ├── 2ece35f2dd489ebe773b19d5ea1d848600d65a60.nq.gz
    ├── 2f8841eb0a384aed9605e16499e9b583332333ea.nq.gz
    ├── 311860c9a6137436f02c3123a386af6856c56738.nq.gz
    ├── 3129f1d95e77faf6c8afea9caff97bb42182e447.nq.gz
    ├── 31ce7bd2248f1581d7d9360417e33651357c8da3.nq.gz
    ├── 33055776e86356f7d84bde40111ec5d8ded65e2d.nq.gz
    ├── 33075dc2cdde973a070921f2d516dfa9a28f53e4.nq.gz
    ├── 3342f752578e01906f862d1d82f7a2f3ec5a8ab4.nq.gz
    ├── 334970afb16ef0d9cc565fd2678dd44d967ecbea.nq.gz
    ├── 334dcaac1a6af39b4af99c24b85561023e630420.nq.gz
    ├── 344d00cf4bfed4edd7eb65d4311d3f363907555b.nq.gz
    ├── 354dd5fe5bed6738dcf42da4aa9286bf8d66b1ed.nq.gz
    ├── 355e8446d3931a76cb14e07cd591e053ee2c7231.nq.gz
    ├── 3608576e03aa97bb0a7991dcb78ca762f205d999.nq.gz
    ├── 374ce2321f66670fff36f259ec16b87f488c206b.nq.gz
    ├── 37853d1155a9f05f6bc7eb3dcdc483b2a3ba66ec.nq.gz
    ├── 381a3c19a91036391b1ace0483f5b6fe4ef537ac.nq.gz
    ├── 391aedb5331aca79719e6bd69787f8d5b26f7262.nq.gz
    ├── 3b0641b270aa3c079112767ed560d5acdfbbb8f7.nq.gz
    ├── 3b66c55772c47f3b44c759c49e57759c2d2bcd57.nq.gz
    ├── 3c82994402e1d9c8b3c2d5e0c242772117e66bd3.nq.gz
    ├── 3e525b66471e1b5aee01e918d7e9ebee8aa571d6.nq.gz
    ├── 3e6fc64a35b18484dbd19bf8c2d5779c4211559a.nq.gz
    ├── 3f0eeb758bed4f43ef5f8d8e27f426b89eb46a57.nq.gz
    ├── 40677e886a785e4076a83cf5d3fda1f36c03b55f.nq.gz
    ├── 4103459a186ed6d6fe6ca8b97535a929894d90f6.nq.gz
    ├── 4215931ed078087cf4dcc3d263448307cc3efb8e.nq.gz
    ├── 4216592a07854a31e92da34b356fe6cd5d682c9f.nq.gz
    ├── 426e87a52249299e92ebca642f25700d13dd0d7b.nq.gz
    ├── 42ac68addb6a6139281441379cdda3d42d301e4c.nq.gz
    ├── 43bf55850c899d67a6a4cafff8dfc48db32ec416.nq.gz
    ├── 44cc49387cd60b4fd352174c4cf56bdda347aeab.nq.gz
    ├── 465a0d7c16dd608e3e21ec089b46b82f27fe9d7f.nq.gz
    ├── 474ea721a529a7cbe88f6e6d29a35709fefd8c34.nq.gz
    ├── 47630be5b32a5a710c5745c29c007db53e683c9d.nq.gz
    ├── 47aeeb579a9de685c628cf527774da1b19e40d82.nq.gz
    ├── 49a69b57c8631a3d8b6b356da431d2d30d62b48a.nq.gz
    ├── 4a5179844e21131bc5fe4320df6f409cdd81a752.nq.gz
    ├── 4a6dcf7e87718f57eb0ab7e406e13d697c2bdad9.nq.gz
    ├── 4b8bdb1ea4c26421242d5d7ba024cae4152ed52d.nq.gz
    ├── 4c9020d390628441c41443d860f784a1e5cb19b0.nq.gz
    ├── 4cd564d9ad441052bef98d25d3e01225d83f3d19.nq.gz
    ├── 4da0b0afe3991a1f57ea5b36bb3c01be5f321d72.nq.gz
    ├── 4dc4971c8706a0517e914380a61568554a2ea51c.nq.gz
    ├── 4de5e084a0a40554840fe60c9837750d7f87bcd6.nq.gz
    ├── 4f999aca0b5e2af0faf26d85a0573ea07bcfbcce.nq.gz
    ├── 5029c511fc434cd62112668a4a0249f25f0aacce.nq.gz
    ├── 502b2782ae5891d3ebd9f0266eec2fb9a235d047.nq.gz
    ├── 5131a597f298a5fd7fae15c3ac39bcd213644ce9.nq.gz
    ├── 518627f4956e4cb870b96535a4aea8af1ba5e082.nq.gz
    ├── 51c21c17fa51207ff689ee5c22262f5a1d841b94.nq.gz
    ├── 52955133414e73f458029f09e266b39e9e0fe413.nq.gz
    ├── 544f787517aaca13aade3b96e992abdda3d0e388.nq.gz
    ├── 55bbcf4d8ffa426a78d233133c2f127ed345376a.nq.gz
    ├── 57276169bea31d205afeaac234ea56c93b098fe7.nq.gz
    ├── 57414f6a67c5061dcb9ce5d963d9734bb43586ed.nq.gz
    ├── 57c0c7b7e685638f178a78b4de74a2f984e6ec0f.nq.gz
    ├── 582d26b00d241d47ee1391fd1742b7446a5b25cb.nq.gz
    ├── 585f5f9a52cea68bbcb56abcbb3cf7ee085620aa.nq.gz
    ├── 58bcaf14c5425e7ac0e0b3f14568a56465b1686c.nq.gz
    ├── 595dcd321304c74644603fb33fc05d624caa9af2.nq.gz
    ├── 59f6e75f3fc338752c3929342db4180b3aae2aa3.nq.gz
    ├── 5aa777133bb9a0e9619fa09158ca790e48c8f283.nq.gz
    ├── 5fce8e04a0dd7cec441d44e5560e3e7e4707db6b.nq.gz
    ├── 60dda973f0aa13b4781aa83ee44085201ff56ca4.nq.gz
    ├── 6146d7ba3bdcbd40b01e96003020e6212bc7b37d.nq.gz
    ├── 6187d9094b52a19e0cca346e5f5d287bb36b31d7.nq.gz
    ├── 61ab06349f0ac91ffee22100a6459efc5bde3229.nq.gz
    ├── 6393459f42fb5051851eed2225ae56c95d2f1e48.nq.gz
    ├── 6580686fd54403dcd30a07a2c9efc3588f365565.nq.gz
    ├── 678e155f5a9e0d2ba3689e8792e43a6f9ba1469c.nq.gz
    ├── 6924e9a0e68b8b468f9f3c862225e608b1343bbf.nq.gz
    ├── 6949897e922539248bca5805237aad36829b940e.nq.gz
    ├── 695c304e6d0f5b3c98e8699b61b1d03d8b1a12c3.nq.gz
    ├── 6a2b56a269951ffa7d08fecc60acec2f2035d3d7.nq.gz
    ├── 6ad192a67e660f30ac85f57d5c0bec5368e3fef2.nq.gz
    ├── 6ce4ecb55b8b9b6e78caccd9c86bf5722ff8971e.nq.gz
    ├── 6fed782cd5d8b4f32360359db64f589823c31a1e.nq.gz
    ├── 70828d5fba9cfbe1c48973580339d5382f386506.nq.gz
    ├── 70b814d0559093fffc2d3c51e1c66b54e22d55e5.nq.gz
    ├── 72675df8c681abfe895502ecbcae1f4d5add7df9.nq.gz
    ├── 733585a43da9af3ad83fd91548f3fcb72b12b367.nq.gz
    ├── 734f0912da9f31f00e39d53be34a681a3770b09b.nq.gz
    ├── 74ec9066db244f62abfaf044615546a06e59d90e.nq.gz
    ├── 767296ed73260a93dea4c30cbe46c1407d3485b1.nq.gz
    ├── 768d45bb65a5fb634a8b151e61a539c024e63499.nq.gz
    ├── 76a010ec1e86e2a1192370cbb1a1de052271c34e.nq.gz
    ├── 76c6359b97bdf362edee82d9aa30e35265568c89.nq.gz
    ├── 772c6ca639bcf5aec4efae10cee490acd5452c1a.nq.gz
    ├── 78f848e3a28c94ac624a0414cf7fba8762ef0c0e.nq.gz
    ├── 79613e338d1c28be0ca617e6c48fcd29ab985e84.nq.gz
    ├── 7acffcac0cfeb6500522002497280db1d8d00dcc.nq.gz
    ├── 7c5c8431c6c560f986c2aacdde01f3967c3bc17b.nq.gz
    ├── 7ce42032dcac40e901b8cc67dc232f7bb5eadbf8.nq.gz
    ├── 7d289c92bca9c1f260033307690e3afef591f95f.nq.gz
    ├── 7d443f0e121eddf372c00b0f591d468d2f44ac25.nq.gz
    ├── 7db51ae63963fe0af4785c55844e8f1f53185ceb.nq.gz
    ├── 7eadc5c8765dd88e5a3fc0660c6c239a727f211a.nq.gz
    ├── 7f084b21d34947522e8061dea339bc1ffc173c6f.nq.gz
    ├── 7f175e4617695f752022d2671a0f97fa95bfd895.nq.gz
    ├── 7f1d9c29344aa7a3ab7b5fbcef6fb7e408d2d70a.nq.gz
    ├── 7fc3c0c5ba64bcd73eb8d3d8873f958c5a044747.nq.gz
    ├── 7ff71c74abb053a4a7298ec604641a91d8ecaf01.nq.gz
    ├── 81eadaa1d43412b36c38e01604c6bb8ae51aaf0a.nq.gz
    ├── 832a8735518acd4ea789bb9009691dcc65e98b90.nq.gz
    ├── 83758415fce51c1e413db3f79ed4d903ddb1db3b.nq.gz
    ├── 83fb8fc927e65681c0fc108092238a3ad2890f48.nq.gz
    ├── 8401d384dc04364f617a07447f8202914c0908cb.nq.gz
    ├── 864ce151c95a053de086d5a6fee762b3d6840b4b.nq.gz
    ├── 8664b905573ac1be2bf053747fd74cde01905520.nq.gz
    ├── 86cc1376dbce3204e47923165d367dc74a65a48e.nq.gz
    ├── 87622bda209ade5f8c58838e81b5918867444103.nq.gz
    ├── 87bfa956ada3336f246bdd8669d4b61ae791e394.nq.gz
    ├── 885c41e8c23a2ea141d08c23ff08806d4d814d1a.nq.gz
    ├── 88a734bb237320080a2bf1cf7a876bd75d1b10f9.nq.gz
    ├── 8a705e4e7851740cb31c6ac0e5cdd7f18973892a.nq.gz
    ├── 8ad11412984473f568facf80087df0d4c5f079c7.nq.gz
    ├── 8be7fba10c405554780ffa1d5ef7a7c36cbb75fc.nq.gz
    ├── 8d2c353f09a42e9b59cdc3c2b1f48e25b897f2d2.nq.gz
    ├── 8d5eba16570175311837cf06a37745c02a035cf4.nq.gz
    ├── 8e76a0ef7f46b491a8da6da59ab14beec057974f.nq.gz
    ├── 8e86113456bab334dbdb2ce3c4b62e8313a095fd.nq.gz
    ├── 8e99af4737beaff0b611dcc0173c811cde13ffbd.nq.gz
    ├── 8fa59ce9903e934454962a065438c1c327edb515.nq.gz
    ├── 90b807fe55765302c72050e419340f687637e7ba.nq.gz
    ├── 916cef31bce91b41c973c4ccad1d3178f64095b8.nq.gz
    ├── 9232c09c9af98b05ffb0cb174a3e968a4d33e5dc.nq.gz
    └── 94949aeff00da656dd8cccf68122ffd2490f8880.nq.gz

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

[canonical/netplan](https://github.com/canonical/netplan)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
