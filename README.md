# Fashion Sense Outfit Preview

Preview your saved Fashion Sense outfits before equipping them, making it easier to browse and choose the perfect look.

[![Nexus Mods](https://img.shields.io/badge/Nexus%20Mods-Fashion%20Sense%20Outfit%20Preview-orange)](https://www.nexusmods.com/stardewvalley/mods/45911)
[![Version](https://img.shields.io/badge/version-1.0.4-blue)](https://www.nexusmods.com/stardewvalley/mods/45911)

## About this mod

Fashion Sense Outfit Preview adds a small preview window and a button for an expanded preview window to the saved outfits menu from Fashion Sense, allowing you to see how an outfit looks before equipping it.

I originally made this mod for personal use because I had a lot of saved outfits and kept getting lost while trying to find a specific one. Since Fashion Sense shows outfit names but does not provide a visual preview in the saved outfits list, I wanted a simple way to check the look first instead of equipping outfits blindly.

After making it work, I thought it might be useful for other players too, so I decided to share it.

## Installation Instructions

1. Install [SMAPI](https://smapi.io/).
2. Install [Fashion Sense](https://www.nexusmods.com/stardewvalley/mods/7300).
3. Download this mod.
4. Extract the folder into your Stardew Valley `Mods` folder.
5. Launch the game through SMAPI.

## How to Use

- Open the saved outfits menu in Fashion Sense.
- Click the **Expand** button to open the full outfit browser.
- Browse your outfits in a larger interface with a live preview of your farmer on the right side.
- You can also hold **CTRL** and left-click an outfit for a quick preview without opening the expanded menu.

> **Note:** The configured preview shortcut will always be used together with the left mouse button.

Designed to make navigating large Fashion Sense clothing collections easier, especially for players with hundreds of saved looks. (like me LOL)

## Main Features

- Expanded outfit browser with a live character preview before equipping.
- Search bar to filter outfits by name.
- Custom outfit categories — create and delete your own groups (e.g. Summer, Winter, Festival) to keep your outfits organized.
- Outfit tags and color tags — label outfits with your own tags (e.g. Fun, Beauty, Pink, Blue) for quick filtering.
- Advanced filter panel — combine category, tags, and color tags to narrow down your outfit list exactly the way you want.
- Quick preview still available via CTRL + left-click for a faster look without opening the full browser.
- You can rename saved outfits by right-clicking on them.
- Save or delete a saved outfit.

## Requirements

- [SMAPI](https://smapi.io/)
- [Fashion Sense](https://www.nexusmods.com/stardewvalley/mods/7300)
- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) (optional)

## Project Structure

```
Fashion_Sense_Outfit_Preview/
├── ModEntry.cs                      # Mod entry point
├── manifest.json
├── i18n/
│   ├── default.json
│   └── pt.json
├── UI/
│   ├── ExpandedOutfitsMenu.cs       # Main expanded outfit browser
│   ├── AdvancedFilterPanel.cs       # Advanced filter panel
│   └── OutfitPreviewRenderer.cs     # Farmer preview rendering
├── Managers/
│   ├── CategoryManager.cs
│   ├── TagManager.cs
│   └── GlobalOrganizationManager.cs
├── Config/
│   └── ModConfig.cs
├── Integrations/
│   └── IGenericModConfigMenuApi.cs
└── Localization/
    └── I18n.cs
```

## Changelog

### Version 1.0.4
- Expanded menu hotkey — added a configurable hotkey to open the expanded browser from the default Fashion Sense saved outfit menu.
- Added:
  - Save current style;
  - Rename outfits;
  - Delete outfits;
- Navigation polish — closing the expanded browser now returns to the Fashion Sense hand mirror menu.

### Version 1.0.3
- Outfit tags — create custom tags (e.g. Fun, Beauty, Scary) and assign them to any outfit from the "Create" menu, then filter by them from the Advanced panel.
- Color tags — tag outfits by color (e.g. Pink, Blue, Yellow) for quick filtering by palette.
- Advanced filter panel — combine category, tags, and color tags at once (an outfit must match all selected filters to appear).
- "Open expanded view by default" option — added to Generic Mod Config Menu, so the expanded browser can open automatically instead of the Fashion Sense outfit saved menu.
- Improved typing — search and naming fields now support accents, ç, uppercase letters.
- Various UI polish — repositioned buttons, clearer category/tag management.

### Version 1.0.2
- Added an expanded outfit browser — click the new "Expand" button in Fashion Sense's outfit menu to open a larger browsable interface with a live preview of your farmer.
- Outfit categories — create or delete custom categories (e.g. Summer, Winter, Work) to keep your outfits organized. Categories are saved per save file.
- Search bar — filter your outfits by name.
- Live character preview — see your farmer wearing each outfit before equipping it.

### Version 1.0.1
- Added option to modify the shortcut key for the preview (GMCM).

## Credits and Permissions

- **Other user's assets:** This author has not specified whether they have used assets from other authors or not.
- **Upload permission:** You are not allowed to upload this file to other sites under any circumstances.
- **Modification permission:** You must get permission from me before you are allowed to modify my files to improve it.
- **Conversion permission:** You are not allowed to convert this file to work on other games under any circumstances.
- **Asset use permission:** You must get permission from me before you are allowed to use any of the assets in this file.
- **Asset use permission in mods/files that are being sold:** You are not allowed to use assets from this file in any mods/files that are being sold, for money, on Steam Workshop or other platforms.
- **Asset use permission in mods/files that earn donation points:** You are allowed to earn Donation Points for your mods if they use my assets.

## Links

- [Nexus Mods page](https://www.nexusmods.com/stardewvalley/mods/45911)
