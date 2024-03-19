# weatherapp
![screenshot](https://github.com/omkarchoudhary001/weatherapp/assets/109873576/7c26ca76-84e5-42de-8017-7bce1a719594)
# Weather App

This is a weather application built using SvelteKit, Tailwind CSS, and TypeScript. It allows users to search for weather information by city name or zip code, displaying the current weather conditions including temperature, description, wind speed, humidity, and UV index. Additionally, it provides an optional 5-day forecast.

## Features

- Search for weather by city name or zip code.
- Display current weather conditions including temperature, description, wind speed, humidity, and UV index.
- Optional 5-day forecast.
- Responsive design for different screen sizes.
- Accessibility considerations for users with disabilities.
- Visual feedback to enhance user experience.

## Technologies Used

- [SvelteKit](https://kit.svelte.dev/): A framework for building Svelte applications.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for quickly building custom designs.
- [TypeScript](https://www.typescriptlang.org/): A statically typed superset of JavaScript that compiles to plain JavaScript.

## Additional Libraries

- [Svelte Store](https://svelte.dev/docs#svelte_store): For state management within the application.

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. Navigate into the project directory:

    ```bash
    cd weather-app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the application.

## Usage

- Enter a city name or zip code into the search input field.
- Press the search button or hit enter to retrieve weather information.
- View the current weather conditions including temperature, description, wind speed, humidity, and UV index.
- Optionally, navigate to the 5-day forecast section to see weather predictions for the upcoming days.

## Folder Structure

The project follows a component-based structure for better modularity and maintainability:

```
src/
├── components/             # Reusable UI components
├── routes/                 # Page components and routing
├── store/                  # Svelte Store for state management
└── ...
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you'd like to see added to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This application utilizes weather data from [OpenWeather](https://openweathermap.org/).
- Special thanks to the creators of SvelteKit, Tailwind CSS, and TypeScript for their amazing tools and documentation.

--- 
 Happy coding!
