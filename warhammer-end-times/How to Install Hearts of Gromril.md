# How to Install Hearts of Gromril

Follow these steps to install the beta for **Hearts of Iron IV**. You do not need GitHub Desktop, coding tools, EU4, or the original EU4 mod.

The mod currently appears in the HOI4 launcher as **Warhammer: The End Times**. Its installation folder must be named `warhammer-end-times`, even though this guide is titled Hearts of Gromril.

## Before you begin

- Install Hearts of Iron IV and open its launcher at least once.
- Use the game version and DLC setup specified in the beta announcement.
- Close the game and launcher before installing or updating the mod.

## 1. Download the mod

On this GitHub repository's main page, click the green **Code** button, then **Download ZIP**.

## 2. Extract the download

On Windows, right-click the ZIP and choose **Extract All**. On Mac, double-click the ZIP.

Find the extracted folder containing `descriptor.mod` and the folders `common`, `gfx`, `history`, and `map`. Rename that folder exactly:

```text
warhammer-end-times
```

These files and folders must be directly inside `warhammer-end-times`, not inside another nested copy of the folder.

## 3. Put the folder in HOI4's mod folder

On Windows or Mac, open your **Documents** folder and go to:

```text
Paradox Interactive/Hearts of Iron IV/mod
```

Create the `mod` folder if it does not exist. On Windows, your Documents folder may be inside OneDrive. Use the HOI4 folder containing your saves and settings, not the game installation folder in Steam.

Move the extracted `warhammer-end-times` folder into this `mod` folder.

## 4. Copy the launcher file

Open the installed `warhammer-end-times` folder.

Copy the file named `warhammer-end-times.mod` into the outer `mod` folder, beside the `warhammer-end-times` folder. Leave the original file inside the downloaded mod folder.

## 5. Check the folder layout

The supplied launcher file already contains the correct location:

```text
path="mod/warhammer-end-times"
```

You do not need to edit it. Its name must remain `warhammer-end-times.mod`, without an extra `.txt` extension. On Windows, turn on **File name extensions** in File Explorer if you need to check.

Your folder layout should now look like this:

```text
Documents/
└── Paradox Interactive/
    └── Hearts of Iron IV/
        └── mod/
            ├── warhammer-end-times.mod
            └── warhammer-end-times/
                ├── descriptor.mod
                ├── warhammer-end-times.mod
                ├── common/
                ├── gfx/
                ├── history/
                └── map/
```

Keep `descriptor.mod` inside the mod folder. It is separate from the launcher file you just copied and edited.

## 6. Enable the mod

1. Open the HOI4 launcher.
2. Go to **Playsets** and create a playset called **Hearts of Gromril Beta**.
3. Add **Warhammer: The End Times** to that playset and enable it. You may need to look under **All installed mods** first.
4. Keep other mods disabled while testing.
5. Select this playset on the launcher's main screen, then click **Play**.

## 7. Start a new campaign

Start a new game beginning in **2519**. Do not load a vanilla HOI4 save.

Use a fresh campaign for each beta update unless the update specifically says older saves are compatible.

## Updating the beta

1. Close HOI4 and its launcher.
2. Remove only the old `warhammer-end-times` folder and the matching outer `warhammer-end-times.mod` file. Keep your saves and other mods.
3. Download the new version and repeat the installation steps above.

Replace the old installation completely rather than copying new files over it, so removed files from an earlier beta do not remain active.

## Troubleshooting

- **The mod does not appear:** close and reopen the launcher. Check the folder layout above and make sure the copied launcher file ends in `.mod`, not `.mod.txt`.
- **The launcher says the mod is missing:** check that the folder is named exactly `warhammer-end-times` and that the copied launcher file contains `path="mod/warhammer-end-times"`.
- **The normal HOI4 map appears:** check that the correct playset is selected and that **Warhammer: The End Times** is enabled.
- **There is a game-version warning:** compare your HOI4 version with the beta announcement's supported version.
- **The game crashes or assets are missing:** try a fresh download with other mods disabled. If the problem continues, report it. The download may need fixing by the mod author.

## Reporting bugs

Use this repository's **Issues** tab, if available, or the feedback channel named in the beta announcement. Include:

- Your country and the in-game date.
- The beta version or the date you downloaded it.
- Your HOI4 version, operating system, and enabled DLC.
- What happened and what you were doing immediately beforehand.
- Whether the problem happens again after reloading.
- A screenshot and, when possible, a save from just before the problem.
