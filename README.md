# Minecraft_Cobblemon_Guide
A guide to install Cobblemon 2.0 as much similar as PokeRayou season 2
<<<<<<< HEAD
=======

> Github limits the size of file to 100MB. Some files in the repo will be more than this limit so I splitted up these files into 100MB chunks.
> To join back these files into 1 you'll need to install [VSCode](https://code.visualstudio.com/) (but I personnally advise using [VSCodium](https://vscodium.com/)), install the "File & Folder Splitter Pro" plugin (it's free).
> You'll have to right click and "Join Split Files". I'll provide an exhaustive list of all splitted files bellow
> ![File and Folder Splitter Pro VSCode plugin](docs/Images/VSCode_File-Splitter)

## Splitted files

```yaml
mods/Abes-Hutts-Cobblemon-1.21.1-1.7.1-1.0.1.jar
```
Note: If you are, like me, using [PrismLauncher](https://prismlauncher.org/) then you'll need to disable the "Moonrise" mod (that's an optimization mod so no feature is disabled).

## Create the world

Change the game rules by turning `OFF` Mob spawning.
Change Difficulty to peacefull and activate Cheat Commands.

## Activate shiny alert

Open `config/cobblemon-spawn-alerts/main.json` and modify this line as following

```json
  "alertAllShinies": true,
```

## Create the /spawn

Install "FTB Essentials" (accept to install "FTB Library", requirement)

Move to the desired spawn location and do `/setworldspawn`
Then each `/spawn` will terminate in this location.

## Spawn a NPC

You need to start typing `/summon` and you'll see a list of all NPC available.

Example `/summon academy:nurse_npc` will summon an NPC that will heal your team over interaction.

## Add the gold economy

Install the "Numismatic Overhaul". This will integrate the bronze, silver, and gold coin currency.