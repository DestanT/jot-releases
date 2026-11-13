Jot 0.3.0 is the first version that keeps itself up to date. It also lets you arrange the tasks in a card, adds a New task button, and gives the dock its own Settings tab.

## New

- **Updates from inside Jot.** Jot is now signed and notarised by Apple, so it opens with a double-click. It checks for a new version once a day and shows you what's changed before installing. You can check any time with Jot › Check for updates…, and choose automatic checks and installs in Settings › General › Updates.
- **Arrange the tasks in a card.** Drag a task up or down in a dock card, or press ⌥↑ / ⌥↓. Your order stays at the top, and the rest follows the list's sort. ⌥↑ / ⌥↓ on a card's header moves the whole card.
- **New task button.** The list toolbar now has New task, which opens quick capture aimed at what's selected in the sidebar: a note, a folder or a vault. The list's other actions (Filter, View options, Add to dock) now sit above the list instead of over the inspector.
- **Dock settings.** Settings › Dock gathers "Keep the dock open when you click elsewhere", the dock's text size and width, and your spaces.
- **Open at login.** Turn it on in Settings › General › Startup.
- **Open a note from its title.** In a list grouped by note, double-click a note's title to open it in Obsidian.

## Improved

- Pinned cards move out of the dock's way while it's showing, and slide back when it hides. New pins line up along the edge of the screen.
- Dragging a card in the dock lifts it and makes room for it. Dragged out, the card follows the pointer, and its pin button now reads Pin to screen or Return to dock.
- The dock has its own text size. Change it with ⌘+ and ⌘− while you're using the dock, or with the slider in Settings › Dock. The + and − buttons are gone from the dock's top bar.
- Renaming a card ends when you click elsewhere, and keeps what you typed. An expanded card collapses again with Show fewer, and double-clicking a card's header minimises or expands it.
- Show or hide the Vaults and Tags sections from Settings › General.
- The dock's shadow follows its rounded corners, and the logo in the sidebar is smaller.

## Upgrading from 0.2.0

Download `Jot-0.3.0.zip`, unzip it and replace Jot in your Applications folder. Version 0.2.0 can't update itself, so this time is by hand; later versions arrive inside Jot. Because the app is now signed differently, macOS may ask once more for access to your notes folder and for notifications.

## Known gaps

- Recurring tasks: completing a 🔁 task does not create the next occurrence. Jot warns you when this happens.
- Plain child bullets under a task you move or delete stay behind.