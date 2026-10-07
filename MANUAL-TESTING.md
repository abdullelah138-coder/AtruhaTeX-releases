# Build 4: install and check

This update was compiled and packaged without automated tests, app launch, or installation testing. Manual Windows acceptance is pending.

1. Save your documents. Open **Settings → About → Application updates → Check for updates**.
2. Choose **Download and install** and approve the installer. Alternatively, download the EXE linked in the README, close the app, and run it over the existing installation.
3. Reopen the app. The visible version remains **Pi 3.1 / 1.0.1**; the build number is identified by this download rather than shown in About. Check for updates again; after installing this release, it should report that you are current.

## Editor

- Type and delete Arabic and English within a mixed line containing `\textbf{...}`. Check that text ordering and syntax colors stay steady.
- Type until the line wraps; try punctuation, braces, Backspace and Undo. The active-line highlight should remain steady.
- Leave the caret near the top of a long file, click the PDF or another panel, scroll the source far down, then click a visible line once and type. The viewport and insertion should stay at the clicked position.
- Repeat at your normal display scaling, then save, close, reopen and compile the document.

## Writing features

- **Structure → Organize active file:** preview a section move or heading change, apply, then Undo. Cross-file moves are not included.
- **Local review beside version history:** add a comment/suggestion and export/reimport its review file.
- **Zotero library → Reading:** inspect synced notes/annotations and insert a quote with its citation and locator.
- **Insert → Manuscript Notation:** define a symbol and review its occurrences.
- **Insert → Scientific Clipboard:** preview a formatted-text or table conversion, insert and Undo.
- With the updated account server, use **Account → Projects → People** for reviewer roles, invitations and file-scoped editing, and the project discussion panel for chat and document comments. Installing the desktop update does not deploy that server.

If a problem occurs, report build number, display scaling, exact steps and whether a new document reproduces it. A brief recording helps diagnose momentary jumps.
