
# Weather Application

The weather application project built in React utilizes weather APIs to fetch real-time weather data and display it to users in a user-friendly interface. Users can input their City to get current weather information, including temperature, humidity, wind speed. The application is responsive, offering a seamless experience across various devices, and may include features like visual representations of weather data and user customization options for units and weather providers.


## Demo

https://weatherappllicaton.netlify.app/


## API Reference

#### Fetch by City Name
```
  https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
```

#### Fetch by City Name & Country Code
```
https://api.openweathermap.org/data/2.5/weather?q={city name},{country code}&appid={API key}
```

#### Fetch by City Name, Country Code & State Code
```
https://api.openweathermap.org/data/2.5/weather?q={city name},{state code},{country code}&appid={API key}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |
| `city name` | `string` | City Name |
| `state code`| `string` | State Code |
| `country code`| `string` | Country Code |



## Installation

 In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
    
