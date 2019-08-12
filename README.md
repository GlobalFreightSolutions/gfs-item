## GFS Item
`<gfs-item>` is a interactive list item.

### Install

```bash
$ npm i --save @gfsdeliver/gfs-item
```

### Import In a HTML file:

```html
<html>
    <head>
        <script type="module">
            import '@gfsdeliver/gfs-item/gfs-item.js';
        </script>
    </head>
    <body>
        <gfs-item>Item</gfs-item>
    </body>
</html>
```

### In a Polymer 3 element
```js
import { PolymerElement, html } from '@polymer/polymer/polymer-element.js';
import '@gfsdeliver/gfs-item/gfs-item.js';

class CustomElement extends PolymerElement {
    static get template() {
        return html`
            <gfs-item>Item</gfs-item>
        `;
    }
}
customElements.define('custom-element', CustomElement);
```

## Properties
Property | Description
---------|-------------
active   | dialog header, wrapped on a "h2" element tag
disabled | dialog content, wrapped on a "p" element tag

## Styling
Custom property | Description | Default
----------------|-------------|----------
--gfs-item | Mixin applied to the item | {}
--gfs-item-selected-color | Color of the a selected item | `var(--black-color)`
--gfs-item-selected-background | Background color of the a selected item | `rgba(236, 236, 236, 0.7)`
--gfs-item-selected-font-weight | Font weight of a selected item | `500`
--gfs-item-selected | Mixin applied to the selected item | {}
--gfs-item-focused | Mixin applied to the focused item | {}
--gfs-item-disabled | Mixin applied to the disabled item | {}

