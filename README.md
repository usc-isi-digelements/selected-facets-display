# selected-facets-display

A Polymer Element providing a way to view and remove selected facets in a breadbox-item element.  Can be used with the [checkbox-list-display](https://github.com/DigElements/checkbox-list-display) element and the [elastic-checkbox-list-filter](https://github.com/DigElements/elastic-checkbox-list-filter) element.

Example:
```html
<selected-facets-display facet-selection="{{countryFacetSelection}}"></selected-facets-display>
```

### Styling

`<selected-facets-display>` provides the following custom properties and mixins for styling:

Custom property                     | Description                     | Default
------------------------------------|---------------------------------|----------------------
`--selected-facet-bg-color`         | Background color of a facet tag | --paper-blue-grey-200
`--selected-facet-text-color`       | Text color for facets           | --paper-blue-grey-800
`--selected-facet-icon-hover-color` | Color for close icon on hover   | --paper-blue-800

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

