# Repolex Knowledge Graph of tiangolo/asyncer

RDF knowledge graph data for [tiangolo/asyncer](https://github.com/tiangolo/asyncer), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/asyncer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── de024c755ca2a5bcc71728fc798b4db210feee04
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── de024c755ca2a5bcc71728fc798b4db210feee04
│           └── chunk-001.nq.gz
├── blob
│   ├── 05eb32df5289cc54cd4138cdc911cd12fb23f13f.nq.gz
│   ├── 099aa16e51d5905f441b409ad3f3877af2d63e17.nq.gz
│   ├── 0b0297eae734d67ad5a53bffbcfa3fcf8444ac54.nq.gz
│   ├── 0d642b5c35c754456afc6a9947f946ca02b5e246.nq.gz
│   ├── 1107f6428eb86c07486e709b77f547a4be7504c7.nq.gz
│   ├── 11358ce551e0b59be55bfc8172695a2e829138ad.nq.gz
│   ├── 11bbf09b5e073869363186a468b38af280ebce91.nq.gz
│   ├── 1271f764d8340cabadc879810597a1dc1079c6a0.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 199b86d1c627c87d443ed16e440612e62fd92e24.nq.gz
│   ├── 1a78accf6dc9f88bb0a74784f1a7e800e6e05035.nq.gz
│   ├── 1cee1aaa1c2c092b32dbe0b13d29adfbcfe5c78f.nq.gz
│   ├── 23b9fd08365426e106006a09a21017c33d76ef30.nq.gz
│   ├── 255efa5c4e179deb949c9498ff9b64b375734b63.nq.gz
│   ├── 2803759abda8938d4da3298c59508a553cc33716.nq.gz
│   ├── 2c09574e3dc7c416801e605dc766dbb5a0db9252.nq.gz
│   ├── 2dbb44fad86d5133bab81e06cacbb633ac29ffd4.nq.gz
│   ├── 2e0061f5e5dfaeeda49d050646d0a8c35a129f0d.nq.gz
│   ├── 2ff4779e25a475faa96f463709b03f12016c405b.nq.gz
│   ├── 30fcffc8a956d90c5d1fda97b139cf06d4b4d975.nq.gz
│   ├── 318c3c2fb01382a87e7445511c4701c3a63bfb40.nq.gz
│   ├── 33e22c2ab1b24ed59c4a1edd661662a48879fe2c.nq.gz
│   ├── 3903ef9af377af5479c26ada9e8cd351595a64f8.nq.gz
│   ├── 3fd86a6cf006e3027beb82de73544e47de9b7318.nq.gz
│   ├── 4081ef528bd1588de2426a7ec1a828f64998ffa7.nq.gz
│   ├── 431dd8c7944c465aacfb09d692008045429c6c74.nq.gz
│   ├── 432ea139e2cec819e6858f2f663a6286540f2a05.nq.gz
│   ├── 459fd4dc020a2c33b7cfde467fe810f554492378.nq.gz
│   ├── 4c2b0d4e117cd889ca2ca1fb7048fb04f8bd53cc.nq.gz
│   ├── 4d9144e37c1b0089a15c5d4e81020bc6429bb198.nq.gz
│   ├── 4f451c005d56140a69ade7f2f3d89d525cdc8655.nq.gz
│   ├── 52bb986b455ec89df30d13e88777f393927fd807.nq.gz
│   ├── 545d30a18cec93495328868463868efc1fccb7d8.nq.gz
│   ├── 563f1490ceabb4035eab7c2402f25e989736a767.nq.gz
│   ├── 588ebf30792de259b544c38e61a717d65383e510.nq.gz
│   ├── 58bb20b090879360085ae7da8764d458648c54cb.nq.gz
│   ├── 59f73f1fa78a8ae0cccb627c4ced943fa6b074e7.nq.gz
│   ├── 5c83954285c970868b13fc680fae9835c2565dd7.nq.gz
│   ├── 5e20c99d8db9ed81c51229d6d07f6ba339413c53.nq.gz
│   ├── 5e390e6edfe324bc3da163624625d8d9a561b821.nq.gz
│   ├── 5ee1d8ae8f64bf6f719850057dafc15f4a80b9a2.nq.gz
│   ├── 6356116c2608105a14aff26895a64cc7fd83f094.nq.gz
│   ├── 63722e99bdecb0d100c28c6475aebc8c55202f50.nq.gz
│   ├── 63d2a617bb6a091c7d2e5f9ea20a7bdfe8f192e6.nq.gz
│   ├── 6694183a06c6903251721c75c9dd9b8c2cd7ee8c.nq.gz
│   ├── 69c3e6fa9c4523edffef1fd49760e640801152ce.nq.gz
│   ├── 6e6487ddc63a67bf3980fd2cb9ebcd72cf972d4c.nq.gz
│   ├── 7231b6aff718e84a4c66dfe7654f2a3c0a78c1d1.nq.gz
│   ├── 73ea40f2ff49cd7462f743566bfa59d8709f1c5a.nq.gz
│   ├── 7a90202642f7d3f6f1c98468f5da6ae3b898442e.nq.gz
│   ├── 7b39f6922c155ddf7c57f55c4c1f7837802daff3.nq.gz
│   ├── 7c35c18f1a71494157e5a8d31720552ee300a5a7.nq.gz
│   ├── 7d5d6142be57896e36f20e55db98ee9440d0843d.nq.gz
│   ├── 7d7262d83962caa290ac24c8523dacccd0a3ffef.nq.gz
│   ├── 8107366c1795a073458161dfd68270daa722f56a.nq.gz
│   ├── 895e2ff48eac8693b9a5c5c5b57eabcb7f684f26.nq.gz
│   ├── 928d6696fc3fa9929fea0dd958589dcf15d1152f.nq.gz
│   ├── 93bd4535110341f797b453df7143ced54f6a0454.nq.gz
│   ├── 97cf7f4f830a9c295c25aabc34aba2b6731008b2.nq.gz
│   ├── 9ca24fd23776f0a53a35a592f01930abb898fddb.nq.gz
│   ├── a1267e60bd9d0a971b2dabcacd9d72d5f98f63d1.nq.gz
│   ├── afce36ecbc93fae6e0d1f4ef48efbba9ae568b39.nq.gz
│   ├── b21e5f2887e126ac03ad40d0081de296c201fc3a.nq.gz
│   ├── b34a5be01f646c7813253fd44d8b51420e25c47a.nq.gz
│   ├── b4d1d5dc46cb6ba8c4864d879317700e082ec08a.nq.gz
│   ├── b69f523abd8b4023cf5f5be6de14beb501aa3ab0.nq.gz
│   ├── b8e04714dd8c045eae01d61e5f8382baf9d3e4db.nq.gz
│   ├── bccf2c5025a2ed3d432b48098b25598af32def30.nq.gz
│   ├── bed73106de9f399ae9b607eccd507a9c0356690e.nq.gz
│   ├── c35e20873bddd8af3c32e35a197291b3c88b2a8b.nq.gz
│   ├── c39ecc211e2235b1638e69c4ca0bf81d88a29003.nq.gz
│   ├── c448159c0768330c8e7656476ff81cbfdc0f9697.nq.gz
│   ├── c546fb7c3265d2bbb96c7d7bde338acdcd0553af.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c9aa5241927d47da74b344d6457b0f8f474324ac.nq.gz
│   ├── ce2d4512aa2c081251c80377a812c5813c8fa6f8.nq.gz
│   ├── d1fd7ab4cf80c4562b1a3ad24125d6871c405ec8.nq.gz
│   ├── d233a7833b6f50e927a2d26573b37f978b50aad7.nq.gz
│   ├── d312ddfe144106a57d147b9cfc3cda6d0dd94a95.nq.gz
│   ├── d811d979e4fcef8bf557a76d4559fb03a18d1573.nq.gz
│   ├── d8478be5edb0e1940a93aed42220d10d08f5b4bb.nq.gz
│   ├── daa6038a0a8a386d6315b541c501a9a2abddc650.nq.gz
│   ├── dacb42816e0a7e3f48b9057586930e849d57d4b1.nq.gz
│   ├── ddbc360a98d000f1e1bf4e16671f893703927865.nq.gz
│   ├── dde004a003ee71a6682ee66faa2c8cd415113305.nq.gz
│   ├── de4d8d1442e93d761007e4be0c28dcf6b157d8da.nq.gz
│   ├── df749a9fe536d393adca21c19f854a69a9acf466.nq.gz
│   ├── e253176a6365a8398efd2d4239db24693252e3d2.nq.gz
│   ├── e3b2da3752ef5dc647eafd6f66a2ceb33d3a05ac.nq.gz
│   ├── e52950484f735766a0cb19057fec86e493f96bc8.nq.gz
│   ├── e53efe7db25b0ae11cae77a4f4ad745024b0eec2.nq.gz
│   ├── e68fe916ab8708ac17e0544e09d1d9e5f977d52a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecd1abdaa71524d60f7dc1f2fd9b7e552cf66e11.nq.gz
│   ├── ecdc1ac8be9148eadaaed33363331497734afbfe.nq.gz
│   ├── ee3cb46fa1d56971af220ea9b71e590a7edbf9cf.nq.gz
│   ├── eee0617f3baef7e070ce2b9c12ddcd973a5f60c7.nq.gz
│   ├── ef6ab6d455bb3b8e7d26d18f772553ab5ceaf4e6.nq.gz
│   ├── f21484370dfa474aef9d3ffcef0bcebc44c53b9b.nq.gz
│   ├── f2bebd127c13001cca61714d373ad0124b7f1c50.nq.gz
│   ├── f5b74b4744411a29c632c97c18b03668f8b341b0.nq.gz
│   ├── f84e1eaff6f837cc01c8c65d323fb30b9fbd5154.nq.gz
│   ├── fb517af86d6e2e02e5c48646fa652ca463aecc43.nq.gz
│   ├── fbf38accf424098312123ec7b5330f9727b52f12.nq.gz
│   ├── fe94cbeb2ce5261b1adbd86e4206208cd8d794f8.nq.gz
│   └── ff4b114b186342c2380e790aa54ac24eb506b217.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── de024c755ca2a5bcc71728fc798b4db210feee04.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[tiangolo/asyncer](https://github.com/tiangolo/asyncer)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
