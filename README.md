# Yazi Files Configuration

## Overview

Yazi Files integrates Yazi, Helix, Zellij, and Nushell to create an efficient terminal file explorer experience.

### Key Features
- **Yazi**: A terminal file explorer that runs in a dedicated pane (20% width) within Zellij.
- **File Opening**: Files selected in Yazi open in Helix within new panes.
- **Layout**: The layout ensures optimal space usage, with Yazi occupying 20% of the terminal width and other panes stacking as needed.
- **Environment Management**: Nushell ensures that Helix operates with the correct environment variables.

## Usage Scenario

Open a new Zellij tab, where Yazi runs in a small pane. Navigate through files using Yazi and press `Enter` to open files in Helix, all within the same terminal tab, enhancing productivity and workflow.
