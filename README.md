# Sensortweets

Welcome to Sensortweets, a simple yet effective Twitter bot designed to fetch daily PNG images from Grafana and post them on Twitter. This bot is a local initiative from Partij voor de Dieren Utrecht, The Netherlands. We encourage you to copy, re-use, and adapt our scripts to your needs. All our scripts are MIT licensed, and everything else is at least GPL licensed. You can learn more about these licenses [here](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licences).

## What does Sensortweets do?

Our bot performs a few key tasks:

1. **Fetches a daily PNG image from Grafana**: We use a public Grafana instance that doesn't have image rendering functionality. Our bot uses the `capture-website-cli` tool to capture a screenshot of the Grafana dashboard and save it as a PNG image.

2. **Posts the image to Twitter**: After capturing the screenshot, our bot posts the image on Twitter, providing daily updates directly from Grafana to your Twitter feed.

3. **Scheduled updates**: The final script is designed to be scheduled using either cron or a systemd timer. This allows the bot to automatically fetch and post images every day without any manual intervention.

## Requirements

To use Sensortweets, you'll need the following:

- Node.js
- npm
- capture-website-cli
- Python
- systemd or cron for scheduling
- System sandboxing should be enabled

For the alternative script that uses Docker, only Docker is required.

## How to Use

1. Clone this repository and navigate to the project directory.
2. Install the required tools and libraries.
3. Set up your Twitter API credentials and Grafana URL in the script.
4. Schedule the script using cron or a systemd timer.

Feel free to contribute to this project or use it as a starting point for your own.
