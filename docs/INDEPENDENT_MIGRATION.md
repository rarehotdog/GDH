# Independent personal repository

Completed on 2026-10-16 (Asia/Seoul). The canonical repository is
https://github.com/rarehotdog/GDH, repository ID `1422184264`, owned by rarehotdog.
GitHub reports `fork: false` and no parent repository. The expiring original
account is not required for access, builds or the personal runtime.

The old fork was retained without deletion at
https://github.com/rarehotdog/GDH-fork-archive, ID `1421780154`.
The paired AI Studio source is the independent rarehotdog/rehearsal-store,
ID `1422184847`, not its retained fork archive.

## Preserved material

All five original branches and full commit history, plus the preservation
branch, public inputs, source assets, original author/commit metadata and
license notices are retained. Original PRs #1-#3 are saved in
[the migration archive](migration-archive/README.md), with untruncated gzip
diff/patch files and complete public descriptions, comments and reviews.
GitHub-native PR numbers/check IDs are not recreated as new PRs.

Original PR Git refs are retained under these new archival tags:

- `archive/original-pr-1-head`
- `archive/original-pr-2-head`
- `archive/original-pr-2-merge`
- `archive/original-pr-3-head`

The synthetic merge tag is historical evidence, not approval to merge it into
main. There were no original tags, releases, Actions artifacts, Git LFS objects
or submodules to fetch separately. Source account URLs in old commits and
archived records remain attribution, not operational dependencies.

## Hosting and recovery

Vercel's thousand-stores-personal project is connected to repository ID
`1422184264` on main. https://thousand-stores-personal.vercel.app runs the
deterministic engine locally inside the function, without calling the old
Cloud Run service. Use [personal hosting](PERSONAL_HOSTING.md) for setup.
Execution caches are ephemeral; keys, credentials and old account permissions
are not copied. Optional new model calls require credentials you own.

For disaster recovery, clone the independent repository or use the complete
local mirror/bundles under Desktop/Develop/thousand-stores-preserved-20261016.
The migration verifier compares every reachable original Git object with a
fresh mirror cloned from this new independent repository.
