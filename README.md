# VariableScout

VariableScout is a powerful Figma plugin designed to streamline the management of variables and nodes within your projects. It provides an intuitive interface for filtering, visualizing, and organizing variables and nodes based on their types and attributes.

## Features

- Variable and Node Visualization: Easily view all variables and the nodes they are connected to within your Figma document.
- Filtering: Filter variables and nodes by type.
- Search Functionality: Quickly search for specific variables, nodes, or collections. Supports multiple search terms separated by semicolons.
- Export Variables: Export variables with customizable options and in various formats (.JSON, .CSV).
- Selection Sync: Automatically updates to reflect the currently selected nodes on the canvas.
- Settings Customization: Tailor the plugin to your workflow with various settings like "Only selected nodes" and "Only unused variables".
- Shared Variables: Access variables in linked/shared libraries across your projects.
- Extended Collection Support: Properly handles library collections that extend or override local variable collections.
- Variable Swap: Directly modify variable connections for multiple filtered nodes simultaneously. Collections are filtered by compatibility.
- Only Unused Variables: Show only variables that haven't been used in the document.
- Trace Variables to the Source: See exactly where a variable is created and how it connects across libraries and files.
- Quickly Reload Collections: After switching pages or updating designs, rescan collections for latest data.
- Limited Mode: Fast launch option for large files that scans only selected nodes, with easy switching to full mode when needed.

## Installation

1. From the community: Visit the [VariableScout Figma Plugin Page](https://www.figma.com/community/plugin/1440799497106254634/variablescout) and click "Open in...".
2. In your file: Go to `Plugins` → `VariableScout` to launch the plugin.

## Instructions

### Settings

| Setting | Description | How to Use | Example |
| :--- | :--- | :--- | :--- |
| Only Selected Nodes | Displays data only for the selected elements. | Toggle this setting on to focus on currently selected elements. | If you select a button on your canvas, VariableScout will only show variables connected to that button. |
| Only Unused Variables | Displays only unused variables in the document. | Enable this setting to identify and clean up unused variables. | Helps in finding color variables that are defined but not applied to any elements. |
| Focused View | Highlights only essential elements by hiding variable values and node paths. | Turn on to reduce visual clutter for easier navigation. | Hides detailed node paths, showing a streamlined list of node labels. |
| Copy Full Token | Copies the full token name, including its group structure, to the clipboard. | When enabled, copying a variable will include its full path. | Instead of copying just `primary-color`, it copies `colors/brand/primary-color`. |
| Merge Collection Sections | Combines all variables and nodes into a single list, hiding separate collection and group sections. | Activate to view all cards in one continuous list. | Useful when you want a holistic view without the hierarchy of collections and groups. |
| Ignore Hidden layers | Hides nodes that are not visible in the document. | Enable this setting to exclude hidden layers from the variable analysis. This helps you focus only on visible elements in your design. | If you have hidden a group of buttons for prototyping purposes, VariableScout will not display any variables related to those hidden buttons. |
| Show Variable Modes | Displays mode-specific usage of variables across nodes and modes. | Turn on to show a separate card for each mode a variable is used in. Turn off to display only the default mode. | If a variable has different values for light and dark modes, enabling this will show separate cards for each mode. |
| Hide Property Badges | Hides the property badges on node cards. | Turn on to remove badges that indicate where variables are applied. Useful for focusing on node names or paths without distraction. | Helps reduce visual noise when reviewing node structure or grouping. |
| Save Settings | Saves your current settings for future sessions. | Toggle on to keep your preferences every time you use VariableScout. | If you always work with "Focused View" enabled, this setting ensures it's active on startup. |

## Usage Guides

> [!IMPORTANT]
> Loading collections and mapping variables to nodes for the first time may take longer than subsequent loads. Future loading times will be faster.

## Quick Tips
- Export Current View: When in export mode, the plugin exports exactly what you see—including all active filters and searches.
- Check Variable Usage: Hover over the number indicator next to the Variables label to view the count of used and unused variables.
- Trace Variable Origin: Click the pointer icon on a variable card to open the variable trace overlay and see where it originates.
- Multi-Term Search: Search for multiple items at once by separating terms with semicolons (e.g., primary;secondary;accent).
- Search While Swapping: Use the search field in the swap overlay to quickly find the variable you want to swap to.
- Large File? Use Limited Mode: For files with many nodes, choose Limited Mode at launch to scan only selected nodes for faster startup. Switch to full mode anytime via the reload button.
- Refresh After Changes: After switching pages or making design updates, click the reload button to rescan collections for the latest data.
- Filter by Selection: Enable "Only selected nodes" to focus on variables used by your current canvas selection.
- Bulk Variable Swap: Select multiple nodes on the canvas, then use Variable Swap to update all their variable connections at once.
- Compatible Swaps Only: The swap overlay automatically filters collections to show only variables compatible with your current selection.

## Support & Feedback

We value your feedback and are here to help you get the most out of VariableScout.

- Figma Plugin Page: [VariableScout on Figma](https://www.figma.com/community/plugin/1440799497106254634/variablescout)
- Browse Issues: [View existing issues or feature requests](https://github.com/herrsascha/VariableScout-Docs/issues)
- Create New Issue: Found a bug or have a suggestion? [Create a new issue](https://github.com/herrsascha/VariableScout-Docs/issues/new)

---

Thank you for choosing VariableScout! If you find this plugin helpful, please consider leaving a review on the Figma Community page.
