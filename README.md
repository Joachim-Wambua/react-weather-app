# Weather Application using ReactJS and OpenWeatherMapAPI

![Weather App](https://res.cloudinary.com/dltjv8zbh/image/upload/v1704138433/Weather_App2_smxc0m.gif)

<div align="center" >
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://seeklogo.com/images/O/openweather-logo-3CE20F48B5-seeklogo.com.png" alt="openweathermapapi" width="100px"/>
</div>

## Overview

Welcome to the Weather Application built with ReactJS and powered by the OpenWeatherMapAPI. This simple and user-friendly app allows users to search for cities and 4retrieve real-time weather data, providing a quick and convenient way to stay updated on the current weather conditions.

## Features

- **City Search:** Users can easily search for cities to get up-to-date weather information.
- **Real-time Data:** The app queries the OpenWeatherMapAPI to display current weather data.
- **Responsive Design:** Ensures a seamless experience on various devices.

## Getting Started

Follow these steps to run the project locally on your machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- OpenWeatherMapAPI Key. Get yours [here](https://openweathermap.org/appid).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Joachim-Wambua/react-weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd react-weather-app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

### Configuration

1. Obtain an API key from [OpenWeatherMapAPI](https://openweathermap.org/appid).
2. Create a `.env` file in the root directory of the project.
3. Add your API key to the `.env` file:

    ```env
    REACT_APP_API_KEY=your-openweathermap-api-key
    ```

### Usage

Run the development server:

```bash
npm run dev
