# Repolex Knowledge Graph of PyCQA/baron

RDF knowledge graph data for [PyCQA/baron](https://github.com/PyCQA/baron), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/baron
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eaa1062beced93061f1184682290136a82b6a490
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eaa1062beced93061f1184682290136a82b6a490
│           └── chunk-001.nq.gz
├── blob
│   ├── 04bb76801ec5889a51a143abf9b0f8d1a354637f.nq.gz
│   ├── 05c3181627dbe07ac79980557f830a35da19f390.nq.gz
│   ├── 0c9e716f8348071126ffe40d8822a4d943a5a5c5.nq.gz
│   ├── 0eb8f3225e4f07ddb60d8ac9fb3663caf4f8d18f.nq.gz
│   ├── 0f9cca0a3a9c38ff964aba4e5fca99f9055bae90.nq.gz
│   ├── 13432bf287dcd5d25dfa51843120695b4daacfe4.nq.gz
│   ├── 154bba037a19c7cafd4d49a76d04e484f123dd42.nq.gz
│   ├── 1b46c73754259bcc6664093d209bf55b698fcdad.nq.gz
│   ├── 1d1273931cff56a330f0ef3a2d69dabf76a58cf5.nq.gz
│   ├── 1dc23928f348cd2d088362f1b0d4746fd08ad9ce.nq.gz
│   ├── 1fb10bf427c861a951974747df04a79376104287.nq.gz
│   ├── 2204b4f02ade387ea0c60e139421400ad70d976f.nq.gz
│   ├── 23671581c8312bdbd8fc802e19557f3f8bd7ebfc.nq.gz
│   ├── 24c99da49769128a41e072c5901662271e38cb26.nq.gz
│   ├── 276aefd4c3599eba04fd3f1d691c32d76513041f.nq.gz
│   ├── 2d2a856276b13a52d7dd71f7993735f2a6df3fbb.nq.gz
│   ├── 2f7ec19cd12ff3ceaae0b692ac82387ae9ef95c4.nq.gz
│   ├── 31ad5809ac279e75e9f9471a34cbf1bb5060929c.nq.gz
│   ├── 342ddff012bd8541e8fc59673b795e0f8cc2dc2c.nq.gz
│   ├── 35bae932d77b3dca8e7218945813835639fee214.nq.gz
│   ├── 36eb32a3edbfa30a60395e61c2c7a7561fdb4d29.nq.gz
│   ├── 401fc42f9853b30dff53c420df11af8a08b44f9c.nq.gz
│   ├── 40a7518fb717a69a251412d6ba1bbe8848379b89.nq.gz
│   ├── 43075234270cf31bdca8b1821aa4c14bbcef0c1a.nq.gz
│   ├── 44d9e374bed36021234b5f365d8d214d57827da8.nq.gz
│   ├── 50e6cb83a0a04c0bce90a4e1c09265f298f0d274.nq.gz
│   ├── 51854dd89763e9ebd8308b588878f13bfc429a29.nq.gz
│   ├── 5772cbea883360ad9f86d1b1f6a7fbaca174c881.nq.gz
│   ├── 57a10b0f125785abb81a531ae375ab4dc22eb22a.nq.gz
│   ├── 5ca30c75127e96bea441435a2f9a4e923d2c8ec8.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 5e79e3e8a0773af04dde54207606a8db87b4597a.nq.gz
│   ├── 65c5ca88a67c30becee01c5a8816d964b03862f9.nq.gz
│   ├── 66c5d8df8ae054dc3d97500f2b56b29d9bf92bbc.nq.gz
│   ├── 6804121ba3c0cc47299002ace39e0a02efad9200.nq.gz
│   ├── 698c04648562850e88b1799925b024142411caf5.nq.gz
│   ├── 6c4f601266049706b0c08d5829e96142474db5fe.nq.gz
│   ├── 6d064fcc5dd7cd31e91b8766323aa4fffc0bc269.nq.gz
│   ├── 6d0a7416181d3092025f66a8ada8408ea5986c51.nq.gz
│   ├── 6d9629a02835e6f6dc46a6e0647c1c2064d8d1aa.nq.gz
│   ├── 6f45cb8d094aa70757cdbb4c00dbb4372ff4f1e5.nq.gz
│   ├── 77493575fb3a691ce5ad673b489b2b904868997d.nq.gz
│   ├── 78683baf0a592b4c19dbc48f4acee08c64eb17d7.nq.gz
│   ├── 7bc7f45bf0654b9f4a9ce7a68d5a04bbdfdfcb77.nq.gz
│   ├── 7d620f49eb14eab68f69f073c28a88a79ddb1260.nq.gz
│   ├── 7de8e60814830835d9870eec66d2c646f837a2c8.nq.gz
│   ├── 7e47ff3e5d8605936cb2f15d493cf95ee1497dde.nq.gz
│   ├── 7ff4c30600743bc65949c1adeda7d0f53fa4684d.nq.gz
│   ├── 89537c7a96228ef9a878d71c83adebe2778ded47.nq.gz
│   ├── 8b53573557c421cc38d41ee24d89e99e2e6f1467.nq.gz
│   ├── 8c65615601bb4117bf27d49e77f95c7951b6a807.nq.gz
│   ├── 8c67da00594ba9aff3a27e487b009456efaa3437.nq.gz
│   ├── 8d0f9f780fc3eb231df457490a8891a32bbaa1bd.nq.gz
│   ├── 926b23b494f1880ac9ddd499e8b3d519cb015f16.nq.gz
│   ├── 928e30f30d01853f60eb2202e05a4b1aaac47ca2.nq.gz
│   ├── 93b6516dd5f8f567ac5d1a188ee6b8e8a55a187c.nq.gz
│   ├── 9b2eee2a3126acaf1616de0d10ed97cab4a733f3.nq.gz
│   ├── 9e99dae642e52e89908fe5f66dfb9dedd72b8495.nq.gz
│   ├── 9f21aacf6a27e86abfd6701240f11a5cfe8ec082.nq.gz
│   ├── a0ee8d7af3f9acccb3292b0faab8797f7a8ad60b.nq.gz
│   ├── a65f45cefbd33d2fd817470fa4f1effeff732a5c.nq.gz
│   ├── a6a992f8184c0f8c88cf05506a4f360219363338.nq.gz
│   ├── a70a612bafbf1691c8bfbeca79a967d7cee41e35.nq.gz
│   ├── a969a1d17189a86a97f548ea3af8ab2d01df1a3c.nq.gz
│   ├── ac263acce88717d77316840dd2f0f54ce103f394.nq.gz
│   ├── ad2096ee79b057871112f7bff0e2a78d7338659c.nq.gz
│   ├── ae865420809077c8a25add03915c416b1c4fc260.nq.gz
│   ├── af3df67d9819700d63b72baaed4f64152bb5b822.nq.gz
│   ├── b0661ce744839d59bb4db3cadfc569d371e222de.nq.gz
│   ├── b5152bdb294113ae4719aa317fdfabe6fb4f57c1.nq.gz
│   ├── ba53b503a85068351e255fce7d5479158f2eab66.nq.gz
│   ├── bb1dfba1687b2e098297f8922d239adac3a74be6.nq.gz
│   ├── bb2d8522e19302f0cf906efc56864b16547d4abe.nq.gz
│   ├── be4a7a8cac7a4bc019c4159e77365382e58f71ed.nq.gz
│   ├── c772a7a5648eea0d084bf20408f2e4d496fe397f.nq.gz
│   ├── cb2fd94888e410174225507e153827d17c1ea23e.nq.gz
│   ├── cdf3daa82e41bea19144a6810ac23c7ed08b8e24.nq.gz
│   ├── d16ea9c3414aba2bedab500861eaa40b21c4cb83.nq.gz
│   ├── d678c50b105bd9be1b177e0f511e3192c94234b1.nq.gz
│   ├── d67f7b2b9786083e4985568ad43515f2999d4e22.nq.gz
│   ├── d7aaffd60e1404010695280be705949c13ac04c5.nq.gz
│   ├── ddc1dbb5065377a10cbd4e8f12ea5ae6f879f4c5.nq.gz
│   ├── ddd85cd9647eda40e4acc0bece5c13c863d7a11d.nq.gz
│   ├── df184b056e2c37c35e60c2f66a2c3df8911fb2d9.nq.gz
│   ├── e456a95b6374cb0eab743aaf622f108742779f9f.nq.gz
│   ├── e64a7ed7d500a76204375e8953cd67b6824c2caf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e767356046398ab2fa644688961b1ef355a212f5.nq.gz
│   ├── e833d40e26ef498cab72386618b9ac0a73186815.nq.gz
│   ├── e8e957a983580c44ac7514e542152b02b9037e04.nq.gz
│   ├── eb51da4cdd8e5ad73058a971e4c6cdaf00aa60d7.nq.gz
│   ├── ec5f1960a4fc797079d07f147c6bbcdc70eb0f1c.nq.gz
│   ├── efb49ffdae1dcd38d129282bf7ad0597b246a0a9.nq.gz
│   ├── f4703c368ea4272396c332eba69354825b4ea5a5.nq.gz
│   ├── f4fa6ee87dd4ca6c3d8b88a8358fde45c68f12b6.nq.gz
│   ├── fb34fe113bd8b61f877b740271adfa1bfef851a9.nq.gz
│   ├── fd58b5cea9fa97880fd210b4537632c9a090b478.nq.gz
│   └── fefa5751d3118ade8f34387667a8a57c1ed3a90e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eaa1062beced93061f1184682290136a82b6a490.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[PyCQA/baron](https://github.com/PyCQA/baron)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
