# VS Save Popup

Visual Studio 2022 extension that shows a notification when a document is saved.  
Supports **MessageBox**, **InfoBar**, or **StatusBar** notifications with **debounce** and **extension filters**.

## Install (Local)
- Build `Release` → install the generated `.vsix`
- Settings: `Tools > Options > VS Save Popup > General`
- Toggle: `Extensions > VS Save Popup > Enable`

## Options
- Enabled: On/Off
- Notify Type: MessageBox / InfoBar / StatusBar
- Extensions: `.cs,.sql,.js` (empty = all)
- Debounce: default 500ms
- Title/Template: `{path}` placeholder available

## Dev
- Open solution → **F5** → Experimental Instance
- Packaging: `bin/Release/*.vsix`

## License
MIT
