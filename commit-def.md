### Comparing Commit Definitions

- **Snapshot View**: A commit is like a snapshot — it captures the repo exactly as it looks at that point in time.
- **Implementation View**: A commit is stored as a file in .git with pointers to trees (file structure) and blobs (file contents).

**Difference**: One view is high-level (like a picture), the other is low-level (how Git actually stores it).
**Why Both Help**: Knowing both makes it easier to debug and understand Git when things go wrong.
