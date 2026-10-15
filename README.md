# Repolex Knowledge Graph of jupyterhub/kubespawner

RDF knowledge graph data for [jupyterhub/kubespawner](https://github.com/jupyterhub/kubespawner), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/kubespawner
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47ce269d515b7b509cb5ebe45d69ebe79d9dd6c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47ce269d515b7b509cb5ebe45d69ebe79d9dd6c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 026ad7cbf176a2c0978860450a44ae47d223f8a9.nq.gz
│   ├── 0319b1f5bb0c861bbf77ebea37adb1c3ecb5e93a.nq.gz
│   ├── 05de5fa5f17cd3ed8d0c22614f86b9cc37700848.nq.gz
│   ├── 06c398b84eb31f3bc48893e8ea8df1ff1ff2887c.nq.gz
│   ├── 08526cc6241653468558cbad129749b19c991ccf.nq.gz
│   ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
│   ├── 0dd865e834d850a4f4c08bb505f4b2072e3e07bf.nq.gz
│   ├── 12849a4f839b2ff38ed842596c678422ab726a21.nq.gz
│   ├── 14738a1abbea8213cb50789d4aac6c2596f88044.nq.gz
│   ├── 157cce0944ec471159ea427d7a7755382ebeeafb.nq.gz
│   ├── 1a6939a4b8fa395512e9ea3caf45a9d1c8f925d6.nq.gz
│   ├── 2249fd795ee09a4e429fd48bf60bf3c0b95eb62f.nq.gz
│   ├── 22fd7fc7d75eb959cdd08bea3e48cf72d233e24b.nq.gz
│   ├── 2d28dd93e0605f08d9f1cc79e041ba9852fb0667.nq.gz
│   ├── 3094d2b2d3c7096fa1a3bc208c3d41142d5267fd.nq.gz
│   ├── 330d998b7081dbdec6b79f11391b5649f5ecc6b9.nq.gz
│   ├── 352d469a6d8893722734a738fd68b830b6c9fdba.nq.gz
│   ├── 38471d74c1c1b1b05248db7d6ebafcdba01a7a0c.nq.gz
│   ├── 3a1abc2087165face704c752fbe1d412af335aba.nq.gz
│   ├── 436efc9ba16d0abc2b23f2e58d140ae2a0860250.nq.gz
│   ├── 44291150434b1cfca13b81c3c254e98778d0a88d.nq.gz
│   ├── 50bf4f917b2204d1438c200bd58f8dce399bd984.nq.gz
│   ├── 55828356c9358874a434592c1942bbf5ea980170.nq.gz
│   ├── 5e19778b531d71ebb8d33c831c6c831691147d89.nq.gz
│   ├── 666d8da346343f3fae5957566c656ccd73ee9b59.nq.gz
│   ├── 71bd06fd95011409846d12dc4a160d54c02f3a40.nq.gz
│   ├── 71dcccfacfbfcda735c859846b0517a514edfb15.nq.gz
│   ├── 73a10e0921d5ab8964e2ce48b25075b325625f69.nq.gz
│   ├── 73ab091848ebeb5ae9ec1aefa4e8c48dc54f24cf.nq.gz
│   ├── 745994730bd02a762411db96cd16276ce7f827b1.nq.gz
│   ├── 76674bc92eefd2e0cfdf27ae0e4e2627bbaf006f.nq.gz
│   ├── 7a23f0b913d0ce184f3d99a16567062f9750197f.nq.gz
│   ├── 7cc62a00133dd3e8d0ac0abb41b3513d92dba486.nq.gz
│   ├── 7d65e4445e6c1757a2fa7aa9a1aaae340eea8ac0.nq.gz
│   ├── 821d7ce24fbb68f263fe1072405a24ec258fbdef.nq.gz
│   ├── 8859c7666d0848738a3132bcaa74b6d00314a672.nq.gz
│   ├── 8b9a0d532217b33a694887d5eb846962193f27b3.nq.gz
│   ├── 8ebf2ff1d216915bf785a1aa5483b86fc27e0934.nq.gz
│   ├── 90bb2561631a47fff05a3b54417244eef3c657c9.nq.gz
│   ├── 92e6efcddc310fef4a5ca5d03c16609a87de6c18.nq.gz
│   ├── 9443a4759f084b1fd6b0564340bd319b04404318.nq.gz
│   ├── 95d9c6dd2b8ad88cf6828ee82f5caa82ae155b32.nq.gz
│   ├── 9e91f3865bbd3910ec6a63b91d5e7fa9afc6bccf.nq.gz
│   ├── 9e952747cf1874ee46d122d69113add1f3f29783.nq.gz
│   ├── a446de63621cd1d8580c1f4d85fb7ef952ca67c3.nq.gz
│   ├── a6677f96d3ad72c97938e01c7259b517974fac64.nq.gz
│   ├── a6fa0cb867f1d42a08188eac5ec459484b7a2c18.nq.gz
│   ├── ab75121aa2b7b834004575c091b5139fd83c8099.nq.gz
│   ├── ab895abbac2dcff598c4fa79b8e776ccd43d6291.nq.gz
│   ├── b37872960b0b1c9d5b0ee747b025f6f064aadbac.nq.gz
│   ├── b8aec21b3e837ce1ff7ba476afd3c709dd9a8682.nq.gz
│   ├── bf1e9a7769823b936cdb06ac9c45e89236ccf0d5.nq.gz
│   ├── c1a96d05b081a4c39b239932dd488d6091d416d8.nq.gz
│   ├── c899ccd5a7f71d95f6610a2b750bfe5ae342b246.nq.gz
│   ├── cc1acff091f8a7509f6844822b8f828421678857.nq.gz
│   ├── d157720c8762cb64328795afc4fd16ff5c3c9a96.nq.gz
│   ├── d78cb3a417497b48389f705b0b11dfb6b364b6a5.nq.gz
│   ├── dfcb71a54abce9e0675f16f86efa47b8500cf6b7.nq.gz
│   ├── e16803ebf7555c31558c8295f3ee40a52988dffa.nq.gz
│   ├── e2598d886f86514ea9394ab02755c25a0c00e626.nq.gz
│   ├── e2b3c0fabf9460ff81d1ca8744354c9d0734b266.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e779ee2fe5f7a16b1b9f3d917a23485ab6aded03.nq.gz
│   ├── f87dba656ce6970006b33bf7884c926bf066aa7e.nq.gz
│   ├── fb19588b5f4a03c43005ee484e28ef1aef4abbfb.nq.gz
│   └── ffa1157303888a27ca9983dcad2ec54710fa6ea3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 47ce269d515b7b509cb5ebe45d69ebe79d9dd6c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[jupyterhub/kubespawner](https://github.com/jupyterhub/kubespawner)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
