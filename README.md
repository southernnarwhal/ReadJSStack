# ReadJSStack
## Display a Map Using ArcGIS Maps SDK for JavaScript

This project demonstrates how to display an interactive map using the ArcGIS Maps SDK for JavaScript. It initializes a map with the "oceans" basemap and centers it over the Sea of Okhotsk.

## Getting Started

Follow these steps to set up and run this HTML file:

### Prerequisites

- An ArcGIS API key is required to authenticate requests to ArcGIS services.
- Basic understanding of HTML, CSS, and JavaScript.

### Installation

1. Clone or download this repository.
2. Replace `"YOUR_ACCESS_TOKEN"` with your actual ArcGIS API key in the `esriConfig.apiKey` line.

### File Structure

This single HTML file contains the following elements:

- **HTML Structure**:
  - `<head>`: Includes links to ArcGIS Maps SDK and stylesheets.
  - `<div id="viewDiv"></div>`: This div is where the map will be displayed.
  
- **CSS Styling**:
  - Ensures full-screen map view by setting height and width to 100% for `html`, `body`, and `#viewDiv`.
  
- **JavaScript**:
  - Loads ArcGIS Maps SDK modules: `esri/config`, `esri/Map`, and `esri/views/MapView`.
  - Creates a `Map` object using the "oceans" basemap.
  - Initializes a `MapView` with a center and zoom level to display Japan, Siberia, and the Sea of Okhotsk.

## Usage

1. Open the HTML file in a web browser.
2. If the API key is valid, the map centered on the Sea of Okhotsk will load with an oceans basemap.
3. Open the developer console (press `F12` in most browsers) to view any console messages.

### Configuration

- **Basemap**: Modify the basemap by changing `basemap: "oceans"` to another option, such as `"topo-vector"` or `"satellite"`.
- **Map Center**: Update the `center` property to display different geographic coordinates.
- **Zoom Level**: Adjust the `zoom` property to change the initial zoom level of the map.

## Dependencies

- [ArcGIS Maps SDK for JavaScript 4.30](https://developers.arcgis.com/javascript/)

## License

This project is licensed under the MIT License.
