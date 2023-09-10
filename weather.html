
const apiKey = '811123e85c5117f7a79613dceedc1957';

const city = "Ormond Beach";
const unit = "imperial";  // Fahrenheit

fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=${unit}`)
    .then(response => response.json())
    .then(data => {
        const temperature = data.main.temp.toFixed(1);
        const feelsLike = data.main.feels_like.toFixed(1);
        const description = data.weather[0].description;
        const icon = data.weather[0].icon;
        const windSpeed = data.wind.speed;
        const windDirection = data.wind.deg;
        const humidity = data.main.humidity;

        document.querySelector("#weather").innerHTML = `
            <h2>Weather in Ormond Beach</h2>
            <p>Temperature: ${temperature}°F</p>
            <p>Feels Like: ${feelsLike}°F</p>
            <p>Condition: ${description}</p>
            <img src="http://openweathermap.org/img/wn/${icon}.png" id="icon">
            <p>Wind Speed: ${windSpeed} mph</p>
            <p>Wind Direction: ${windDirection}°</p>
            <p>Humidity: ${humidity}%</p>
        `;
    })
    .catch(error => {
        console.error("There was an error fetching the weather data.", error);
    });
