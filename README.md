# Earthquake Map

An interactive Java applet that visualizes earthquakes and cities worldwide, with features for exploring seismic data on a live map.

## Features

- Browse earthquake and city markers across a global map
- Hover over a **city marker** to see its name, country, and population
- Hover over an **earthquake marker** to see its magnitude and region
- Click a **city marker** to isolate it and show only earthquakes that could affect it
- Click an **earthquake marker** to show only cities within its potential impact zone
- Click the active marker again to restore the full map view
- Zoom into any location by clicking directly on the map

## Installation

### Eclipse

1. Clone the repository to your local machine
2. Open Eclipse and go to **File → Import → Existing Projects into Workspace**
3. Select the `UnfoldingMapsProject` folder and click **Finish**

### Other IDEs

1. Clone the repository to your local machine
2. Create a new Java project in your IDE
3. Copy all project files into the project directory
4. Add all JARs from the `lib/` folder to your build path
5. Set the native library location for `jogl.jar` to the folder matching your OS
6. Add the `data/` folder as a source (`src`) directory

## Troubleshooting

| Problem | Solution |
|---|---|
| VM errors on launch | Switch the Java Compiler version to **1.6** or **1.7** in your IDE settings (Processing is compatible with both) |

## Preview

After building the project, the map will launch and display markers for earthquakes and cities around the world. Interact with the markers to explore seismic data and city details.

<img width="900" height="739" alt="earthquake-applet-view" src="https://github.com/user-attachments/assets/c5f4f15e-3cc9-4aee-9822-9c6078d43112" />
