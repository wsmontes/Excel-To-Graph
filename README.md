# GPU-Accelerated Graph Visualizer

An advanced, browser-based 3D graph visualization tool that leverages GPU acceleration for smooth rendering of large networks.

## Features

- **High Performance**: GPU-accelerated rendering using Three.js
- **Multiple File Formats**: Import data from Excel, CSV, or JSON
- **Interactive Mapping**: Map data columns to visual properties
- **Automatic Suggestions**: Smart column mapping based on data patterns
- **Real-time Visualization**: Progressive loading for large datasets
- **Responsive Design**: Works on both desktop and mobile devices

## Usage

1. Open `GraphV5.html` in a modern web browser
2. Click "Choose File" and select your data file (Excel, CSV, or JSON)
3. Configure the column mappings (or use the auto-suggested mappings)
4. Explore your graph data in 3D space:
   - Rotate: Click and drag
   - Zoom: Mouse wheel or pinch gesture
   - Pan: Right-click and drag

## Data Format Requirements

Your input file should contain:
- **For nodes**: At minimum, columns for node IDs and labels
- **For edges**: Columns for source and target node IDs
- **Optional**: Additional columns for node colors, sizes, and grouping

## Examples

For optimal results, prepare your data with these column types:
- **Node ID**: A unique identifier for each node
- **Node Label**: Text to display on nodes
- **Node Color**: Can be text (auto-converted to color) or hex codes
- **Node Size**: Numeric values (automatically scaled)
- **Group**: Category names for color grouping
- **Edge Source/Target**: Node IDs for connecting edges

## Dependencies

- [Force Graph 3D](https://github.com/vasturiano/3d-force-graph)
- [Three.js](https://threejs.org/)
- [XLSX.js](https://sheetjs.com/)
- [PapaParse](https://www.papaparse.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)

## License

MIT License - see LICENSE file for details
