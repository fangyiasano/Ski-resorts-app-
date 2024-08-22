## Overview

This application is designed to provide interactive visual analytics for ski resorts wordwide, integrating multiple metrics such as elevation, price, slope length, and snow cannons availability.

## Features

### Interactive Maps and Charts
**Resort Map:** Displays ski resorts on a density map, filterable by price and amenities like summer skiing, night skiing, and snow parks.
 ![ScreenRecording2024-08-21at22 54 46-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/be402c40-43a7-482e-985d-002d2a6b25b4)
 ![ScreenRecording2024-08-21at23 17 49-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/16d95ede-6f70-4b1c-ac0a-078c6d437ca8)

- **Country Profiler:** Enables users to view and analyze resorts' rankings within a specific country based on selected metrics. The visualization is presented through interactive bar charts.
 ![ScreenRecording2024-08-21at23 28 31-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/aa1572ee-6dfe-493d-a5fc-db923a0e8b3b)

### Dynamic Theme Customization
- Users can customize the application’s appearance by selecting from a variety of Bootstrap themes via a dropdown menu, enhancing the user interface and accessibility.
 ![ScreenRecording2024-08-21at23 38 50-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/6831c00e-e27a-40c7-a7ab-c7595801871e)
  
## Installation

### Prerequisites
- Python 3.6+
- Pandas
- Dash
- Plotly

### Install Required Packages
```bash
pip install jupyter_dash
pip install dash_bootstrap_components
pip install dash_bootstrap_templates
```

### Running the Application
Execute the Notebook.

## Interactivity

- The app includes several interactive components such as dropdowns, sliders, and checkboxes that trigger visual updates.
- Dash callbacks handle the interactivity, ensuring real-time data processing and visualization updates based on user inputs.

## Example Usage

- **Market Analysts:** Evaluate competitive standings of ski resorts in various regions.
- **Tour Operators:** Identify popular resorts based on specific requirements and price points for targeted package offerings.
- **Policy Makers:** Assess the tourism capacity and infrastructure of ski resorts to guide development policies.
