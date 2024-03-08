# ArchValheim

A minimal modpack for Arch Valheim players

To request more mods, ask kevr in IRC.

## Setup

1. Retrieve the latest `AppImage` at https://github.com/ebkr/r2modmanPlus/releases
2. `chmod +x /path/to/r2modman-X.X.XX.AppImage`
3. Run the `AppImage` and update r2modman if prompted. Any update may change the original AppImage version.
4. `ln -s /path/to/r2modman-X.X.XX.AppImage ~/.local/bin/r2modman`

Now, you can launch r2modman via ~/.local/bin/r2modman.

## Usage

1. Open `r2modman`
2. Select the *Game* tab, search for *Valheim*, select it, and choose *Steam*
3. Create a new profile
4. Browse for and install `ArchValheim` and/or `ArchValheimOptional`
5. Launch Valheim with *Start Modded* in the upper-left corner of r2modman
6. Log in to the server as per usual

NOTE: **DO NOT** follow update prompts in r2modman for outdated mods. The
`ArchValheim` modpack will maintain the correct versions for all mods we
use. Upstreams may update their mods, but we may be using outdated versions
purposefully.

## Required Mods

Required mods are maintained within the this modpack.

These mods are required by the client because all clients need to be
running them in order for them to be properly used at all.

## Optional Mods

Optional mods are maintained within the [ArchValheimOptional](https://valheim.thunderstore.io/package/Kevver/ArchValheimOptional) modpack, which depends on this modpack to function.
