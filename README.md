# Repolex Knowledge Graph of NousResearch/datatrove

RDF knowledge graph data for [NousResearch/datatrove](https://github.com/NousResearch/datatrove), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/datatrove
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22606036e92c8d83268f313f462ee98eceb3fa0b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22606036e92c8d83268f313f462ee98eceb3fa0b
│           └── chunk-001.nq.gz
├── blob
│   ├── 016d401d10b20738cda9abafebfbb6bd0d274024.nq.gz
│   ├── 05e0733921afcbff195542d32fb51801515e1388.nq.gz
│   ├── 065496a21c8669bb765e5711a710be65bc056039.nq.gz
│   ├── 08204030faf3c9e06fdb9dca1c3f8196161a3f13.nq.gz
│   ├── 0c6900794451990de07e70317cb52e92c399b64f.nq.gz
│   ├── 15fcf8bcc71482606771cb0ee32ceff07669eb52.nq.gz
│   ├── 1868dde2326e6e6cb3015216c2959e50d95732b4.nq.gz
│   ├── 1b997b875b4be47b07088967b75a4284417573c2.nq.gz
│   ├── 1b9f0131ad26be2e7a32da3f7b0be23445b84403.nq.gz
│   ├── 1d8356fa6f064db7050227d00861cef0769a6207.nq.gz
│   ├── 1fad1508a7ed25dc20e05d293613b243475c6182.nq.gz
│   ├── 21337b9bc49bccbc9b6645cf9b2451b7c3f663a6.nq.gz
│   ├── 249bf964ca67fd213cf37090b7f9fe86442cb831.nq.gz
│   ├── 24d76a183bd8b24793aa73d1e26b7d985ea778e0.nq.gz
│   ├── 255c8853a182f82eeec7e568d3b78a5e008dceeb.nq.gz
│   ├── 258636e3545ecb3040078423e8d3f0d1040e459c.nq.gz
│   ├── 260b4235db592b9f9a589a9f1da06a9bc847b895.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2901e388207fdad195c98e8950d501312aad2541.nq.gz
│   ├── 29359aa793d5edf00bf7fdd1a4df4222091af1cc.nq.gz
│   ├── 29f3b1d0b30f3edbbdc20972b19da99bff59c399.nq.gz
│   ├── 2ab5298df1b6b53cd62af3efae75a6990604885b.nq.gz
│   ├── 2ebdb647f7915108e6cfd875b12275bd50f03dc9.nq.gz
│   ├── 2ebe82e8ff66172cd000b5ad362a5fc98b504dee.nq.gz
│   ├── 3155cffe592234e9de3b334277012ae7f7bfdabd.nq.gz
│   ├── 31ceee083d85cdf7630ed25783deaa3d2406dc52.nq.gz
│   ├── 36347e3058507e3674fe15c7d657751ab8141fef.nq.gz
│   ├── 38644992a2a6e18299e976783fdbd6a23d25bcf1.nq.gz
│   ├── 3a0df8a9146233696c80a8d13f9ce1609cc2d388.nq.gz
│   ├── 3d076308b04a12031c2b9b8d85d72c41ff6cf635.nq.gz
│   ├── 409e97ea31aa32f5ffdd6c903803b11e8faa150d.nq.gz
│   ├── 463e002d0ee4ef984391a5b9d3c255e11e1f4ff2.nq.gz
│   ├── 487ebba1d85863cbd0c75d143e83642c1b57c0ad.nq.gz
│   ├── 48ed26018394117ce32a51df369e422daa08f6d4.nq.gz
│   ├── 49a50b91b4287ac667243777dc7e992d990795d8.nq.gz
│   ├── 4a05fc5df76995bbe41ea8c9e7939e23c712b989.nq.gz
│   ├── 4a9503c2e099672f182800cd230dd3f979005ffc.nq.gz
│   ├── 4c0d4911ccabdc0a7633e9c3a2b5ac3f66b37902.nq.gz
│   ├── 4c598a59b367d31ad27962ddb84def7c63daf3b1.nq.gz
│   ├── 4cff7daa0a1596ee0586499d1f0d94182dde79c4.nq.gz
│   ├── 4dce04be19308958ec8e26e0e2e1342126ab8ca7.nq.gz
│   ├── 4e5aee23771af764bef49ca5ba1c129ab874e957.nq.gz
│   ├── 512f56c78e23e3a497fbe9e19e82742c7336eb57.nq.gz
│   ├── 52323c54e4c6bc1ec2d83f8460ae64ffa54e76dc.nq.gz
│   ├── 55e8ec644d8eb8eec767fdbd074460b103787071.nq.gz
│   ├── 58b2b4da150fbadbc2a3dc56fa2234fd86f9481d.nq.gz
│   ├── 5a4a4276a734bc3b6b1973b930647ba5494cd0f3.nq.gz
│   ├── 5ebb3cc82dc2dbaefa410c5a6a423e24fe4f2c29.nq.gz
│   ├── 5f460e7d967438bc4a194e4f4f3f3b3aba6f1848.nq.gz
│   ├── 5f678cf6245a430fd8808238bcc603c75d03f314.nq.gz
│   ├── 5fbef257507d0ade5d41fd4a74280075fadfa52e.nq.gz
│   ├── 6448820cfdf7fc11807c4bba2b52ab8060f19eb5.nq.gz
│   ├── 652a85ccf6f28eb7f426d34ddc6956dc260a69a0.nq.gz
│   ├── 68e94c764f1c597c3b91458993587791faae0e7f.nq.gz
│   ├── 69651d0fd2f9ed984b65d3f46d961c6eac15e34a.nq.gz
│   ├── 6a4b96ce095aed9dfa6f43ccecbf8ddcd0852ace.nq.gz
│   ├── 6f0062940ccb91a0d1109335d3ee531e1a4bfc98.nq.gz
│   ├── 73d2d3404199b9114be61699a55a55513b8c9817.nq.gz
│   ├── 763e5c37fa096f0bb57fe480cebcc0d47ce1d89d.nq.gz
│   ├── 777a2cfb9d1832371b88fb252ef6ba753c1ef741.nq.gz
│   ├── 7894b56d543947e77593fc6ece571ef1f22766ef.nq.gz
│   ├── 7ab7d3d4a1bedbe94b5542d96e901bccebc401f9.nq.gz
│   ├── 7b7d6c707f5d86011c49d6953668ea2479c2eb68.nq.gz
│   ├── 7ff45c8756c401bea5188a8473d5acf3949a4a53.nq.gz
│   ├── 8106bafad66558e65add1f063b8fd861dcf134c4.nq.gz
│   ├── 810de9a1a013890410ed067fd86bb95d699a66cb.nq.gz
│   ├── 843e2c5909a9b22caade5844ac739c6a65d75f05.nq.gz
│   ├── 85d76bb308978b37a50e30d4f3cf37566e50d33a.nq.gz
│   ├── 898c739999b9f285e37a842469f423857ce09235.nq.gz
│   ├── 8b09d6d8143186ef29aaa3db8309278da698d51d.nq.gz
│   ├── 8cee638b2269661400cf9bc37e607191b44bac54.nq.gz
│   ├── 8fc84dc011546ea98f1464ac1b145be8e5442896.nq.gz
│   ├── 8fe16d521042b4956acf0545c98fd24227188706.nq.gz
│   ├── 918d95a47190e0a44ab79d246fbf4c617cde4895.nq.gz
│   ├── 9259c8b37144c5987bc2f413516e8f5e5c51fc27.nq.gz
│   ├── 92e7b9ef861028d5065383b3662231ce041f38b1.nq.gz
│   ├── 94041f017d40d48ad38cf33e6e5041bc5fe2df82.nq.gz
│   ├── 9620bd2f8e4778186ba86aafcbb3c9f2485c99ec.nq.gz
│   ├── 97ad9488d7dffd798c4e155703f578abbb80e3c9.nq.gz
│   ├── 9b95b1ea041ec10c0b37203881d6db108b3b9e1a.nq.gz
│   ├── 9bf169a1eae658f2ccefdc7013af81cb0370664b.nq.gz
│   ├── 9cbbf6803724dacc4759b69d7002bb34831e5937.nq.gz
│   ├── 9d859a43045aaf7faa10111c140a4e21d9fc7bdf.nq.gz
│   ├── 9e5e68b651f5fcb8f0d03d14f26ff43958fd2389.nq.gz
│   ├── 9ff4b4a430579712ddd42da29d2730fa7326c2ae.nq.gz
│   ├── a013766bd4d555587c62caa9fda7b79a27368c69.nq.gz
│   ├── a2e0756ee1dbe1ff5748856fe2a9f2c97bffaa8f.nq.gz
│   ├── a42f6294298f47b4e54151d9327a58b2b5af6b89.nq.gz
│   ├── a5bd5174a20dd40a2abf34ea7406020120cc3cc1.nq.gz
│   ├── a9e200ee62aae0e6aa387050a010c44603199052.nq.gz
│   ├── aaf5576e5634e3bcb6021ab6eb0a95d9404ae6e0.nq.gz
│   ├── aca0b24ca18f690142fe9ff9302dfda8b1b0cd11.nq.gz
│   ├── adbbc35794def0a51cbcf8a48b7374b0d0b46463.nq.gz
│   ├── ae268901ad7cdb39c260d77e0b0f6c6cea40ce93.nq.gz
│   ├── b0c52038551dbc5390617ba7f9dce30f80be9381.nq.gz
│   ├── b401a968b86300a3795d46d670b61311b60a08e9.nq.gz
│   ├── b892a07fb28af0e43938eed11c560e6583dd17e9.nq.gz
│   ├── b90ed859fa8af6c863f7453cfe6b19cd5af4787c.nq.gz
│   ├── bc9a2cac28ddff1f825b272a34cd66b5d1f72a85.nq.gz
│   ├── be270407d3e66a59fedf9f18dee4ca81a2f59d88.nq.gz
│   ├── bebaddb8116458e93aae5872b47e5a1bcb1fb4d2.nq.gz
│   ├── bf2897991ce718b5204c7f37934cc4c46a3dd5f2.nq.gz
│   ├── c0582459081dfbadab56cf9ab36fb9241694a339.nq.gz
│   ├── c063f1effe7fdf468a35c2f88dd041520b4b1d9c.nq.gz
│   ├── c27ac4fb74ad43eefb2a751bd75d3424088da23e.nq.gz
│   ├── c44344274f0e1f835bd9eb3851f06c927477de15.nq.gz
│   ├── c4d981141d2f1ac998d858ba5272005ed598e02c.nq.gz
│   ├── c4f6f25f61fcfea8e479ad2a50bd229e4f09b9b9.nq.gz
│   ├── c5d51aa2df7f9d46539ee5bfede9f53ba1044ee0.nq.gz
│   ├── c5e8f2f9f32e67c6f4f16d1b1f6f4d2b741076c7.nq.gz
│   ├── cd2e735b136c767c89c837eaf21c7999053efe0e.nq.gz
│   ├── ce1f4808363281ffe2e625f9bbd4d852c9002bf8.nq.gz
│   ├── cf52a7b4d88710eee8a3e8a09986e3ce2953b553.nq.gz
│   ├── d016ba1589877834ffb90e170d9cb210dfb4a6e2.nq.gz
│   ├── d0be899aa4609258141336a9e41e1cda3ac90ca1.nq.gz
│   ├── d2282c93658ccde25ab6ca7f37c0acbdaf2c74a1.nq.gz
│   ├── d53187601dc8abf92e7690af829eeea92e123dd4.nq.gz
│   ├── d777b48535b4b2a8e8d1342bced7640974484d5d.nq.gz
│   ├── dad66dc8ce8431e324631d36c289a91817a51679.nq.gz
│   ├── dafdd6bc32a4dae4d8c3db41605b31bba5688df4.nq.gz
│   ├── dd3a1e2d9774a651e088c2dba27ef50028d5da2f.nq.gz
│   ├── dd83f3ba3dba17f3b420f39f7a730236cfa1ffa9.nq.gz
│   ├── dfc3ca5f141d61c276e46af479338f8bc8005453.nq.gz
│   ├── dfd4a1d4b5ac06cb547ca12b1062a3e0c5ccf70f.nq.gz
│   ├── e068eb85ea1e583a0f1cf64cbead52ffda9f72b0.nq.gz
│   ├── e61a0b64fd72266348248bcdc5e2c2f87ec5f15a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a7e8cf16879acc94e61f21f317772ae71ef80f.nq.gz
│   ├── ea420b4ec300581bea2e1d33dc0fb4b65080ccf0.nq.gz
│   ├── ea9b7c903c0790916c1676f7ab0953456c34fbb4.nq.gz
│   ├── eacac71334d052285f7e06a97c34e60954b09304.nq.gz
│   ├── eb313302bd86962995be03abab2ee74e0cc82c20.nq.gz
│   ├── ec7e1417a86cb7ef81b99cf5daaf698f90378e24.nq.gz
│   ├── eca0d5101e9b96207ace90001e16f918b68168ca.nq.gz
│   ├── ed2cf4d5eae5ba6cd010766224ff368b82784f58.nq.gz
│   ├── efea634c33b8e4096b97adea06c47e5228dde8f5.nq.gz
│   ├── f0f437eb2e1a91cafd4a878a53fe9d3e558ed45b.nq.gz
│   ├── f2d71a8573cf980e6558c496559426f538fec528.nq.gz
│   ├── f37fee612579da87d82b18dfd3d71ea2995fd31f.nq.gz
│   ├── f3ab55c8fd249adeb4c64b1bb0985075c4b85b33.nq.gz
│   ├── f64438981af1b1d29d06343f040a6b3819fd31b3.nq.gz
│   ├── f9344267219b2d1c334693ddfd1c970be92387ce.nq.gz
│   ├── fb6a33c7f0d77b2ba274d244f885e9b1e41f29fa.nq.gz
│   ├── fbdab672c616cda377c4fd07a3db57c71aafba58.nq.gz
│   ├── fd7ecde2362c49944f2cf1cbc8b70144ad2e7aed.nq.gz
│   └── ffcdffb01d6c4bb7bda56a111e054781f7c758ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22606036e92c8d83268f313f462ee98eceb3fa0b.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 153 files
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

[NousResearch/datatrove](https://github.com/NousResearch/datatrove)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
