# OpenedFilesView - See Which Process Has a File Open

## At a Glance

A folder that "is in use" is not a mystery if you can read the process name and the path. OpenedFilesView shows opened files and the process that has them. You find the path you care about, close that application, and try the move again. System processes will appear. They are not targets. A file held by Explorer is often a preview pane or a working directory you can leave by navigating elsewhere.

- Path and process in one row
- A refresh after you close the app
- No need to reboot as the first idea
- Handles closed only when you understand the process
- No record of files that were opened yesterday

Use it on your own PC while you are unlocking a file you need. It is not a way to watch another person's documents on a machine you do not administer.

## What You Do with a Row

| Process | Action |
|---|---|
| The app you can see | Close the document or the app |
| Explorer | Leave the folder, or close the preview |
| Search indexer or backup | Wait, or pause that feature if it is yours |
| A random temp executable | Note the path and do not kill it blindly |
| System | Leave it alone |

1. Reproduce the "file in use" message.
2. Refresh OpenedFilesView and find the path.
3. Close that program the normal way.
4. Refresh. The row should be gone.
5. Retry the rename or the delete.

![OpenedFilesView showing a path and the process that holds it](https://www.rarst.net/images/LookupallfilesinusewithOpenedFilesView_13931/openedfilesview_interface.png)

## Who It Is For

Anyone stuck on a locked file on a PC they are allowed to use. A poor fit for a crash dump, a driver store, or a network of other computers. A poor fit for closing handles in lsass or other system processes because a guide said handles are optional. They are not optional there.

[![Open OpenedFilesView](https://img.shields.io/badge/Open-OpenedFilesView-1f6feb?style=flat-square&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/OpenedFilesView)

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows the build supports |
| Rights | Administrator for a fuller list |
| Timing | The file must be open now |
| Scope | This PC |

## Fixes

The file is not listed. It was locked for a moment and already released, or a different path is in the error.
The process returns immediately. Something relaunches it. That parent is the real stop.
You closed a handle and the app crashed. That is why closing the app is better.
Explorer holds a folder. Change directory or turn the preview off.
The list is huge. Filter by the filename in the error, not by curiosity.

## A Lock Is Not a Bug

Installers, sync clients, and editors hold files because they are using them. OpenedFilesView is how you find which one, so you can finish or quit it. A script that closes every handle on a directory will break the programs that were doing real work. One path, one process, one normal close. If the same installer lock survives a reboot, then it is a startup item, and this window has already told you the executable name to look up.

## Close the Program, Not Every Handle

The "file in use" dialog names a path. Refresh OpenedFilesView and find that path. Close the program the normal way, refresh, and try the rename again. Explorer often holds a folder because of a preview pane or because that folder is the current directory. Leave the folder. System processes stay in the list and stay running. Closing their handles crashes more than the file lock.

The list is this moment. It is not a history of yesterday's documents, and it is not a way to watch a PC you do not administer. If the process returns immediately, something relaunches it. That parent is the next stop, often a startup entry. One path, one process, one ordinary close.

- Error path searched, not the whole list
- App closed from its window
- Explorer preview considered
- System processes left alone
- Relaunch means a parent, not a second kill
- Refresh after the close
- Reboot only if the lock survives it

| Holder | Action |
|---|---|
| An editor you can see | Close the document |
| Explorer | Change folder or preview |
| Installer | Let it finish or exit it |
| Unknown temp exe | Note the path before you kill anything |

A lock usually means the file is in use on purpose.

## Further Reading

openedfilesview, nirsoft opened files, which process locks file, openedfilesview windows, file in use process, close locked folder, handle snapshot, openedfilesview path filter
