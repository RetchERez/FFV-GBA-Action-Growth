# Final Fantasy V Advance: Action Growth

By RetchERezzed. Inspired by demgelphoenix.

[Download v1.4](https://github.com/RetchERez/FFV-GBA-Action-Growth/raw/refs/heads/main/FFV_GBA_Action_Growth_v14.zip)

The ZIP contains exactly `FFV_GBA_Action_Growth_v14.ips` and `README.txt`. **No ROM or save is included.** Apply the IPS to a clean Final Fantasy V Advance USA ROM, not an already patched game. Installation hashes and save notes are in the README.

Action Growth replaces traditional character EXP leveling with permanent growth from actions in battle while keeping FFV's Job system. Version 1.4 fixes a demonstrated v1.3 battle-result write that could force Combat Rank 99 without earned growth. It changes exactly four bytes from public v1.3 and preserves its balance and Job AP curves.

Real headless mGBA 0.10.5 tests verified the actual first Job unlock for all four members, repeated Job changes, natural STR/AGI/STA/MAG growth retention, HP/MP formulas, native growth messages, repeated SRAM save/load, party departure/rejoin, random victory, L/R escape, independently learned/equipped `!Flee`, and Wing Raptor's story continuation. The original Rank 12–13 first-Job spike did not reproduce on current v1.3's award.

Coverage is 24/25 matrix cases passed with explicit scope limits. **Galuf versus Exdeath remains unverified because no validated pre-event save was available.** This is a targeted maintenance release, not full-game certification. Older-save checks have checkpoint-origin limits; v1.0's already erased growth cannot be recovered, and a Job rebuild can lower old inflated Rank/HP/MP. Back up existing saves.

Public ZIP SHA-256: `136fa46e379fc968416117a1ce465e3c214aab64561e96d5afa7d170d3706c6f`

IPS SHA-256: `98ddbb5e113503a51d3268950cdf7e50c3a7f67ac65574412bc8cca235c2a944`

[Issue #1 investigation](https://github.com/RetchERez/FFV-GBA-Action-Growth/issues/1)
