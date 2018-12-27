function_name: "drawRectangle"
function_type: "Global and local"

arguments:
  - name: x
    type: int/float
  - name: y
    type: int/float
  - name: width
    type: int/float
  - name: height
    type: int/float
  - name: fillColor
    type: string/object
  - name: storkeColor
    type: string/object
  - name: settings
    type: object
    arguments:
      fillColor: string/object
      strokeColor: string/object
      lineWidth: int/float
      roundedCorners: bool

aliases:
  - name: "rectangle"
  - name: "rect"
  
description: "drawRectangle, rectangle or rect draws a rectangle at (x, y) with the specified width and height, fillColor, strokeColor and settings"

examples:
  - name: "Draw rectangle"
    description: "Draws a red rectangle with orange outline to the screen. Position: (100, 100), width: 75, height: 60"
    code: "var gc = new GameCanvas();\n\nrectangle(100, 100, 75, 60, \"red\", \"orange\");"

last_updated: 2018-12-27
edit_notes: "Create file"
