# Warhammer: The End Times — Project Instructions

The user moved development materials out of the public mod on November 13, 2026.
On Jeff's workspace, read and follow:

`/Users/jeffgomez/Desktop/Codex/Hearts of Gromril Dev Stuff/AGENTS.md`

Keep development notes, tools, source artwork, dependencies, reports and backups
in that local development folder. The mod's `Dev Stuff` folder retains only
`To Do.md`; do not edit that document unless explicitly requested. Do not restore
the old development tree inside this repository or create a `Dev Notes` folder.

The two authorized write locations are this `warhammer-end-times` folder and
the local `Hearts of Gromril Dev Stuff` folder above. The EU4 Warhammer mod and
the vanilla HOI4 installation remain read-only references; never modify either.

Development scripts use `workspace.json` and `conversion/workspace_paths.py`
in the local development folder. Legacy `Dev Stuff/...` manifest paths are
resolved there; do not use symlinks to put private development files in GitHub.

Maintain the root `CREDITS.md` whenever adding or replacing credited assets.
Preserve creator/source links and documented stand-ins in the local development
archive. Its `conversion/build_credits.py` regenerates public credits without
links to files that are absent from the repository. Keep the portable
`warhammer-end-times.mod` launcher file and the installation guide at the root.
