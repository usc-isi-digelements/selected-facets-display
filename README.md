# selected-facets-display

A Polymer Element providing a way to view and remove selected facets in a breadbox-item element.

Example:
### Example
```js
var facets = {
  city: {
    'New York, NY': {
      category: 'City',
      enabled: true,
      text: 'New York, NY'
    }
  }
};
```

```html
<selected-facets-display
  facet-key="city"
  facets="{{facets}}">
</selected-facets-display>
```

### Styling

`<selected-facets-display>` provides the following custom properties and mixins for styling:

Custom property                     | Description                           | Default
------------------------------------|---------------------------------------|--------
`--selected-facet-icon-color`       | The color of the icon(s).             | --paper-grey-900
`--selected-facet-icon-hover-color` | The color of the close icon on hover. | --paper-red-900
`--selected-facet-item-style-mixin` | The custom style mixin of the items.  | none
`--selected-facet-text-color`       | The text color of the items.          | --paper-grey-900

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

