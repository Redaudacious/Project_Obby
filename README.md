# Roblox Obby Project

A Roblox project using modern development tools like Rojo, Wally, and Rokit.

## Prerequisites

### VS Code Extensions
- Luau Language Server by JohnnyMorganz
- Rojo - Roblox Studio Sync by evaera
- Selene by Kampfkarren (recommended)
- StyLua by JohnnyMorganz (recommended)

### Required Tools
- Install Rokit: https://github.com/rojo-rbx/rokit

## First-Time Setup

Run these commands in your project folder:

rokit init
rokit add rojo
rojo init
rokit add wally
rokit add wally-package-types
wally init
wally install
wally-package-types -s sourcemap.json Packages/

## Development

### Build the place file:
rojo build -o "Test.rbxlx"

### Sync with Roblox Studio:
1. Open Test.rbxlx in Roblox Studio
2. Run: rojo serve

### Install dependencies (when you pull the project):
wally install

## Key Dependencies & Documentation

- Knit (game framework) - https://sleitnick.github.io/Knit/docs/intro/
- Janitor (cleanup utility) - https://howmanysmall.github.io/Janitor/
- roblox-lua-promise (Promise library) - https://eryn.io/roblox-lua-promise/
- Cmdr (command system) - https://github.com/evaera/Cmdr?tab=readme-ov-file
- General Roblox developer docs: https://create.roblox.com/docs

## Resources
- Rojo docs: https://rojo.space/docs
- Wally: https://wally.run/
- Rokit: https://github.com/rojo-rbx/rokit