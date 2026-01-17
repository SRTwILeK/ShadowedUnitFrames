# Shadowed Unit Frames

A comprehensive unit frame addon for World of Warcraft: The Burning Crusade Anniversary Edition (2.5.5), providing highly customizable and feature-rich unit frames for all aspects of gameplay.

## Overview

Shadowed Unit Frames (SUF) is a powerful unit frame replacement addon that allows you to customize every aspect of your player, target, party, raid, and other unit frames. This version has been adapted for The Burning Crusade Anniversary Edition, maintaining full compatibility with the 2.5.5 client.

## Features

### Supported Unit Frames
- **Player & Pet** - Customizable player and pet frames
- **Target & Target of Target** - Multiple levels of target frames
- **Focus & Focus Target** - Focus frame support
- **Party & Party Pets** - Full party frame customization
- **Raid & Raid Pets** - Flexible raid frame layouts
- **Boss Frames** - Dedicated boss unit frames
- **Arena Frames** - Arena target frames with pets
- **Main Tank & Main Assist** - MT/MA frames with targets
- **Battleground Frames** - Battleground-specific unit frames

### Core Modules

#### Visual Elements
- **Health Bars** - Customizable health display with color options
- **Power Bars** - Mana, rage, energy, and other power types
- **Portrait** - 2D and 3D portrait options
- **Cast Bars** - Spell casting and channeling indicators
- **Auras** - Buff and debuff tracking with filtering
- **Aura Indicators** - Icon-based aura notifications

#### Class-Specific Features
- **Combo Points** - Rogue and Druid combo point display
- **Druid Mana** - Mana bar for shapeshifted Druids
- **Totems** - Shaman totem timers and tracking
- **Runes** - Death Knight rune display (if applicable)

#### Advanced Features
- **Tags System** - Powerful text customization with custom tags
- **Range Checking** - Automatic range-based opacity fading
- **Fader Module** - Conditional frame fading based on various conditions
- **Incoming Heals** - Prediction bars for incoming healing
- **Highlight** - Target highlighting and mouseover effects
- **Combat Text** - Integrated floating combat text
- **Indicators** - Customizable icon indicators for various states

### Configuration Options

#### Frame Customization
- **Positioning** - Drag and drop frame positioning with unlock command
- **Scaling** - Individual frame scaling options
- **Colors** - Customizable colors for health, power, class, and more
- **Layouts** - Multiple layout presets and custom layouts
- **Visibility** - Zone-based and condition-based visibility rules

#### Filtering System
- **Buff/Debuff Filters** - Whitelist and blacklist filtering
- **Zone Configuration** - Per-zone unit frame visibility
- **Priority System** - Custom aura priority and grouping

#### Text and Tags
- **Custom Tags** - Create your own text displays using Lua
- **Default Tags** - Extensive library of pre-made tags
- **Text Positioning** - Multiple text anchors per frame
- **Font Options** - Compatible with LibSharedMedia-3.0

## Installation

### Method 1: Manual Installation
1. Download the addon
2. Extract the contents to your WoW AddOns folder:
   ```
   World of Warcraft\_classic_\Interface\AddOns\
   ```
3. Ensure both folders are present:
   - `ShadowedUnitFrames`
   - `ShadowedUF_Options`
4. Restart WoW or reload your UI with `/reload`

### Method 2: Addon Manager
Install using your preferred WoW addon manager (CurseForge, WowUp, etc.)

## Configuration

### Accessing Options
Open the configuration panel using any of these methods:
- Type `/suf` in chat
- Navigate to Interface > AddOns > Shadowed Unit Frames
- Click the minimap icon (if enabled)

### Quick Start
1. **Unlock Frames**: Type `/suf unlock` to enable frame movement
2. **Position Frames**: Drag frames to desired locations
3. **Lock Frames**: Type `/suf lock` to lock positions
4. **Configure**: Open `/suf` to access detailed configuration options

### Common Commands
- `/suf` - Open configuration
- `/suf unlock` - Unlock frames for positioning
- `/suf lock` - Lock frames in place
- `/suf reset` - Reset configuration to defaults

## Technical Details

### Dependencies
- **Required**: None (fully standalone)
- **Optional**:
  - LibSharedMedia-3.0 - Additional fonts, textures, and sounds
  - AceGUI-3.0-SharedMediaWidgets - Enhanced media selection
  - LibSpellRange-1.0 - Improved range checking
  - Clique - Click-casting integration

### Embedded Libraries
- Ace3 (AceDB-3.0, AceConfig-3.0, AceGUI-3.0)
- LibStub
- CallbackHandler-1.0
- LibSharedMedia-3.0
- LibSpellRange-1.0
- LibClassicDurations - Accurate buff/debuff duration tracking
- LibClassicCasterino - Cast bar support for Classic

### Database
- Saved Variables: `ShadowedUFDB`
- Profile Support: Full profile management with copy, reset, and delete
- Database Revision: 61 (Classic Revision: 5)

### Localization Support
Fully localized in multiple languages:
- English (enUS)
- German (deDE)
- Spanish (esES, esMX)
- French (frFR)
- Korean (koKR)
- Portuguese (ptBR)
- Russian (ruRU)
- Chinese Simplified (zhCN)
- Chinese Traditional (zhTW)

## Compatibility

### Game Version
- **Interface**: 20505 (TBC Anniversary Edition / 2.5.5)
- **Version**: v4.3.4-classic

### Known Compatible Addons
- Clique - Click-casting integration
- OmniCC - Cooldown count support
- Most threat meters
- Most bag addons
- Most action bar addons

## Credits

### Original Author
- **Shadowed** - Original Shadowed Unit Frames for retail WoW

### Classic Adaptation
- **Nevcairiel** - Classic version adaptation (v4.3.4-classic)

### This Version
- Adapted for The Burning Crusade Anniversary Edition (2.5.5)

### Community
Special thanks to the WoW addon community and all contributors to the libraries used in this project.

## Links

- **Original Project**: [Shadowed Unit Frames](https://github.com/Shadowed/ShadowedUnitFrames)
- **Classic Fork**: [Nevcairiel's Classic Version](https://github.com/Nevcairiel/ShadowedUnitFrames/tree/v4.3.4-classic)
- **WoWAce**: https://www.wowace.com/addons/shadowed-unit-frames/
- **Curse Project ID**: 19268
- **WoWI ID**: 13494

## Support

### Reporting Issues
When reporting issues, please include:
1. Your game version (should be 2.5.5)
2. Addon version
3. Steps to reproduce the issue
4. Any error messages (enable Lua errors in Interface options)
5. List of other addons installed (conflicts may occur)

### Getting Help
1. Check the in-game configuration options - most questions are answered there
2. Review the tag documentation for custom text displays
3. Search existing issues for similar problems

## License

This addon is a fork and adaptation of the original Shadowed Unit Frames. Please refer to the original project for licensing information.

## Changelog

### TBC Anniversary Edition Version
- Updated for Interface 20505 (TBC Anniversary 2.5.5)
- Maintained compatibility with Classic API
- Integrated LibClassicDurations for accurate buff/debuff tracking
- Integrated LibClassicCasterino for cast bar functionality
- API compatibility layer for C_AddOns and other modern API changes
- Full TBC class support with appropriate modules

---

**Note**: This is a community-maintained version specifically for The Burning Crusade Anniversary Edition. For the most up-to-date retail version, please visit the official project links above.
