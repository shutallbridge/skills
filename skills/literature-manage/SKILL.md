---
name: literature-manage
description: Set up and maintain the user's literature library — choose or change the library folder, inspect the setup, delete or rename papers, validate frontmatter, find duplicates or missing conversions, and rebuild index.md. Use for any admin or cleanup task on the library, or when another literature skill reports the library isn't set up.
---

# Manage the library

<!-- Setup: get_library → if not initialized, confirm the folder (host path) with the user →
     init_library(path), which creates papers/, index.md and the .literature-library marker.
     If source is "env", explain LITERATURE_ROOT takes precedence over init_library.
     Existing non-empty folder: ask before adopting it. -->

<!-- Finding the library: if the path from get_library isn't reachable in this shell,
     search the folders shared with this session for the .literature-library marker
     (in Cowork, currently under /sessions/*/mnt — undocumented, may change). If no marker
     with a matching id is found, ask the user to share the library folder; don't fail. -->

<!-- Maintenance: delete, rename keys, validate against references/schema.md,
     duplicates, papers missing paper.md, rebuild index.md. Confirm before destructive changes. -->

- Frontmatter and keys: read [references/schema.md](references/schema.md)
