# Pf2e Action list tray add-on for Foundry VTT
This isa fork of the original foundry action pack but designed to support the PF2e system, because I liked using the original in 5e.

Adds a toggleable panel containing all the activatable items, abilities and spells of the currently selected actor. The panel
slides out from the left side of the screen.

## Goal

The idea of this module is to allow quick access to all the activatable items on the character sheet. This will in most cases remove
the need to have the character sheet open all the time. The list is also intended to provide a quick overview of everything, not requiring
flipping tabs on the sheet itself.


## Hot keys

- Hot key for toggling the tray (default: E). This will temporarily hide the tray if in When token selected mode or in Automatic mode as the GM, or persistently toggle if in Toggle mode or Automatic as a player
- Hot key for accessing skills (default: K). This will open the panel and reveal skills/scroll to the skill list if the panel is not open, toggle the skill list open/closed if the panel is open and skills are collapsible or simply scroll the panel to show the skill list if the skill list is at the bottom.

## Settings

- Selectable tray display modes
    - Toggle: Explicitly open and close the tray by clicking the control icon or pressing the hot key
    - When token selected: Automatically open the tray whenever a token is selected, otherwise hide it
    - Automatic: "Toggle" for players, "When token selected" for DMs
- Three size options for the item icons: Small, Medium, Large
- Three sizes for the overall panel width
- Select the skill list location
    - Skill list at the top of the tray is collapsible. This takes up less screen real estate and is easy to discover, but requires a click to open
    - Skills are listed at the bottom of the panel. This way skills are not quite as easy to find, but can be accessed simply by scrolling and don't require clicking.
- Sort items alphabetically (default is to sort the same as the character sheet)
- Show cantrips always (default assumption is for active cantrips to be "Always Prepared")
- Hide or show the tray activation icon (left pointing finger) in the token controls
- Option to hide abilities with a set number of uses (e.g. per rest) from the list when their uses run out
