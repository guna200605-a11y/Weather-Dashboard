<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Dashboard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Weather Dashboard</h1>
        <input id="city-input" type="text" placeholder="Enter city name">
        <button id="search-btn">Search</button>
    </header>
    <main>
        <section id="current-weather">
            <h2>Current Weather</h2>
            <p id="city-name"></p>
            <p id="weather-description"></p>
            <p id="temperature"></p>
            <p id="humidity"></p>
            <p id="wind-speed"></p>
        </section>
        <section id="forecast">
            <h2>5-Day Forecast</h2>
            <div id="forecast-container"></div>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>

