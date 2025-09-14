# Workspace App Sets (or "Batch Launcher")

## 1. The Problem / User Story
As a GNOME user, I often have specific workflows that require opening the same set of applications every time I begin a task.

For example, when I start my "Development" workflow, I must manually find and launch:

- VSCode
- Postman
- Firefox (specifically for devtools)
- A Terminal
- And often a music app like Spotify.

This process is repetitive, creates friction, and adds mental overhead every single time I switch contexts or start my workday. The current App Grid requires me to launch each application individually.

## 2. The Proposed Solution: "App Sets"
I propose a new feature, "App Sets" or "Workspace Presets," that allows users to group multiple applications into a single, launchable entity.

This feature would allow a user to:

    Create a new "App Set" (e.g., "Dev Workflow," "Writing," "Creative").

    Add any number of installed applications to this set (e.g., the "Dev Workflow" set would contain the .desktop entries for VSCode, Postman, Firefox, GNOME Terminal, and Spotify).

    Launch the entire "Set" with a single click from the Activities Overview or a launcher icon.

Upon activation, the system would execute all launch commands for the apps within that set simultaneously, instantly setting up the user's required environment.

## 3. Key Use Cases
This feature has broad appeal beyond just developers:

    Developer Workflow: Launch VSCode, Postman, Firefox, Terminal, and Slack all at once.

    Creative Workflow: Launch GIMP, Inkscape, and Spotify.

    Office/Productivity: Launch Firefox, LibreOffice Writer, Geary (or another email client), and Calendar.

    Daily Start-Up: Any user's custom set of "morning apps."

## 4. Potential Implementation Ideas
While this is a feature concept, it could potentially be implemented in several ways to integrate smoothly with the GNOME desktop:

1. A simple standalone app: A small utility named "Workspace Launcher" or "App Sets" where users can define and launch these sets.
2. Integration into the App Grid: Perhaps allowing App Folders (groups) in the grid to have a "Launch All" context-menu action.
3. GNOME Control Center Panel: A new settings panel under "Multitasking" or "Applications" to define these sets, which then appear as a single, combined icon in the App Grid.
