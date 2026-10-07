# Curation policy

Help people learn to secure, test, evaluate, and govern AI agents. Learning value matters more than popularity.

Include agent-specific courses, labs, CTFs, documentation, research, books, videos, and podcasts. Broader AI and foundational material belongs here when its relevance is explained. Paid resources are welcome with accurate labels and no affiliate links. Vendor-authored education must teach something and identify its source.

Product homepages, broad directories, inaccessible pages, and unclear curricula belong in `data/research-inbox.json` until investigated. Do not describe credentials as accredited or industry-recognized without evidence. Certificates of completion and professional certifications differ; use the provider's terminology.

## Suggest a resource

Choose **Issues → New issue → Suggest a learning resource**. For a PR, edit `data/resources.json`; README is generated. Write an original description, select topics and format, and label scope, cost, availability, and inspection status. Disclose affiliation.

For local edits run `python3 -m unittest discover -s tests -v` and `python3 scripts/build.py`. Commit the regenerated README in the same PR. Validation rejects a stale README. If you edit only on GitHub, ask the maintainer to regenerate it on your PR branch before merging.

## Review automated proposals

1. Open each original link. Search matching does not establish quality.
2. Remove weak, duplicate, promotional, inaccessible, or out-of-scope entries from the proposed JSON.
3. Replace generic descriptions with useful summaries and correct classification and cost.
4. After inspecting the page, set `verification` to `Page inspected` and `checked_on` to today's date. Page inspection is not completing a course or testing a tool.
5. Inspect **Files changed**: discovery should change only the catalog and generated README.
6. Merge to accept all remaining additions; close without merging to decline the entire batch.

Hidden candidate IDs in PR descriptions let the bot remember open, merged, and rejected proposals. Preserve those comments. Removed entries from a partially accepted batch are also remembered. Reconsider an entry by adding it manually. `data/ignored.json` supports explicit exclusions as objects with `url` and `reason`.

Discovery uses simple keyword classification. It does not audit courses, run tools, watch videos, or validate credentials. Human review is the editorial gate.
