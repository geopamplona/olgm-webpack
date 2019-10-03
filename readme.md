# OpenLayers - Google Maps integration library + Webpack

This example demonstrates how the `olgm` package can be used with webpack.

Clone the project.

    git clone git@github.com:geomaplona/olgm-webpack.git

Install the project dependencies.

    cd olgm-webpack
    npm install

Create a bundle for the browser.

    npm run build

Open `index.html` to see the result.

    open index.html

To use OL-Google-Maps, first you need to load Google Maps API. It's important to load Google Maps API **before** OL-Google-Maps. You also need to use your own Google Maps API key.

```
<script
  type="text/javascript"
  src="https://maps.googleapis.com/maps/api/js?v=3&key=<YOUR_KEY>">
</script>
```