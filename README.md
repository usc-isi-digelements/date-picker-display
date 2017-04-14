# date-picker-display

A Polymer Element that displays a date picker used for filtering (uses paper-date-picker).

Example:
```html
    <date-picker-display
      facet-selection="{{facetSelection}}"
      key="[[dateKey]]"
      title="[[dateTitle]]"
      prefix-label="[[datePrefixLabel]]"
      date-identifier="[[dateIdentifier]]">
    </date-picker-display>
```

### Styling

`<date-picker-display>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--date-select-bg-color` | Background color for the date selection buttons | --paper-blue-grey-200
`--date-select-text-color` | Text color for date selection buttons | --paper-blue-grey-800

To style the date picker popup, use the styling options supported by [Polymer.PaperDialogBehavior](https://github.com/PolymerElements/paper-dialog-behavior/).