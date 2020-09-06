# Notepad++ macro to fix Google Translated Gutenber tags

## Notepad++ macros file location Windows 7/8/10
C:\Users\%username%\AppData\Roaming\Notepad++\shortcuts.xml

## Insert the macro into the the marco file (shortcuts.xml).
Insert the <macro>...</macro> code from the repo into the <macros>...</macro> tags.

## Modifying/adding a replacement action in an existing macro
All actions in the code are string replacement actions.

Copy an existing replacement sequence for example this paragraph:
'
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="paragraaf" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="paragraph" />
            <Action type="3" message="1702" wParam="0" lParam="768" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
'

Modify as required.

## Notes
When you record a macro inside the Notepad++ application, the changes to shortcuts.xml are written when the application closes.
So don't panic if you recorded a macro while having shortcuts.xml open and you don't see your changes. When you close and reopen, they'll be there.
