# BoJOS v5 — rc12c image

Latest release candidate. GitHub on this account hard-rejects git objects over 100 MB, so the ISO is
distributed as **release assets** (GitHub allows up to 2 GB each) instead of in the git tree.

ISO file: `bojos-v5-rc12c.iso` (3,116,105,728 bytes) — download both parts from the [v5-rc12c release](../releases/tag/v5-rc12c).

| Part | Size (bytes) |
|---|---|
| bojos-v5-rc12c.iso.part1 | 1,558,052,864 |
| bojos-v5-rc12c.iso.part2 | 1,558,052,864 |

## Reassemble

    # Linux / macOS
    cat bojos-v5-rc12c.iso.part1 bojos-v5-rc12c.iso.part2 > bojos-v5-rc12c.iso

    # Windows (cmd)
    copy /b bojos-v5-rc12c.iso.part1 + bojos-v5-rc12c.iso.part2 bojos-v5-rc12c.iso

Verify all three hashes against SHA256SUMS.txt.
