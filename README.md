# Medicine Viewer

A lightweight web app to browse basic information about medicines stored as JSON files.

## Features
- Displays medicine data from the `Medicine/` folder.
- Sidebar listing of available medicine files.
- Search box to quickly filter medicines. Trade names or commercial products
  will match their active ingredient.
- Responsive and simple design using plain HTML, CSS and JavaScript.
- The README is loaded and shown as the default home page.

## Usage
For best results run a simple HTTP server in the repository root and open `index.html` in your browser (for example `python3 -m http.server`). The app loads the available JSON files automatically. Click a medicine from the sidebar to view details.

The search box supports trade names in addition to active ingredient names. Typing a brand such as `Prozac` will reveal the Fluoxetine entry.

To add a new medicine, place a JSON file with the same structure as the provided examples in the `Medicine` folder and include its name in the `medFiles` array inside `index.html`.

v1.1.0 - Eymen Yıldırım®

## License
This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International** (CC BY-NC 4.0) License.  See the [LICENSE](LICENSE) file for details.
