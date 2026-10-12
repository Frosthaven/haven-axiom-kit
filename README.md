# Haven Axiom Kit

Run [Axiom](https://modrinth.com/mod/axiom), the creative world editor, in a copy of
**Create Ultimate Selection 2 12.1.0** for planning builds offline on a copy of the Haven world.

Axiom is a Fabric mod. This kit holds the bridge that runs Fabric mods on NeoForge:

| Mod | Version | License |
| --- | --- | --- |
| [Sinytra Connector](https://modrinth.com/mod/connector) | 2.0.0-beta.17+1.21.1 | MIT |
| [Forgified Fabric API](https://modrinth.com/mod/forgified-fabric-api) | 0.116.15+2.3.4+1.21.1 | Apache-2.0 |
| [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) | 1.14.2+kotlin.2.4.21 | Apache-2.0 |

Axiom itself is not in the kit: its license does not allow sharing it. Download it from Modrinth.

These versions run on the pack's own NeoForge (21.1.243). Newer Forgified Fabric API
versions need a newer NeoForge.

## Install

1. Download `haven-axiom-kit-1.0.zip` from [Releases](../../releases/latest) and unzip it.
2. Download **Axiom 6.1.3 for Minecraft 1.21.1** (Fabric) from
   [Modrinth](https://modrinth.com/mod/axiom/versions?g=1.21.1&l=fabric).
3. Make a copy of the pack, so your main profile stays as the server expects:
   - **CurseForge (Windows, macOS):** right-click the Create Ultimate Selection 2 profile
     → **Clone as...** → keep the Minecraft version → **Create**.
   - **Prism Launcher (Linux):** right-click the instance → **Copy** → name it, for example
     "Haven Planning".
4. Open the copy's `mods` folder:
   - **CurseForge:** right-click the clone → **Open Folder** → `mods`.
   - **Prism Launcher:** right-click the copy → **Folder** → `minecraft` → `mods`.
5. Put the three jars from the kit's `mods` folder and the Axiom jar in there.
6. Launch the copy. The first start takes longer while Connector prepares the Fabric mods.

To get the world, log in to the [Haven map](https://map.minecraft.thedragon.dev) and use
**Download world**.

## Use

- Axiom only works in creative. The Haven world download opens in creative with cheats on.
- **Right Shift** opens the editor. Hold **Left Alt** for the builder tools. Keys are
  under Options → Controls → Key Binds → Axiom.
- [Axiom documentation](https://axiomdocs.moulberry.com)

Play on Haven with your main profile, not with this copy. The server does not run Axiom, so the
editor is off there. To move a build to the server, save it with Create's **Schematic and Quill**
and print it with a **Schematicannon**; see the
[Haven Codex](https://claude.ai/artifact/QG2xPPxSAM2BQiovWVoGiF#planning).
