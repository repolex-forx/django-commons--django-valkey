# Repolex Knowledge Graph of django-commons/django-valkey

RDF knowledge graph data for [django-commons/django-valkey](https://github.com/django-commons/django-valkey), parsed by [repolex](https://repolex.ai).

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
rlex download django-commons/django-valkey
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 33bf0b0b921b9966bfeaedb9a9405018ef61e7ff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 33bf0b0b921b9966bfeaedb9a9405018ef61e7ff
│           └── chunk-001.nq.gz
├── blob
│   ├── 034c7f25308743cdd65a9103a2ab3e30c2fd3f21.nq.gz
│   ├── 063a7d7dd6f70e7af38bf01b762619020e1ed028.nq.gz
│   ├── 07431b247c3b238587627df77c99187a8f8af88a.nq.gz
│   ├── 090b83d717212dcdd78fa27749b18748cc387a69.nq.gz
│   ├── 0af6b34798c5e8ca3805041080bbb1e5bcf10d27.nq.gz
│   ├── 0d90b7e110f4bac74b7bf236e3dd10c2c4dcb875.nq.gz
│   ├── 0ec7d7c25d6d8938a406c92f4c0e32cd53017250.nq.gz
│   ├── 11488a556396088785c99c33c6abf522418c915a.nq.gz
│   ├── 1b73e6dac8f966e458ed9d94781e946724d1208b.nq.gz
│   ├── 1bd928cd3215e8ca2bc3dc22a6d78116086359c4.nq.gz
│   ├── 1d2b6eb89c533de39772cf956d1046be2ca0be69.nq.gz
│   ├── 204300268c19975d4896733903cf4242e98c862e.nq.gz
│   ├── 28bd72cac3984712919ab2da3d4d4a63495f55e2.nq.gz
│   ├── 2c9701e3cd371b2518099ab6cf326b58a1eee9ec.nq.gz
│   ├── 2d85d9c62b77060be9b74effc6ec57b3161e73bb.nq.gz
│   ├── 34ac3bc27422ad1f029d99348711125ff7a0be6e.nq.gz
│   ├── 34c0e51825a3eae5bbe0ea9e157ccb1fccc2e5f0.nq.gz
│   ├── 355b67947aa304378d5e4e1bdd76784063bf36f4.nq.gz
│   ├── 369b95eef5333819ae7602d872fc27b33193ae52.nq.gz
│   ├── 3796d179bb5460ce5176fc25e6182e640ebfaf38.nq.gz
│   ├── 39d4089b29d7ecba6ccafe2a537cd353b06b5e0c.nq.gz
│   ├── 3ad63167d0defdba73fb314b898068099dca5990.nq.gz
│   ├── 3dbcb32ab2ba23884471d149a6f1babdcc4668e4.nq.gz
│   ├── 405cb2c529c8e5bb48c82991200f9abf4ef83491.nq.gz
│   ├── 40aa4bc92bb74109ff62d01231f292c657da7063.nq.gz
│   ├── 41721ffbb659634a1a5d27af58789ebf7fefaf76.nq.gz
│   ├── 41e45bc1d04359ba9b918edb901190e11edf499b.nq.gz
│   ├── 4afadbd89b7f1141186b2302c172c373d590d8aa.nq.gz
│   ├── 4fe5e9c2141f0f9f7022df743bde46345ca35311.nq.gz
│   ├── 50a454aadbd736cff235d05a902b884fe26cf96c.nq.gz
│   ├── 5250ced4f4c773f56487a6ee5d3c14e38b6ba649.nq.gz
│   ├── 52a7a443e069a77611d74c71cbc1784a970084aa.nq.gz
│   ├── 5358775de58945fc0d6532a50f01d708ccd8b55b.nq.gz
│   ├── 559588002907fcc6e28c80fca3e814524c71aaa2.nq.gz
│   ├── 5687080955380cbd2d3c791a355992f53bbf0493.nq.gz
│   ├── 58b2a22d4e3dad98e646f1740d99b98645cbf262.nq.gz
│   ├── 59797e7d19960e70cb8d8bfd2fe0cfb01532a6a2.nq.gz
│   ├── 5a05da3a9168eb886be743e2d6225f826578a512.nq.gz
│   ├── 5a4384f3e9930e1de1adf14d14fa69e3c47322a9.nq.gz
│   ├── 5c380d2685fb38bdabcb92c99643998ac6cb20eb.nq.gz
│   ├── 5e0cc386faad129e4f702bf91dccf46eaa5746b6.nq.gz
│   ├── 6479838ac04ca9c55985a6513a117668edfa6a47.nq.gz
│   ├── 64b49ba5ea42c8866521839a817330d050c507e6.nq.gz
│   ├── 662bbdd4d511b5e170566949c00170312a082e68.nq.gz
│   ├── 690f285ee2ba749a914fa40a26d6033f3ae8dfee.nq.gz
│   ├── 6b2ae20937e4eb5f40ec9e45530ee4a8396bbefb.nq.gz
│   ├── 6b9cba7488042108d659185c0bcabccad7be29d9.nq.gz
│   ├── 6bf4fff8ec3b6bfaabc86f9a38f0ffde29d8c6b1.nq.gz
│   ├── 740bf606b74ebddb7c0b2351c21f778761085e1c.nq.gz
│   ├── 74159c1e0b3985b77f75791109b9875ebf046f6a.nq.gz
│   ├── 76ed98e92e6e8a01f5ade4e6817711b0b4d4763c.nq.gz
│   ├── 7866f2e931f95c0009319c23bb21e5ff292fe6fe.nq.gz
│   ├── 79ecba94e576932b7c0fd8800ce2765453551656.nq.gz
│   ├── 7b34b59e23d96cabd35188092d1bb6d45305bc34.nq.gz
│   ├── 7ed72b6ca390b623a56254c9e590faae29e9672f.nq.gz
│   ├── 805a658cb91f47962ff02eec31de2937e86a7b91.nq.gz
│   ├── 80bdadf6f8de7ae3ba5ae9cf96ee8064afa3b55a.nq.gz
│   ├── 8358468862a1af9d0f03a1737667ff5214a3c36b.nq.gz
│   ├── 837ffc9e7c3af0a3aa7363b952e5d2c6fc88b14b.nq.gz
│   ├── 86749e9b19dffb9dc330a120ceae30552d2f88f7.nq.gz
│   ├── 88fc342fc14e4991633aef7ea49678b28a865eb8.nq.gz
│   ├── 8b62eb4c92efcb6f7df1b695b37b963d3b6a5520.nq.gz
│   ├── 8e2c680f60100b3cbceb541d4c9387e474d9055a.nq.gz
│   ├── 946732693ef73ac2297f8c5815316edcb640a7aa.nq.gz
│   ├── 946bdfcaa4602e64aecaf639ae6d987db6ed7c8e.nq.gz
│   ├── 9933cefcc988ef93fd491a8ad1a32158a9592864.nq.gz
│   ├── 9a380c5b8f7a2b28e4f686faed0b4224b0d75401.nq.gz
│   ├── 9a51150c6b522231ced2a3a223c892cad8f89d98.nq.gz
│   ├── 9c2d8a438a14454a1fdd35fcbec99d676fef94ed.nq.gz
│   ├── 9e6b70b2c646282a718c65f3f476c06a1940833d.nq.gz
│   ├── a3f95561202baacc8ad8f25e34feab9392ad610e.nq.gz
│   ├── a4e3ce261915d3062bf2eb5f0a10bc28531d9750.nq.gz
│   ├── aa16d218d6fd9e1fd73db2c4344baccc77132362.nq.gz
│   ├── aa3b568cb187862cb0458dfa6348cc395aafe7bd.nq.gz
│   ├── ab75354956b177c406e14ca6976cdbc60cafc6fa.nq.gz
│   ├── ac4914876e2cea6694663ff01210d2c424900e5b.nq.gz
│   ├── ad91b9cfeff371e48355127dc8d2645c988c4d0b.nq.gz
│   ├── b06e5bb8822b0855c2ea3da866ecd88b0f915b20.nq.gz
│   ├── b1943d45eadc6370eb5441fcadbfc12e36b1cf22.nq.gz
│   ├── b1ae92a6bfe6f311af1e36e7f564bb3c145f1814.nq.gz
│   ├── b251449e9587a6c5c4f4ee3c2c6f75149638bbe0.nq.gz
│   ├── b89a494ccab63737cc2dad412bb5c15c8b1de734.nq.gz
│   ├── b9c1682a1c2903a81ebf90e95331386ec6f6ced0.nq.gz
│   ├── bb1d2dfb5386fc6dc512a9c0fb621ae191be7fdc.nq.gz
│   ├── c19998b32669575fd1e997edd42969e2f514d4d5.nq.gz
│   ├── c199a8a68e5111c80712be4f796bd8e8c4398155.nq.gz
│   ├── c868016b9b2fe3c12d1b2618dc24baf817c8db11.nq.gz
│   ├── c8a25191bb6cac30f5f53ad4fe5163534a04e048.nq.gz
│   ├── c99ad3f9c24294715e722372b17444c2a4016ff5.nq.gz
│   ├── cab682a4f15aae2290520f0641e2e592a832ea9e.nq.gz
│   ├── cb0ed5f53bdded47c6c533fa9e83952e159b5e8e.nq.gz
│   ├── cb2798347736894e89123b34a59691a305bb3f54.nq.gz
│   ├── cd628f5b05d583f12d3c6cacd1bb88d6f21fc974.nq.gz
│   ├── ceffc2eefb8f39e04150023cca0eb7ff40dfac0a.nq.gz
│   ├── cfc9b02f92b0be21155bfb450287a7db8a14a1df.nq.gz
│   ├── d3ebb20c6e081fb9deef72e68c5428cded7601f4.nq.gz
│   ├── d41b08b410585a2070ca1e97e2edfd3f1aeb5943.nq.gz
│   ├── d427ce0d311a75b22bbd4bdfed57ff64f27ae818.nq.gz
│   ├── d43534e7571bc7d22eb153b212d52c778e0e747b.nq.gz
│   ├── d57582de1ed3286b891ccc1ff4d350b79d0f18f2.nq.gz
│   ├── d6141f7861d93ab8d3f4a2639e0b53195783f69b.nq.gz
│   ├── d631deba898aa77999a49b36c07e045b59d72a5f.nq.gz
│   ├── d7f1697054b7b4f8cfe4f7795be05cddf86c79cd.nq.gz
│   ├── d928c3115e4fe6b313bfd057639aa783caeec8da.nq.gz
│   ├── dac8a2717e0162a64e7956853f5b5520ba08091f.nq.gz
│   ├── ddb86e9ade45f70d41fce42cda90dce65db2fb61.nq.gz
│   ├── df8c44cc2cc9a25c9260dc184584e95d3f5f3d2b.nq.gz
│   ├── e543f7a06f6f202f2b477592d5b2c35a7696bc94.nq.gz
│   ├── e59075bf1b1543bc00fd010df2e97886e7a69aba.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8abff87e0b165b655d43c085479bc27a8725728.nq.gz
│   ├── ec14290d849be5c30aeb7ee6bf16a3e4a8cac304.nq.gz
│   ├── ec42c52a243e8037911f26f51778fdb20b11e859.nq.gz
│   ├── ec65b212f2176b1145279dc79635444dddd4482b.nq.gz
│   ├── ee7a0ff4638b732ed3409bc23e826723d36d6312.nq.gz
│   ├── efd30a00961fd8415e78dd8f5a81029e1cc7983c.nq.gz
│   ├── f0bfc4b612a1b2fd0078b85cc1b210dae61ea476.nq.gz
│   ├── f101af4e45666f517d31163fb4b2d4e5ba3b0078.nq.gz
│   ├── f33e6d2816b7ec24fc4804bf0b3f8ceaed835dec.nq.gz
│   ├── f59a444dfe4f3037aa949be3f23bdda3ba82c734.nq.gz
│   ├── f77c03c797212e0319cb6e7c0bee1e5a8ed6f9bc.nq.gz
│   ├── fc232ecec54b047634ca0889f06ae29c42ea5b8e.nq.gz
│   ├── fcc8a48591270fcf83ce13356a550f37256d5e59.nq.gz
│   ├── fce544c8869682b5a4828ccc9e3f165e57d9c449.nq.gz
│   ├── fd651378fe3a664efa5b98679a0261c1262ae306.nq.gz
│   ├── fe11b48703a6a6ea3b9151d2d0b67a3ae5fc6eb8.nq.gz
│   └── fed537de4dd1707fdb11cf5a48c235b06159bf32.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 33bf0b0b921b9966bfeaedb9a9405018ef61e7ff.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 135 files
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

[django-commons/django-valkey](https://github.com/django-commons/django-valkey)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
