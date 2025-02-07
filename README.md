> [!IMPORTANT]
> The plugin is currently in Open Beta. Some features might still be refined, and feedback is invaluable in helping improve it before the final release. Thank you for being part of this journey!

# VariableScout

VariableScout is a powerful Figma plugin designed to streamline the management of variables and nodes within your projects. It provides an intuitive interface for filtering, visualizing, and organizing variables and nodes based on their types and attributes.

## Features

- Variable and Node Visualization: Easily view all variables and the nodes they are connected to within your Figma document.
- Filtering: Filter variables and nodes by type.
- Search Functionality: Quickly search for specific variables, nodes, or collections.
- Focused View: Simplify the variable value and node path, highlighting only the essential elements.
- Export Variables: Export variables in various formats (.JSON, .CSV).
- Selection Sync: Automatically updates to reflect the currently selected nodes on the canvas.
- Settings Customization: Tailor the plugin to your workflow with various settings like "Only selected nodes" and "Only unused variables".
- Shared Variables: Access variables in linked/shared libraries across your projects.
- Variable Swap: Directly modify variable connections for multiple filtered nodes simultaneously.
- Only Unused Variables: Show only variables that haven’t been used in the document.
- Export Variables: Export variables with customizable options.

## Installation

1. Install from Figma Community: Visit the [VariableScout Figma Plugin Page](https://www.figma.com/community/plugin/1440799497106254634/variablescout) and click "Install".
2. Run the Plugin: In your Figma file, go to `Plugins` → `VariableScout` to launch the plugin.

## Instructions

### Settings

| Setting | Description | How to Use | Example |
| :--- | :--- | :--- | :--- |
| Only selected Nodes | Displays data only for the selected elements. | Toggle this setting on to focus on currently selected elements. | If you select a button on your canvas, VariableScout will only show variables connected to that button. |
| Only Unused Variables | Displays only unused variables in the document. | Enable this setting to identify and clean up unused variables. | Helps in finding color variables that are defined but not applied to any elements. |
| Focused View | Highlights only essential elements by hiding variable values and node paths. | Turn on to reduce visual clutter for easier navigation. | Hides detailed node paths, showing a streamlined list of node labels. |
| Copy Full Token | Copies the full token name, including its group structure, to the clipboard. | When enabled, copying a variable will include its full path. | Instead of copying just `primary-color`, it copies `colors/brand/primary-color`. |
| Merge Collection Sections | Combines all variables and nodes into a single list, hiding separate collection and group sections. | Activate to view all cards in one continuous list. | Useful when you want a holistic view without the hierarchy of collections and groups. |
| Ignore hidden layers | Hides nodes that are not visible in the document. | Enable this setting to exclude hidden layers from the variable analysis. This helps you focus only on visible elements in your design. | If you have hidden a group of buttons for prototyping purposes, VariableScout will not display any variables related to those hidden buttons. |
| Remember Settings | Saves your current settings for future sessions. | Toggle on to keep your preferences every time you use VariableScout. | If you always work with "Focused View" enabled, this setting ensures it's active on startup. |

## Usage Guides

> [!IMPORTANT]
> Loading collections and mapping variables to nodes for the first time may take longer than subsequent loads. Future loading times will be faster.

> [!NOTE]
> Loading large collections (>2500 variables and/or 25000 Nodes) may take some time.

## Support & Feedback

We value your feedback and are here to help you get the most out of VariableScout.

- Figma Plugin Page: [VariableScout on Figma](https://www.figma.com/community/plugin/1440799497106254634/variablescout)
- Browse Issues: [View existing issues or feature requests](https://github.com/herrsascha/VariableScout-Docs/issues)
- Create New Issue: Found a bug or have a suggestion? [Create a new issue](https://github.com/herrsascha/VariableScout-Docs/issues/new)

---

Thank you for choosing VariableScout! If you find this plugin helpful, please consider leaving a review on the Figma Community page.
