## Installation
Due to a bug on `iron-overlay-backdrop`, if you want to override the styles, you must add them in the root file (ex. index.html).
This effect projects that start with polymer-starter-kit

Read more for the bug here:
https://github.com/Polymer/polymer-starter-kit/issues/154

## Properties
Property | Description
---------|-------------
active   | dialog header, wrapped on a "h2" element tag
disabled | dialog content, wrapped on a "p" element tag

## Example

```html
<gfs-item on-click='console'>Item 1</gfs-item>
<gfs-item icon="view-list">Item 2</gfs-item>
<gfs-item selected>Item 3</gfs-item>
<gfs-item disabled>Item 4</gfs-item>

```


## Styling
Custom property | Description | Default
----------------|-------------|----------
--gfs-item-selected-color | Color of the a selected item | `var(--black-color)`
--gfs-item-selected-background | Background color of the a selected item | `rgba(236, 236, 236, 0.7)`
--gfs-item-selected-font-weight | Font weight of a selected item | `500`
--gfs-item-selected | Mixin applied to the item | {}

