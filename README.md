# selected-facets-display

Polymer element providing a way to view and remove selected facets in a breadbox. Can be used with elastic-checkbox-list-filter and checkbox-list-display.

Example:
```html
  <selected-facets-display facet-selection="{{countryFacetSelection}}">
  </selected-facets-display>
```

### Styling

`<selected-facets-display>` provides the following custom properties and mixins
for styling:

Custom property | Description | Default
----------------|-------------|----------
`--selected-facet-bg-color` | Background color of a facet tag | --paper-blue-grey-200
`--selected-facet-text-color` | Text color for facets | --paper-blue-800

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

