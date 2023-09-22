In the latest version of Visual Studio Code, there are several new features and improvements:

- Focused view in window title: The `window.title` setting now has a `${focusedView}` variable that displays the name of the view in the title bar if a view is currently focused[^0^].
- Accessible View for inline completions: Inline completions, like those from the GitHub Copilot extension, can now be inspected in the Accessible View[^0^].
- Actions in the Accessible View: Screen reader users can go to next/previous, disable accessibility verbosity, and more for a given feature in the Accessible View[^0^].
- Diff Editor: The new diff editor is enabled by default, with improvements and bug fixes[^0^].
- Configure the cursor appearance when unfocused: The look of the cursor in the terminal when it is not focused can now be configured with `terminal.integrated.cursorStyleInactive`[^0^].
- New link formats: GNU-style link formats are now detected in terminals[^0^].
- Create workspaces from the Chat view: You can now use `/createWorkspace` to create workspaces from a natural language description in the stable build of the GitHub Copilot Chat extension[^0^].

Other notable improvements include:

- Terminal accessibility help: A command to provide important information for screen reader users[^2^].
- Improved multi-view resizing support: Resize multiple views at the same time by dragging the corners of the views[^2^].
- Redesigned inline suggestions toolbar: The toolbar is more compact and easier to use, with buttons to cycle through alternative suggestions and accept a suggestion fully or word by word[^2^].
- Terminal editor file drag and drop support: Drag and drop files to write them to the terminal instead of opening an editor[^2^].
- New shellscript grammar: VS Code now uses a new grammar from better-shell-syntax for shellscript syntax highlighting[^2^].
- JavaScript React language label is now JavaScript JSX: The JavaScript React language mode has been renamed to JavaScript JSX to reflect that JSX syntax is used by more than just React[^2^].

Additionally, VS Code is working on migrating its codebase to ESM (ECMAScript Modules) to improve performance and maintainability[^2^].

[^0^]: [Source 0](https://code.visualstudio.com/updates)
[^2^]: [Source 2](https://code.visualstudio.com/updates/v1_75)