### 1.1.1

- Improvement: export workspace diagrams will be organized in a directory named with "out" by default. you can changed directory name with setting `plantuml.exportOutDirName`.

### 1.1.0

- New Feature: Export workspace diagrams
- Add more suffixes: ".iuml", ".plantuml"
- Small improvements
- Changed command name and display

### 1.0.5

- `plantuml.exportFormat` default is not set, user may pick one format everytime exports. You can still set a format for it if you don't want to pick. Setting enumeration added.
- currnet document remains active after preview command
- Bug Fix: Update twice when trigger preview command
- code optimization

### 1.0.4

- Improvement: Update preview when move cursor to another diagram
- Improvement: Stop watching when preview closed. But it has a 3 minutes delay due to [#13623](https://github.com/Microsoft/vscode/issues/13623)
- Bug Fix: Remove excess "PlantUML:" display in Command Palette

### 1.0.3

- Bug Fix: dealing with unsaved file
- New Feature: Symbol list support

### 1.0.2

- Improvement: custom error display

### 1.0.1

- Bug Fix: export diagram without title

### 1.0.0

- Initial release ...