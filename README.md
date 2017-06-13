# date-picker-display

A Polymer Element that displays a date picker used for filtering (uses paper-date-picker).

### Example
```js
var facets = {
  dates: {
    dateStart: {},
    dateEnd: {}
  }
};
```

```html
<date-picker-display
  facet-key="dates"
  facets="{{facets}}"
  key="dateStart"
  title="Date From"
  prefix-label="From"
  date-identifier="start">
</date-picker-display>
```

### Styling

`<date-picker-display>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--date-select-bg-color` | Background color for the date selection buttons | --paper-blue-grey-200
`--date-select-text-color` | Text color for date selection buttons | --paper-blue-grey-800

To style the date picker popup, use the styling options supported by [Polymer.PaperDialogBehavior](https://github.com/PolymerElements/paper-dialog-behavior/).

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct
