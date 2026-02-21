# HLiquity repository final-state plan

This repository was used to add the HLiquity adapter to DefiLlama.

## Reference
- Adapter file: `projects/hliquity/index.js`
- Protocol page: https://defillama.com/protocol/hliquity

## Super-minimal final state (public)
1. Keep one primary branch only (`main` or `work`).
2. Delete stale branches.
3. Keep this single document as project context.
4. Archive the repository when active development is finished.

## Optional maintenance commands
```bash
# list branches
git branch -a

# delete old local branches
git branch -d <branch>

# delete old remote branches
git push origin --delete <branch>
```
