# Repolex Knowledge Graph of vcstools/rosinstall

RDF knowledge graph data for [vcstools/rosinstall](https://github.com/vcstools/rosinstall), parsed by [repolex](https://repolex.ai).

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
rlex download vcstools/rosinstall
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c33f88d7c93024491c8f8f062ebab3827b7f9ae8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c33f88d7c93024491c8f8f062ebab3827b7f9ae8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00271b91a3005d0c657dbed7edd6754510ac4722.nq.gz
│   ├── 0ccfb2c019ff4ea71281261e0756812b16cd91d7.nq.gz
│   ├── 0cd80ce87e016e1ee54c8b3e99c2878b577259b7.nq.gz
│   ├── 249d4e2fcdae430649726656e6dc5f11b61f67f2.nq.gz
│   ├── 25412b4e4499048a4aef5d0f403a532f995cc862.nq.gz
│   ├── 33912c2671f348365c568df4f6199c31d6d7c8a0.nq.gz
│   ├── 357ec4bd958cf89956045e207ec80fde01e97fa8.nq.gz
│   ├── 4052c104be6e21694395d15d667b49c90f970b16.nq.gz
│   ├── 48b89540bc988b43ef10be83dbd865dad9858cde.nq.gz
│   ├── 4b4c52451d5622ef698c3932692cba1ab0100737.nq.gz
│   ├── 510618f7be8c3faee37de46ffbc23cfb3bec609c.nq.gz
│   ├── 56fb885e50fa0ebb4f2a2e04fed7348d4173e682.nq.gz
│   ├── 58950bf3b408d5469ee8f7eb4108d835a57e081e.nq.gz
│   ├── 5b35860a26e9300a0d6fe34227aa3b57c3e2abb2.nq.gz
│   ├── 5f54eeb9922b05629b953dd2bafc0110f5a5c79b.nq.gz
│   ├── 5f7b4169bbd6ea7a9e9a6b795e3c070e8d4a74bc.nq.gz
│   ├── 681cf5b7a24c00db8436b3b6d5f4edb85e495fed.nq.gz
│   ├── 69d26c9dc650c7d749674f5626de2ef4421ff8f0.nq.gz
│   ├── 6d42e3574845b37157e22d457adfac8067056f25.nq.gz
│   ├── 6d4fb22d4389209982c94c5ec822d8066f2ecf33.nq.gz
│   ├── 6ebbeda1780881d53dcae04610570ef5e5b9b120.nq.gz
│   ├── 783b335f4d5abfdd2240e3008088450776d3b8aa.nq.gz
│   ├── 7da9ecefca13676c2dfcd0630c416ffcf422f1f1.nq.gz
│   ├── 7eb9dc7091b608aee9a549c69ce707bff782b0b8.nq.gz
│   ├── 845ed9de8657e1a9445f7ebebf44796feb8ef34f.nq.gz
│   ├── 889776fb7978839b78493edb73d5e8fd36c64282.nq.gz
│   ├── 8c2e1a297df1ebc429e64052a6035f525c08ef9c.nq.gz
│   ├── 8ee24ffdadf81171f0c0c96f55e889ecc8c15346.nq.gz
│   ├── 938b1f5d73644d397a20c4e681be3868fc7a3c17.nq.gz
│   ├── 963ca002abd24fcf23375cbd0bef28d46d40d995.nq.gz
│   ├── 989d3ea30f9bc9e532c868a80fd7edb30e928d10.nq.gz
│   ├── 9efa63aab4e8cf384f4bbb3601b65c9a47218976.nq.gz
│   ├── 9f54f36a23f07ccf1f269d611d55d0ab409574ad.nq.gz
│   ├── a5deede6223d86dca04ea6d9175c7143d6d6bdc6.nq.gz
│   ├── a6786964fedc62bda938926680a3c1375ba890e8.nq.gz
│   ├── a83c69d4e1cf7b4a688a378df99eb8b6956c4461.nq.gz
│   ├── a88024f35da1a932be6c89dc8c89dfa7e3bdafd2.nq.gz
│   ├── b27a0cff93cc7effb229efab0ec60559c8f42e41.nq.gz
│   ├── b60e9e00a7a809634594489121ba6f40dbc31439.nq.gz
│   ├── bc9ad64a3436bf306adf9038be9d369fd050970c.nq.gz
│   ├── c1849dbab219314e064f2019a2ea24004f67cb88.nq.gz
│   ├── c34c4376ad3adff086e9cde8ca63c48c3b526858.nq.gz
│   ├── d0ea8b7a960d2bd5e53155190ad81dceb253d5c8.nq.gz
│   ├── d1d51010262528b7cbdfdf082797f541370055a2.nq.gz
│   ├── d21d73abcacb58b9b0ff7157d13335d1fc7a70bf.nq.gz
│   ├── d3e902ed3cc4fcbfd2c04a734e9b00d274d52cad.nq.gz
│   ├── d67453f68a049de4941a69b6f8a44d8c0d619d6b.nq.gz
│   ├── d92bacd304648fa62c7b75cbb37afb8a09a68341.nq.gz
│   ├── dd0d8cc9e0081633248dab08657e434913d323b1.nq.gz
│   ├── df1da4ac09f6a3f8ccfc32717ad805132cf6b5bc.nq.gz
│   ├── e225993c7c2950636b64abae119650f646958290.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e93fe8a8fb508098bac95dac71ee1b2895af4e50.nq.gz
│   ├── ea1a726cfb3096bd9383ca76e7562a1b8160ee0b.nq.gz
│   ├── ecd956c9c7d182cd053e8d34c0c59e6de58ba664.nq.gz
│   ├── f29ca80bf8e9529dd73a00035494f2d3c287e7eb.nq.gz
│   ├── f9b5e3afb0c3f4b8162bb95bf0a02f7548420284.nq.gz
│   └── fef3900021ef73d93d651db7ce3cc8063aa6dc04.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c33f88d7c93024491c8f8f062ebab3827b7f9ae8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[vcstools/rosinstall](https://github.com/vcstools/rosinstall)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
