# aggregation-display

A Polymer Element showing a bar chart with a header, loading spinner, and Show More button.

### Example
```html
<aggregation-display
  show-checkboxes
  data="[[data]]"
  selected-ids="{{selected}}">
</aggregation-display>
```

### Styling

`<aggregation-display>` provides the following custom properties and mixins for styling:

Custom property                                      | Description                                                         | Default
-----------------------------------------------------|---------------------------------------------------------------------|--------
`--aggregation-display-bar-color`                    | The color of the single or left bars.                               | --paper-grey-300
`--aggregation-display-bar-count-color`              | The color of the single or left count labels.                       | --paper-grey-900
`--aggregation-display-bar-height`                   | The height of the single or left bars.                              | 20px
`--aggregation-display-bar-title-color`              | The color of the single or left title labels.                       | --paper-grey-900
`--aggregation-display-bar-title-hover-color`        | The color of the single or left title labels on hover (if a link).  | --paper-indigo-900
`--aggregation-display-max-height`                   | The max height of the bar chart.                                    | 280px
`--aggregation-display-second-bar-color`             | The color of the right (second) bars.                               | --paper-grey-300
`--aggregation-display-second-bar-count-color`       | The color of the right (second) count labels.                       | --paper-grey-900
`--aggregation-display-second-bar-height`            | The height of the right (second) bars.                              | 20px
`--aggregation-display-second-bar-title-color`       | The color of the right (second) title labels.                       | --paper-grey-900
`--aggregation-display-second-bar-title-hover-color` | The color of the right (second) title labels on hover (if a link).  | --paper-indigo-900

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

