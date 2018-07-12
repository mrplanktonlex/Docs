1. https://github.com/jonasschmedtmann/advanced-css-course
     - https://github.com/mrplanktonlex/advanced-css-course
2. http://codingheroes.io/resources/
3. https://docs.emmet.io/cheat-sheet/ 
4. https://codepen.io/

Tools Setups:-
- code editor: vscode
- browser: chrome

Vscode extensions:-
- Auto close tag + Auto Rename tag
- Color Highlight
- Paste and Indent
- Path Intellisense
- Prettier
- Project Manager

Settings
If you want your editor to work and look exactly the same way as mine does in the course videos, you can copy these settings to your own settings file. Just go to settings in VSCode, and on the right side, you can paste this code.

{
  "workbench.colorTheme": "Oceanic Next (dimmed bg)",
  "files.autoSave": "onFocusChange",
  "editor.minimap.enabled": true,
  "workbench.statusBar.visible": true,
  "workbench.activityBar.visible": true,
  "editor.formatOnSave": false,

  "workbench.colorCustomizations": {
    "statusBar.background": "#333333",
    "statusBar.noFolderBackground": "#333333",
    "statusBar.debuggingBackground": "#263238"
  },
  "editor.fontSize": 16,

  "css.validate": false,
  "scss.validate": false,
  "less.validate": false,
  "editor.wordWrap": "on"
}

--- 

Natours project 1: Download starter pack from https://github.com/mrplanktonlex/advanced-css-course/tree/master/Natours/starter 

The 3 shades of green we will use:-
/*
COLORS:

Light green: #7ed56f
Medium green: #55c57a
Dark green: #28b485

*/

L 06:
GOAL: Building the Header - Part1:-
G1. Best way to perform basic reset using the universal selector
G2. How to set project-wide font definitions
G3. How to clip parts of elements using clip-path. (modern css)

G1.
- normalize.css is used to do a cross-browser reset. Its no longer necessary as browsers are becoming smarter and the need for normalize.css is waning.
Instead lets just do a basic reset using the universal selector.
- what is a universal selector? 
* {  
}
This is an universal selector.

see L6-7-8-9-10.txt


