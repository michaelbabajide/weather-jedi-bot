# Weather Bot (Work in Progress)

## Introduction

Weather Bot is a simple Telegram bot that provides weather forecasts for user-specified locations. The bot allows users to input a location, and it returns the weather forecast for that location using the OpenWeatherMap API. This project is currently a work in progress, and I am continuously enhancing its functionality and features.

## Requirements

- Python 3.x
- Python-telegram-bot library
- Requests library
- Geopy library
- OpenWeatherMap API key

## Setup

1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Obtain your OpenWeatherMap API key and set it as the value of the `WEATHER_TOKEN` environment variable.
4. Obtain your Telegram Bot Token and set it as the value of the `BOT_TOKEN` environment variable.

## Usage

1. Start the bot by running the Python script `weather_bot.py`.
2. Open your Telegram app and search for the bot by its username.
3. Use the `/start` command to initiate a conversation with the bot.
4. Use the `/weather` command to request weather information. The bot will prompt you to enter a location.
5. Enter the desired location (e.g., city name, postal code) to get the weather forecast.

## Work in Progress

This project is still under development, and I am actively working on improving its features and usability. Some of the planned enhancements include:

- Supporting more weather forecast details, such as temperature, humidity, and wind speed.
- Implementing location detection based on user coordinates.
- Implementing unit tests to ensure correctness of wach function's behaviour.
- Enhancing error handling and user experience.

## Contribution

I welcome contributions to this project! If you have any ideas for improvements or would like to report issues, please feel free to create a pull request or open an issue in the repository.

## Disclaimer

This project is for educational purposes and should not be used as a production-level weather service. The accuracy and reliability of the weather data depend on the third-party API and geocoding service.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or questions, please contact [babajidemichael67@gmail.com].
