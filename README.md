# react-flight-tracker
An open-source project written with React and TypeScript.

The goal of this project is to read the data from [OpenSky Network](https://opensky-network.org/) and visualize it on a map.

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## 📦 Packages:
- [ts-lib-module](https://github.com/xSNOWM4Nx/ts-lib-module)
- [react-lib-module](https://github.com/xSNOWM4Nx/react-lib-module)
- [TypeScript](https://github.com/microsoft/TypeScript)
- [react-router](https://github.com/ReactTraining/react-router)
- [material-ui](https://github.com/mui-org/material-ui)
- [react-map-gl](https://github.com/uber/react-map-gl)

## 🔮 Features:
- Using "Hooks", "Context" and other popular React patterns.
- Written entirely in TypeScript.
- Using maps from [mapbox](https://www.mapbox.com/) with the React friendly wrapper [react-map-gl](https://github.com/uber/react-map-gl) from Uber.
- Using styling components from the popular [material-ui](https://github.com/mui-org/material-ui) project.
- Fetching flight data from [OpenSky Network](https://opensky-network.org/).

## 🔌 Usage:
You will need a [mapbox](https://www.mapbox.com/) access token in order to display the map. For development and own-use it is perfectly fine to use their free option.

In order to have more recent flight data around ~5 seconds, create a free account on [OpenSky Network](https://opensky-network.org/). If you do not have an account the flight data will be around ~10 seconds old.

Start by cloning the repository and install the packages:
```
npm install
```
Create a `.env.local` file in the root directory containing following entries:
```
REACT_APP_MAPBOX_TOKEN=<YOUR_MAPBOX_TOKEN>
REACT_APP_OSKY_USERNAME=<YOUR_OPENSKYNETWORK_USERNAME>
REACT_APP_OSKY_PASSWORD=<YOUR_OPENSKYNETWORK_PASSWORD>
```
Start the project:
```
npm start
```

## 📑 License:
- MIT © [xSNOWM4Nx](https://github.com/xSNOWM4Nx)
---
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).