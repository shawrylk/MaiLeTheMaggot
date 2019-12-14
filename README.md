Notepad++ v7.8 enhancements and bug-fixes:

1.  Upgrade Scintilla from 4.1.4 to 4.2.0
2.  Fix non Unicode encoding problem in non-Western language(Chinese or in Turkish).
3.  Add "No to All" and "Yes to All" options in Save dialog.
4.  Add the command line argument "-openFoldersAsWorkspace" to open folders in "folder as workspace" panel.
    Example: notepad++ -openFoldersAsWorkspace c:\src\myProj01 c:\src\myProj02
5.  Enhance plugin system: allow any plugin to load private DLL files from the plugin folder.
6.  Fix File-Rename failing when new name is on a different drive.
7.  Make "Clear all marks", "Inverse Bookmark", "Remove Consecutive Duplicate Lines" & "Find All Current Document" to be macro recordable.
8.  Make "Command Argument Help" MessageBox modal. 
9.  Fix Folder as Workspace crash and "queue overflow" issues.
10. Make Combobox font monospace in Find dialog.
11. Fix folding in user-defined languages for non-windows line endings.
12. Fix crash of Folder as Workspace when too many directory changes happen.   
13. Fix '-nosession' overwrites config.xml issue.
14. Fix the crash due to NPPM_DESTROYSCINTILLAHANDLE message.
15. Improve GUI in Find dialog for Find Previous & Find Next buttons.
16. Fix Sort Line as Integer regression.
17. Add more OS information to debug info. 
18. Fix tab dragging issues under WINE and ReactOS.
19. Enhance supported language (on function list or auto-completion): LISP, BaanC,(PL/)SQL & COBOL.
20. Fix indent indicators continue to following code blocks for Python.
21. Fix Python folding collapse issue.
22. Fix crash when sorting "out of range" columns.
23. Fix find 2 times for the same occurrence in both original and cloned documents issue.
24. Fix command line issues where filenames have multiple white spaces in them.

Unicode
1.  Fix popup dialog on startup regression regarding notepad replacement issue.
2.  Make monospaced font in Find dialog optional, disabled by default.
3.  Add download progress bar while download plugin(s).
4.  Fix issue for Alt+Tab doesn't show Notepad++ on Windows 7.

