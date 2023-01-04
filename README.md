# SVG Editor
This repository is for the SVG editor

## Concepts:
- Shape: the geometry object displayed in canvas, include rectangle, line, ellipse and so on. It also covers the object which could be surranded by the geometry frame, for example, text and image.
- Layout: the group of shapes. All of shapes in one group apply the same behavior (moving, resizing, layer number chaning, color changing and so on).
- Widget: the concepts of shape and layout are collectively called as widget.
- Menu: the area in the top of the web browser, in which all of the supported functions are provided for user operations.
- Toolbar: the area in the top of the web browser, under the menu, in which the frequent used functions are provided as the icons for user operations.
- Overview sidebar: the area in the left of the web browser, in which the organizations of pages and layers are displayed as hierarchy.
- Property sidebar: the area in the right of the web browser, in which the properties of the selected widget (shape or layout) are displayed, and also are allowed to modify by the user.
- Workplace: the area in the center of the web browser, in which user could design and draw the image.

## Requirements
- [x]  Workplace (HTML5 canvas)
    - [x]  Canvas initializing
    - [x]  Widget (shape and layout)
        - [x]  Percentage (Relative units)
        - [ ]  Scale
        - [x]  Rotation
        - [x]  Moving
        - [x]  Multiselecting
        - [ ]  Resizing
    - [x]  Events handler
      - [x]  Mouse Event
        - [x]  Drag and drop events
        - [x]  Mouse down, move and up events
        - [ ]  Click and double click events
      - [x]  Touch Event
        - [x]  Touch start, move and end events
      - [ ]  Keyboard event
- [ ]  User operations (provided in the menu and toolbar)
    - [ ]  Add and delete shapes
    - [ ]  Undo and redo
    - [ ]  Bring forward and backward (layers)
    - [ ]  Group widgets (layout)
- [ ]  Overview sidebar
    - [ ]  Multipage organization
    - [ ]  Multilayer organization
- [ ]  Property sidebar
    - [ ]  Get the widget properties and shown in the sidebar
    - [ ]  Set the widget property values changed in the sidebar
- [ ]  Supported image file formats
    - [ ]  SVG: Loading (optional)
    - [ ]  SVG: Saving
    - [ ]  XML: Loading
    - [ ]  XML: Saving
    - [ ]  Yaml: Loading
    - [ ]  Yaml: Saving
    - [ ]  Json: Loading
    - [ ]  Json: Saving
