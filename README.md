# Haven Axiom Kit

> **No longer needed for Haven players.** Haven now has an **Offline Editor (Axiom)** option: press Play, click
> **Optional mods...**, tick it. It installs Axiom and this bridge (newer versions) by itself and keeps them updated.
> See Creative Planning in the [Haven Codex](https://claude.ai/artifact/QG2xPPxSAM2BQiovWVoGiF#planning). This kit
> stays for reference.

Run [Axiom](https://modrinth.com/mod/axiom), the creative world editor, in a copy of the
**Haven** Prism instance, for planning builds offline on a copy of the Haven world.

Axiom is a Fabric mod. This kit holds the bridge that runs Fabric mods on NeoForge:

| Mod | Version | License |
| --- | --- | --- |
| [Sinytra Connector](https://modrinth.com/mod/connector) | 2.0.0-beta.17+1.21.1 | MIT |
| [Forgified Fabric API](https://modrinth.com/mod/forgified-fabric-api) | 0.116.15+2.3.4+1.21.1 | Apache-2.0 |
| [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) | 1.14.2+kotlin.2.4.21 | Apache-2.0 |

Axiom itself is not in the kit: its license does not allow sharing it. Download it from Modrinth.

These versions run on the pack's own NeoForge (21.1.243). Newer Forgified Fabric API
versions need a newer NeoForge. Tested 2026-10-15 with Haven 12.1.0-haven.39 (Sodium 0.8.13): Axiom 6.1.3 loads
and starts.

## Install

1. Download `haven-axiom-kit-1.0.zip` from [Releases](../../releases/latest) and unzip it.
2. Download **Axiom 6.1.3 for Minecraft 1.21.1** (Fabric) from
   [Modrinth](https://modrinth.com/mod/axiom/versions?g=1.21.1&l=fabric).
3. In Prism, right-click the Haven instance → **Copy** → name it, for example "Haven Planning".
   Your main instance stays as the server expects.
4. Right-click the copy → **Folder** → `minecraft` → `mods`.
5. Put the three jars from the kit's `mods` folder and the Axiom jar in there.
6. Launch the copy. The first start takes longer while Connector prepares the Fabric mods.
   The copy keeps updating with the pack; the kit jars and Axiom stay in its `mods` folder.

To get the world, log in to the [Haven map](https://map.minecraft.thedragon.dev), use
**Download world**, and unzip it into the copy's `minecraft/saves` folder.

## Use

- Axiom only works in creative. The Haven world download opens in creative with cheats on.
- **Right Shift** opens the editor. Hold **Left Alt** for the builder tools. Keys are
  under Options → Controls → Key Binds → Axiom.
- [Axiom documentation](https://axiomdocs.moulberry.com)

Play on Haven with your main Haven instance, not with this copy. The server does not run Axiom, so the
editor is off there. To move a build to the server, save it with Create's **Schematic and Quill**
and print it with a **Schematicannon**; see the
[Haven Codex](https://claude.ai/artifact/QG2xPPxSAM2BQiovWVoGiF#planning).
