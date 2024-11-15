# Network Latency Checker

## Overview

The Network Latency Checker is a simple web application that monitors and displays network latency over time. It uses an image to measure the latency and displays the results in a line chart, offering an easy way to gauge the network stability and performance.

## Features

- Detects the online or offline status of the network.
- Measures network latency by loading a small image.
- Visualizes latency data using a real-time updating chart.
- Stores latency data in localStorage for persistence across page reloads.
- Automatically updates latency measurements every 5 seconds.
- Changes chart color to red when offline.

## Requirements

- Modern web browser with JavaScript support.
- Internet connection for loading the image used for latency measurement.

## Getting Started

1. Clone the repository to your local machine or download the source files.
2. Open `index.html` in your preferred web browser.
3. The network latency check will automatically begin, and results will be displayed in the embedded chart.

## Installation

No installation is required. This is a static HTML page and can be run directly in a browser.


## Usage

- Upon loading the page, the network status (online or offline) will be displayed.
- The application will measure latency every 5 seconds.
- Latency data is displayed in a scrolling line chart.
- Latency values are stored locally, providing a history across sessions.

## Limitations

- Requires an active internet connection for accurate measurement.
- The latency measurement might be affected by the reliability of the image source server.

## License

This project is licensed under the [MIT License](LICENSE).

## Demo






