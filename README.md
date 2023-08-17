# Node-RED Moving Average Node

[![Platform](https://img.shields.io/badge/platform-Node--RED-red)](https://nodered.org)
[![node-red-contrib-moving-average](https://img.shields.io/github/v/release/racksync/node-red-contrib-moving-average)](https://github.com/racksync/node-red-contrib-moving-average/releases) [![last commit](https://img.shields.io/github/last-commit/racksync/node-red-contrib-moving-average)](https://github.com/racksync/node-red-contrib-moving-average/commit/)

Have you ever been in need to compute a running average of your incoming data in Node-RED? Well, you're in the right place! This script efficiently calculates the moving average of the latest data points, ensuring you always get the most recent average without storing an excessive amount of old data.

## Features:

🚀 Adjustable Window Size: The default window size is set to 20, but feel free to modify Windows Size to fit your specific needs.
🚀 Efficient Storage: Only the most recent data points up to Windows Size are stored, ensuring optimal memory usage.
🚀  Easy Integration: The script is plug-and-play! Simply integrate it into your Node-RED flow, and you're good to go.
🚀 Feel free to contribute, suggest improvements, or report any issues you face. Let's make data processing smoother for everyone! 😊

# Installation

You can install the nodes using "Manage palette" by searching ```moving average``` from node-red kebab menu or run the following command in the root directory of your Node-RED installation

```
npm install node-red-contrib-moving-average --save
```

# Usage

Put "Movng Average" into your flow workspace as you wish

![racksync-screenshot](https://github.com/racksync/node-red-contrib-moving-average/blob/main/images/screenshot.png?raw=true)

### Node-RED Node by RACKSYNC
- [Toggle Flows](https://flows.nodered.org/node/@racksync/node-red-contrib-hass-flow)
- [Tradfri Remote](https://flows.nodered.org/node/@racksync/node-red-contrib-hass-tradfri-remote)
- [Low Pass Filter](https://flows.nodered.org/node/@racksync/node-red-contrib-low-pass-filter)
- [Moving Average](https://flows.nodered.org/node/@racksync/node-red-contrib-moving-average)


### Tips

- It is recommended to always do a full deploy when you changed some of the nodes of this library to prevent unexpected behavior.
- Always use debug node to test message payload before using in Production.

### Automation Training

- [Product & Services](http://racksync.com)
- [Training & Course](https://facebook.com/racksync)

## [RACKSYNC CO., LTD.](https://racksync.com)

We helps our customers to create life easier across the border of entire technology stack with household and business solutions. We modernize life with Information Technology, Optimize and collect data to make everything possible, secure & trusty
\
\
RACKSYNC COMPANY LIMITED \
Suratthani, Thailand \
Email : devops@racksync.com \
Tel : +66 85 880 8885 

[![Home Automation Thailand Discord](https://img.shields.io/discord/986181205504438345?style=for-the-badge)](https://discord.gg/Wc5CwnWkp4) [![Github](https://img.shields.io/github/followers/racksync?style=for-the-badge)](https://github.com/racksync) 
[![WebsiteStatus](https://img.shields.io/website?down_color=grey&down_message=Offline&style=for-the-badge&up_color=green&up_message=Online&url=https%3A%2F%2Fracksync.com)](https://racksync.com)
