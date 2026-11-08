# Repolex Knowledge Graph of UKPLab/naacl2025-missciplus

RDF knowledge graph data for [UKPLab/naacl2025-missciplus](https://github.com/UKPLab/naacl2025-missciplus), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/naacl2025-missciplus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09d51e7cd6f905fcbf1ee4b5796f701fedbceba5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09d51e7cd6f905fcbf1ee4b5796f701fedbceba5
│           └── chunk-001.nq.gz
├── blob
│   ├── 01101b2ed71ab3ebdb260d5c1405316022d95d23.nq.gz
│   ├── 036436bc953987de69caaad4ec2592ee8c6f5320.nq.gz
│   ├── 058a0e2d4dbcb8d03800f6b3956192c124e5522d.nq.gz
│   ├── 07e6ee7de7cc24cfd4d6ca0bf6b21bd259a10a76.nq.gz
│   ├── 0898c199912ca067033b4de76f652ad673e6d9a7.nq.gz
│   ├── 0ce6a4abe80ac52966f7f72c9aca38e9505e728e.nq.gz
│   ├── 0d4e297463fbebacbdef6590100dad7b8356e11f.nq.gz
│   ├── 0f03e640db50b41e268a315398a84adff7a2f3aa.nq.gz
│   ├── 10c03f4dff958aa561c458b98af8fbf54ea65e9d.nq.gz
│   ├── 13386d4923cccad2de738aac440cca3fc11f3ba1.nq.gz
│   ├── 15f711c87a83a411cdf8d9c2dc64adbaf6352055.nq.gz
│   ├── 1849445b0f01d044b663d95fcc2a545a93fb6849.nq.gz
│   ├── 227cf46130db93e8b3f3428db343dd56ef876f7a.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2a48189b86646a8ae20f8aaff90fae4ceeb8d4d7.nq.gz
│   ├── 2f7ac585b6239f0892c9391d9b75c1b96f7f7848.nq.gz
│   ├── 329ffff2f31fc60b6031005ae786b54e78e01ae8.nq.gz
│   ├── 32dccf202bef0bb58e7653f799dc3edc938bbe3c.nq.gz
│   ├── 331626a430144268255d878c80f0357c7c5687dd.nq.gz
│   ├── 3473f1c535025ab251d4fab3df891350dbe7ca16.nq.gz
│   ├── 356234138382d3d41ee362a081176a7c38d37116.nq.gz
│   ├── 35fe49fbc8bd7a2078a4590768032046354de7e5.nq.gz
│   ├── 3d2ff30d2ff62a32b81581c13d8ee91f16727afe.nq.gz
│   ├── 3f9f12518acf4120c048e90d4dd8f3580e8ab240.nq.gz
│   ├── 412a37d5ca48d15efd4cca23bed255297daadc8d.nq.gz
│   ├── 457ef44bd9d9e1702974b827513d3ccd0e91a0e1.nq.gz
│   ├── 4605217aa18b149e89b2f8721462805e4b568fc4.nq.gz
│   ├── 48a3b0b53dfa0cabe0fea8429ca780c456e067cd.nq.gz
│   ├── 4942d1a148f1015f2fa73929a626a61750c7b5bc.nq.gz
│   ├── 4997fde3730d24dab7d1ced49da1eea2ec497b1e.nq.gz
│   ├── 4d6961af8a8b0bbbbc6fbd870617d94d976ea882.nq.gz
│   ├── 50dd719655cad662d744acf0fdb9da0771dba3bc.nq.gz
│   ├── 51b5a2d35c02a3e8bae373f823165c4f453ebe92.nq.gz
│   ├── 52391168faad7301362c2d5a9f6fa455b42fdc8c.nq.gz
│   ├── 5abb05c66a3277c147b6c5392ef84750e4b54535.nq.gz
│   ├── 5af272906a4a74a2c70926194389abe45e92f51d.nq.gz
│   ├── 5b779f48559e375fa7fc167e9a2d9ec881bc1f01.nq.gz
│   ├── 6cc1478470ad478dc616ef459e89cc50781a5487.nq.gz
│   ├── 6cf0ef61fc243ca801b5b34c5de15e83fe6d9786.nq.gz
│   ├── 6e7ae0d9ac2a34b24b42ce31b3aeba146a006ccd.nq.gz
│   ├── 6e946657f54a504e589dd93d76f5eaa4f01a3571.nq.gz
│   ├── 7053c92adda89dc6978672dec9fd954c7a9889fb.nq.gz
│   ├── 731e67cb3cff11a630d992b907cd4c3923c3579f.nq.gz
│   ├── 745d7c5ea1b25fb5e54a8e57e2ad8d6f064699ec.nq.gz
│   ├── 755be8329a074c66abb1ffd8bd4a9bb96446ca92.nq.gz
│   ├── 76bd3627bf7ce36f53d3ee71eddf8a139810f4e8.nq.gz
│   ├── 787fbfa763f6e00e1b2093b6483fb40656c48e1d.nq.gz
│   ├── 799b2af1737ec3496c076d3d9142e23acaf23bea.nq.gz
│   ├── 7c55c6f6dcf42e04315b3cff8cb9be219f386219.nq.gz
│   ├── 7f688ab3765f1d07a9e2bacffe266bc90ad53967.nq.gz
│   ├── 82b8975942eddffe4e07bd7c84196ce6073e785f.nq.gz
│   ├── 84c02f0f8d7204ad0573b24df352a5702cb7cf8b.nq.gz
│   ├── 8537b105318d48eb964cf97abeea2c05daf42525.nq.gz
│   ├── 85a89a4643012c46fbf7c2c63d11c1c1cb3c1ef1.nq.gz
│   ├── 87a34aea8ea986a310aa9fd0beb46bccaf425dec.nq.gz
│   ├── 8a93e8e9dad23c82c00e1f5aeed6e4f0c7a17954.nq.gz
│   ├── 8b7b06c023384d28ab9e2c9058c40124e660133c.nq.gz
│   ├── 8c96a56b1f5a1ef6cbe4d413b3a6e64e7954a4da.nq.gz
│   ├── 8dc1bcdb3d207e940ed5d5e7e72ea099f440e27f.nq.gz
│   ├── 8ec1837f9289282cfffe8a253a51b5788f7cfe4c.nq.gz
│   ├── 8f4f130f73374bef419200702dcfd6d4cb8cba69.nq.gz
│   ├── 90de1b826ccb79e59483b8ed396c7688410feb0d.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 970c83fcbc8f7eeae8fedc81f3bde7c47d277258.nq.gz
│   ├── 99409f5e76646ce08d6a1366f647fb59b0eeb2dc.nq.gz
│   ├── 9955408af7ef9883eb9940e9048dab0f7075cc34.nq.gz
│   ├── 995b12a3fd194ca7f105be3cf370350fec7689ff.nq.gz
│   ├── 9967a32fd73a48041b45dd0b83ac318ea45aa113.nq.gz
│   ├── 9bb619fafadaa5b2257e980ba268f46903e39983.nq.gz
│   ├── 9cd2c9c5cdbbf5bd2135c9c23254826315410df7.nq.gz
│   ├── 9ea3900255734e6dbadb39c8886f7e60de3fa659.nq.gz
│   ├── 9ed5f4479f39774ddb92de24994fccb1132dcc7c.nq.gz
│   ├── aa32a7dd354841ef276e193df98f9c97803bf200.nq.gz
│   ├── b3d068a60cd4698d378b1e2a81c8a38b919637de.nq.gz
│   ├── b4c3f30d5f3e04f86c8bb2ec91ed6b32d5111af9.nq.gz
│   ├── b58ee4f542c7bfdb5b2994178da42b5e46099342.nq.gz
│   ├── b97749faa43e9bceabf3ac80d7ba93fc2cf8f62e.nq.gz
│   ├── bcc4612ae8332e61c922f6b49c369dcd510276bf.nq.gz
│   ├── c2033f0bc97bd3b052d4e5c54224c15bc8ce4c14.nq.gz
│   ├── c7861a51eb208c56f55935148534ed4e1e2f7245.nq.gz
│   ├── cabe32a12a4e86a4fbaac1cfcaabf98f9a02effb.nq.gz
│   ├── ccabfbabdea7e811b266da42d1de84395a43c087.nq.gz
│   ├── d526908a5ed947a2a0bedcae18de785663906797.nq.gz
│   ├── da6aa8a4f70af3bb7fec51c2703a935529ed7c9b.nq.gz
│   ├── da78bd08a99c2352197d9fe4b56748e96bca7345.nq.gz
│   ├── dfbfe8801b038b2c7527ac88e99f64235980be37.nq.gz
│   ├── e137a30a1512e75360325f8f3a4ceb9d243a7c84.nq.gz
│   ├── e28c18297338d265b900330c45894f8f3a094289.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f962237e355f46e1e5c80fd0bd9d232550e869.nq.gz
│   ├── e8cc1af60b131759b16a89b6d7b3b3daa5992997.nq.gz
│   ├── e98032649eb0eb11a41e9f216800d5b4b1e06ff2.nq.gz
│   ├── ec8c048fb3c2bc79cf16ff5ecaf431f316709dbb.nq.gz
│   ├── edeb75013d5a89ff39b90950653058e142dfe478.nq.gz
│   ├── eeddf90aae4d738ad6c465c473a9771cfbe16d1c.nq.gz
│   ├── eff0de9d37b381da08c2d12cd9ebb7a63b264110.nq.gz
│   ├── f095059701e48a6022da6ff37cfd0d74ba4c3914.nq.gz
│   ├── f2d902b1867ffb99c04097472e70e89c37b30d9b.nq.gz
│   ├── f423e2abda941549e85ce89dc658e8fe2abc2b6f.nq.gz
│   ├── f5118883a66fe9680dd06e97c8b8bcac9cd44538.nq.gz
│   ├── f5cea383e80b8c51c2e7fd2838963c75e7ba0f36.nq.gz
│   ├── f687df880a1955048a83eef84875c9cf7ea287f1.nq.gz
│   ├── f72a8ed3c73e7cabe6b2d2500b3f184c9d9fb3f5.nq.gz
│   ├── f749df8c1291b2c662fd6b4e42a50a2dcc7d1d47.nq.gz
│   ├── fc72a9ea2d17ca84d18677bd4e9061c1f4b34550.nq.gz
│   └── fd680fc7d9051e03c712514fb4fe63a7a7ee9dd8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09d51e7cd6f905fcbf1ee4b5796f701fedbceba5.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 113 files
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

[UKPLab/naacl2025-missciplus](https://github.com/UKPLab/naacl2025-missciplus)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
