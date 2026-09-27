# Hi, I build AI memory infrastructure

I'm working on [**MemTether**](https://github.com/MemTether/MemTether) - a cross-client AI memory hub where heterogeneous AI agents share the same physical SQLite database via file-level pointers.

**No server. No sync. Zero API cost.**

## What is MemTether?

Multiple AI clients (Codex, WorkBuddy, OpenClaw, ZCode, etc.) all point to the same memory.db file — so when you switch from one client to another, your memory comes with you.

### Key features
- **File-level pointers** (junction/symlink) — not sync, not copies
- **Dual-timeline governance** — business time + recorded time, supersession version chains
- **Hybrid retrieval** — vector (bge-m3) + FTS5 BM25 + keyword + literal, RRF fusion + cross-encoder reranking
- **Conflict detection** — automatic detection + human review, not blind overwrite
- **Memory Exchange** — governance semantics travel with memory across systems (5 adapters)
- **Zero cost** — 100% local, offline capable, zero API fees

### Quick start
\\ash
pip install memtether
\
## Links
- **GitHub**: [MemTether/MemTether](https://github.com/MemTether/MemTether)
- **PyPI**: [memtether](https://pypi.org/project/memtether/)
- **License**: Apache-2.0
