---
filename: /packages/material-ui/src/ListItemIcon/ListItemIcon.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# ListItemIcon API

<p class="description">The API documentation of the ListItemIcon React component. Learn more about the properties and the CSS customization points.</p>

```js
import ListItemIcon from '@material-ui/core/ListItemIcon';
```

A simple wrapper to apply `List` styles to an `Icon` or `SvgIcon`.

## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name required">children&nbsp;*</span> | <span class="prop-type">element</span> |  | The content of the component, normally `Icon`, `SvgIcon`, or a `@material-ui/icons` SVG icon element. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element (native element).

## CSS

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:


| Name | Description |
|:-----|:------------|
| <span class="prop-name">root</span> | Styles applied to the root element.
| <span class="prop-name">alignItemsFlexStart</span> | Styles applied to the root element when the parent `ListItem` uses `alignItems="flex-start"`.

Have a look at the [overriding styles with classes](/customization/components/#overriding-styles-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/ListItemIcon/ListItemIcon.js)
for more detail.

If using the `overrides` [key of the theme](/customization/themes/#css),
you need to use the following style sheet name: `MuiListItemIcon`.

## Notes

The component is fully [StrictMode](https://reactjs.org/docs/strict-mode.html) compatible.

## Demos

- [Lists](/components/lists/)

