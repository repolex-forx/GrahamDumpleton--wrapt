# Repolex Knowledge Graph of GrahamDumpleton/wrapt

RDF knowledge graph data for [GrahamDumpleton/wrapt](https://github.com/GrahamDumpleton/wrapt), parsed by [repolex](https://repolex.ai).

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
rlex download GrahamDumpleton/wrapt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b521fe63070a43697de682d54b797927e8f6b399
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b521fe63070a43697de682d54b797927e8f6b399
│           └── chunk-001.nq.gz
└── blob
    ├── 00d2c154571e1a5ae8ff35da2426ceaf75efce95.nq.gz
    ├── 00e4146cb662a01ee28ab64a9086214461068c3b.nq.gz
    ├── 02e7d6b8f26b9b9d15c6d12a669683a9ad15d53e.nq.gz
    ├── 065d6c05f6f49923d83269a6a2f9698d198c3e5f.nq.gz
    ├── 074219b92d050fa1283782c7cd0b12d4dcf0a87d.nq.gz
    ├── 0a776c4bf8f8484ab0c26ef8ece4781702f9047d.nq.gz
    ├── 0ce3e8b7eb3494776f42cc2e2053fa78e54b724c.nq.gz
    ├── 0d101ae3973fa67c4bdb00398e2cb627b8ba055a.nq.gz
    ├── 0e674cdc510bbfbdddcd6a57dee2ccca9763d305.nq.gz
    ├── 0fd55ae9c1f767f8b432cada54bef579141f201e.nq.gz
    ├── 1240418c2af85f82342fd227ea116aff2e186fdb.nq.gz
    ├── 124af5dc71feefdf8bb3667ea7ff9e19e02cc1cd.nq.gz
    ├── 127dc836671ac205602817d4ed2ac90364b7de84.nq.gz
    ├── 142804078fad4f09a96b2cb6c33b9d7deabaf500.nq.gz
    ├── 154c153e5e25eb558cada8a435b1f9a73a73f449.nq.gz
    ├── 16a4d89cb3dc760a86f227acd06f2ca79698e092.nq.gz
    ├── 16f06194b1fea48a52eb60fc6d79a7499b363a41.nq.gz
    ├── 173103054dfd4691e60068e3407d248d986783f1.nq.gz
    ├── 17a073e22f5f4d41961b293535bea94e8d5e50c0.nq.gz
    ├── 19757fe02b56446b32cd6cac77658be267c5fb97.nq.gz
    ├── 1a64fd21f2bed83b268ba3b90474e5bf15374560.nq.gz
    ├── 1b86946bb6fa14cd5dc7bb7cfe669879de0d4a36.nq.gz
    ├── 1d0fae4fe9edffb68c49ca6aec0cbddb3ef63bc0.nq.gz
    ├── 1df1ec2d1ea674f878d348a49cb248e3d585f896.nq.gz
    ├── 1f55dd6e3ecaceb8bedcc309947b4bc185150948.nq.gz
    ├── 21397c8aec794fea12be579136d3b1521ce4a51b.nq.gz
    ├── 21fb713b735d3df82c605c97c7a2916bbc56e2fe.nq.gz
    ├── 228c8c96d12d064dab57dcd7b6229c7220d9573f.nq.gz
    ├── 24552a187e71b8eda3cb187a0ee7b8f695ec5991.nq.gz
    ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
    ├── 25f8bc620addda37b167f68b3f26eacb034e00c1.nq.gz
    ├── 26efbffa798de37a2b32e44c4c0a697e5b8d3551.nq.gz
    ├── 271f8a42e5ec50c128fce0544c8acf9d8e9d7c88.nq.gz
    ├── 298a24fab5c28ff4ad91b34d975d4c2d924a1a8b.nq.gz
    ├── 2b685388884156cedbea5ed33c718b8f2306d41d.nq.gz
    ├── 2b9d53b0c23d054f8d64502062d6a2dcaa0115f4.nq.gz
    ├── 2d9da36e2af3ace00dd4f4253ba94c608a73355f.nq.gz
    ├── 2ded470d25f2b3caf1400b36117bf722ff02707e.nq.gz
    ├── 2e0c68478cb55c7cd4c50262714db0f1d86419c9.nq.gz
    ├── 30349cee7442509a7f284e0d3a971e8020bab547.nq.gz
    ├── 31b859a03333394d2a8e5f92ba8bab043bec8c13.nq.gz
    ├── 328cff69ef719804acacbe539b296adb27ff6535.nq.gz
    ├── 32cbe7c18ac59d6f396ea4a08b20376041b6044c.nq.gz
    ├── 33aab21306bbe640386aaa9c597a92793bddafe2.nq.gz
    ├── 3431fd7e194b780473fa44f08b3e13367ffdc8d7.nq.gz
    ├── 3504490548f77c916964c77274a0e3ffc8ecb51a.nq.gz
    ├── 35efecebdd72c17eabbba7487fb929548559ad3b.nq.gz
    ├── 37b9506ac8b721870678f938d237921e108fabc3.nq.gz
    ├── 37e9e5eb0889a61b5471a16ddac736c21078666d.nq.gz
    ├── 3865b04e29d21320f011d2819118526127590f85.nq.gz
    ├── 3b7acd1eda023966541f7731fca7d9fb0bdf6c67.nq.gz
    ├── 3c88aa240b357377d98df38820e3ea4cccdd08e4.nq.gz
    ├── 3cec666209bc60637e588f250250c3b2a40ccdc2.nq.gz
    ├── 3d021f453c622435cb2e87ace35365f8edd14015.nq.gz
    ├── 3e71dd52020f1c177798e3f8fe9265adfc1bda2f.nq.gz
    ├── 3fdf2bce63a119bac1a82384627048c581f73c84.nq.gz
    ├── 41305294981c3f60a853efb336f3da1d8cb54971.nq.gz
    ├── 433b407eb32bff33b389a64701f9895c6a386b92.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 444ad5d57de5e63a64cb3d691ea270ffac610141.nq.gz
    ├── 448fb6a34e0a66745496c494168f7eeab1ee4ab7.nq.gz
    ├── 44e20a55aa3d025fdc5e67adb2a8469ecb795c2f.nq.gz
    ├── 4575fcca6700c5b510ece64aa5eb80f317929d08.nq.gz
    ├── 46b9c504e4860051eeff7509285cd82991c07627.nq.gz
    ├── 49bde0bf27f65af255a94fb3066470d1d36f16fb.nq.gz
    ├── 4b48fe4293b516e2c4aad06be566a6a50ea0f02a.nq.gz
    ├── 4c1ea5f629a2c533b43927d62b6004c9aaf03629.nq.gz
    ├── 4c52b5d294bd4aafef8cb37869657e2c9c53efae.nq.gz
    ├── 4c845ea0a52fe65099b6c099b8a1c9d00632f086.nq.gz
    ├── 4cccb97b99258ab985db24a75b5f65bb6874c02d.nq.gz
    ├── 4dd98c6b08b1290cf3cc01432f6fcbe041b465b0.nq.gz
    ├── 4ea881f57fcaa06b6ba5e3261168baa00f9e4662.nq.gz
    ├── 4ef0e19be496961319a58a199b3d0faeed78d048.nq.gz
    ├── 5065208c6dde823943019e612cd0a0806ca4f704.nq.gz
    ├── 537f5ca7adbb97aee90f60c32ebbc89fd8418831.nq.gz
    ├── 5536e83630982a97c980cda41b713805897432dc.nq.gz
    ├── 55618ad1c70aa06f4a0f35161f950a92e0af2b21.nq.gz
    ├── 55a8711afe1c9cc3689ffc8665a5441d6770703f.nq.gz
    ├── 5732af8ca5650bc4c0787999aa13854d6f99a3b4.nq.gz
    ├── 573e8a22a8e0c45cbf691610b11c42b86954188e.nq.gz
    ├── 5796cd68b5bd1067ade8e9a456f4a16ba318d694.nq.gz
    ├── 58dfb5c737e2cc50f53356e226fe1355f3559532.nq.gz
    ├── 5a0519c3f1c073a49cff8834f7b9badc6392c064.nq.gz
    ├── 5abc518f941193b1ea53c84d827bd60b72702aae.nq.gz
    ├── 5cbe6afb5390bec1ef842dc886e6a8223286700f.nq.gz
    ├── 5d4fadb6e98aacdb813fc561bce1a6031db30722.nq.gz
    ├── 5dd5e62cfbc7d33eff6682c8492eeef59af23a71.nq.gz
    ├── 5dfb99694134264b4a230d6c6dc27e064d8de6ef.nq.gz
    ├── 5e871f617a59dafd63e442920c108f14bc90d3ea.nq.gz
    ├── 5ead5504268cd0e7084b000d28f3e527268de3e4.nq.gz
    ├── 5eddac1e0620b480b81d8bf75cd08a4db0de958b.nq.gz
    ├── 612c198943f2b9e983ea9e09c2f25ec03dbefa41.nq.gz
    ├── 6195cd3478fe981977cba4d5e2facfd26c5c3d91.nq.gz
    ├── 62bf361e925e4f654b0520727fa6f07f350badfc.nq.gz
    ├── 62da4b61dd518edcfee4f8ae2130340bbbf6725d.nq.gz
    ├── 64b4958fcd6f0fce084bb649609322caaf089751.nq.gz
    ├── 67984abf4e4b6988ee4b169e486f11b813d9787e.nq.gz
    ├── 688cdb3be5fe123c333f6614c4e74e4bed7df3e6.nq.gz
    ├── 690e6ecf3d5c46d6df5187e268c44b2e0cc798b9.nq.gz
    ├── 6a0ad24a339cf6016c5cae1ea297bb70d9977821.nq.gz
    ├── 6c8ddef457053a595216a16497ae89171a4fd8e6.nq.gz
    ├── 6dbc1e25ae039fd5347219a634d556b837e7b836.nq.gz
    ├── 6ef322d8078f3dd519a8fc19e4d1adaaa8e02abc.nq.gz
    ├── 7056301051fad4b32655f5eb6907181773965f55.nq.gz
    ├── 72266974de729b8e8fb1454f629038df6e24c769.nq.gz
    ├── 7266718f858a5fe692e93c3919b231032514a772.nq.gz
    ├── 7310e254fa54d21e153ff6badb560feadf7c0d10.nq.gz
    ├── 750227587cb225bbae52be9f2f210067c31c1f60.nq.gz
    ├── 756c9b37af2139bae700683e422179f50efca492.nq.gz
    ├── 75febda8309d0d18a76df08500b34805362c8d01.nq.gz
    ├── 779e5f71c3d265f8ddd8ecd65a00b2f5b7e93ba0.nq.gz
    ├── 783cea7f03388ebb5609c24f3ec06344c50db731.nq.gz
    ├── 790d9450a2baca59d0d1a67f1fda5abcbcaa966a.nq.gz
    ├── 7aa8b446d475c0bf44c61b09e944e740f0058750.nq.gz
    ├── 7aee2227f5f7e11d6da8e1db8ec4d19445040a0b.nq.gz
    ├── 7e2e613e97a45462a235a7bc6b06a3b2e6734202.nq.gz
    ├── 7e9ceac0f7c6d2770af1d93d18d5639e31524a93.nq.gz
    ├── 82133027c9eb6dd3ff20c82704ecf25650e474f5.nq.gz
    ├── 83d3bc25022f781719bc1f91b055ac0ba9c08e2b.nq.gz
    ├── 84b75e88be32eea336b4aa631ef1b6642db3d0cb.nq.gz
    ├── 84e03fd76fbcf6e29cd82d992095252eff9966a5.nq.gz
    ├── 8520acd0fb36103a420ce0eff2185b74f467ef7f.nq.gz
    ├── 8539cd2ed98cd05e81db9dc93832e897c1d2a470.nq.gz
    ├── 8784ea84e5bb3a5709861df4dfcb46bf472f2b18.nq.gz
    ├── 8a2b992b912c4a2979ff723287109d0499a4be7f.nq.gz
    ├── 8b5789728c31882cb3b133c2b250483bd5793421.nq.gz
    ├── 8b98dd5e45d837d5ad6bcde39ee38329dbede0bf.nq.gz
    ├── 8bf5f6170355b5b24ec898404ee25c3588642672.nq.gz
    ├── 8e709a00c1016b5ef97f960b7e280091aff82524.nq.gz
    ├── 8e97b3fbc3a60eef4fa6c36f6b7dd64e8f209414.nq.gz
    ├── 91c3e43fc611a3e406515652fabf48959babb776.nq.gz
    ├── 929e049e1e9ee7e0ee2ebf4074713417fcc7fc41.nq.gz
    ├── 947df5f8bffec8c7e9ffd3e2621b2131c0d6ee76.nq.gz
    ├── 947e02d34b5667afa15a625b4d3118536155c101.nq.gz
    ├── 962d19a4ccf0996c13f9941a161b901ed7bfe7b0.nq.gz
    ├── 9712e405d1b34354d26d780b774bf20fe2dae0d3.nq.gz
    ├── 9b0e49bc147f84892154df57b9ca6e7c760df2a9.nq.gz
    ├── 9dc24065c5bf7165e9b645ae58acc2521749535a.nq.gz
    ├── 9dd1f1c1a255a5af0283201c83b7a20de22afe6c.nq.gz
    ├── 9dd3f7f774254d5d9d813c16d5e347eeed6eeab2.nq.gz
    ├── 9eb20fd0f31a968d56fc25b2b02ab6ecbbfb17e7.nq.gz
    ├── 9ed70942ddb686e6440e72baedb50f876067432f.nq.gz
    ├── 9ef490318d21b4deca1ca36d43ed8e1488025b97.nq.gz
    ├── a0a7e6e4ce8d59b4403d1f819afb1bfdb961487f.nq.gz
    ├── a1dda4e1ad7c5f4cad8c5a739dccf5438ba4ed5b.nq.gz
    ├── a2abd13395d5e65691df575f8834ae8315fc41d1.nq.gz
    ├── a2cb248f60e3357d5a0a012301dfbf0bd9f11abf.nq.gz
    ├── a2e08b2dd11cc087632433334abfe79efd971091.nq.gz
    ├── a4ae1f5503afd1bc9337d6a9342f3e7b0db3fa20.nq.gz
    ├── a59187bbad7c60d2d52624402cf6949664bd286b.nq.gz
    ├── a64655b176672a7708100550e44c96c2468d1db0.nq.gz
    ├── aa8727de5805c0dd7cf3a5dacb212450ca1b2011.nq.gz
    ├── ab4a7bf25f5f967d424ee792323b0f5a7133cf8d.nq.gz
    ├── ac040109f1134206188ec16bd6d647da17bd7608.nq.gz
    ├── af1868de6e0276b3116962665ae231d0327cfce1.nq.gz
    ├── b15c16208c6da6461d6c035a76fed1716a28e6f9.nq.gz
    ├── b354828a80fd8500dd6afbee5d98e6989a85f4c2.nq.gz
    ├── b4c3bbeadaf5e58fd67877ddbcee3be525fa0088.nq.gz
    ├── b5e9e59ee7e931a3fb33424698d0cd5240bf97c6.nq.gz
    ├── b787bc2ffba3f080232e79e760dd2c6e646635c4.nq.gz
    ├── b7d5dd90636c164e80c504b3f7bea51a4601cb93.nq.gz
    ├── b80d2de5ea410b8d3189983c7fc480ba0cbfd772.nq.gz
    ├── b8fa89df7c40937700bf8bc1f77bb5b1a9fea422.nq.gz
    ├── b9fb7c35c357790c8e1d4f5e835c39dd9278090d.nq.gz
    ├── bdcd342168288ab9ece14fd0d2c491ca6a9a593c.nq.gz
    ├── bf332c8b0a2e986eb6d3475f52e79075a20a41fc.nq.gz
    ├── bf414beb6f165c13b9cc174da2b546568f2965db.nq.gz
    ├── c119e1a80624fb8665909554baf7634116fcd98a.nq.gz
    ├── c22451833c7169538d34ae211eedfe79cbed3434.nq.gz
    ├── c3bb318b3b56f293cfb94de824186b3764a53331.nq.gz
    ├── c5273ffbdc0e11902074692334e1ede4fca59bc1.nq.gz
    ├── c59f6a27d40d9dd2809714a43c02d1a203b77c9b.nq.gz
    ├── c7961adc51f0b149d4c25cc3cf98726354a3ce6d.nq.gz
    ├── c8fb524cddbbf378cf2a2e54545cdd0ae56935b0.nq.gz
    ├── ca6c4c945be87d9444aad89aac27ccc2637d4fc1.nq.gz
    ├── cabbeccd9951ef0a2df2a214d86a7b4359580f31.nq.gz
    ├── cb7924ff75225294cc6eac08e89cc6b08222b955.nq.gz
    ├── cba8fe93b51a761d9714fdb147cbb5c1f15bcb45.nq.gz
    ├── cbc853bb9af816678bcdae7d0e5902832c179314.nq.gz
    ├── cd42875e609bef424b1e1cbe940bc13922008fa7.nq.gz
    ├── d51704b494ec6f96d51053586ffd674b75fb4c75.nq.gz
    ├── d5a32f27d06dcd3790d32adb23d2d8e1561e35fa.nq.gz
    ├── d606d841baef3df4b598b1b4e8c316e0adc25bc1.nq.gz
    ├── d799bf2e484703ee0451cb74dc19a4546ac10892.nq.gz
    ├── d8067e14aca75fe596a40e14f6987c36781b4e18.nq.gz
    ├── d8fbc78703969213e2c5afe293731c701890791f.nq.gz
    ├── d9b6de441dd494db912eef7cd8f761235744268a.nq.gz
    ├── da6d498e5eb4720db5fb1ebb4fd9d594603389df.nq.gz
    ├── dc72a2914a6ac557998f49bcdfc7f5578e717763.nq.gz
    ├── dc886d564fcfa342a0dac53b025f30cdc4aa6e47.nq.gz
    ├── de1c01ce67cd2c4836534f1edfaed88973cbaff0.nq.gz
    ├── e2a81245a37f869e66aba09083b37ff4cd96c943.nq.gz
    ├── e42b3a41932a3c68c558345f72b9f553c2b9eb83.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e92ff70e656ff7a7676f2b74309817b231ad0ac1.nq.gz
    ├── e9ca20baa4c6e12a18d2b5b5e62ce613e4de7773.nq.gz
    ├── ed31b7843e1e22a2b6e23982a13950723dc8422c.nq.gz
    └── ef6605d6aa736bcaafe649249434e309fd27d09f.nq.gz

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

[GrahamDumpleton/wrapt](https://github.com/GrahamDumpleton/wrapt)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
