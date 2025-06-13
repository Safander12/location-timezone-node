# 🌍 Location Timezone Node

![GitHub Release](https://img.shields.io/github/v/release/Safander12/location-timezone-node?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-16.0%2B-brightgreen) ![TypeScript](https://img.shields.io/badge/TypeScript-4.0%2B-blue)

Welcome to **Location Timezone Node**! This library provides a simple and efficient way to gather information about capitals, countries, locations (cities), states ANSI (USA), and the timezone of various entities. Whether you need to find the timezone for a specific city, capital, coordinates, country, province, or state, this library has you covered.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Fast and Efficient**: Designed for performance, this library can quickly return information.
- **Wide Coverage**: Supports capitals, cities, states, provinces, and more.
- **Timezone Information**: Get accurate timezone data for any location.
- **TypeScript Support**: Fully typed for better development experience.
- **Easy to Use**: Simple API makes it easy to integrate into your projects.

## Installation

To install the library, run the following command:

```bash
npm install location-timezone-node
```

## Usage

Here’s a quick example of how to use the library:

```javascript
const { getTimezone } = require('location-timezone-node');

const timezone = getTimezone('New York');
console.log(`The timezone of New York is: ${timezone}`);
```

This code snippet retrieves the timezone for New York and prints it to the console.

## API Reference

### `getTimezone(location)`

- **Parameters**: 
  - `location` (string): The name of the city, capital, or coordinates (latitude, longitude).
- **Returns**: 
  - (string): The timezone of the specified location.

### `getCapital(country)`

- **Parameters**: 
  - `country` (string): The name of the country.
- **Returns**: 
  - (string): The capital city of the specified country.

### `getCountry(location)`

- **Parameters**: 
  - `location` (string): The name of the city or coordinates.
- **Returns**: 
  - (string): The country of the specified location.

### `getCoordinates(city)`

- **Parameters**: 
  - `city` (string): The name of the city.
- **Returns**: 
  - (object): An object containing latitude and longitude of the specified city.

## Examples

### Get Timezone of a City

```javascript
const { getTimezone } = require('location-timezone-node');

const timezone = getTimezone('Los Angeles');
console.log(`The timezone of Los Angeles is: ${timezone}`);
```

### Get Capital of a Country

```javascript
const { getCapital } = require('location-timezone-node');

const capital = getCapital('Canada');
console.log(`The capital of Canada is: ${capital}`);
```

### Get Coordinates of a City

```javascript
const { getCoordinates } = require('location-timezone-node');

const coordinates = getCoordinates('Tokyo');
console.log(`The coordinates of Tokyo are: ${JSON.stringify(coordinates)}`);
```

## Contributing

We welcome contributions! If you have suggestions for improvements or want to add features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them.
4. Push your branch and open a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, please visit our [Releases](https://github.com/Safander12/location-timezone-node/releases) section. You can download the latest version and execute it as needed.

To stay updated with the latest changes, check the [Releases](https://github.com/Safander12/location-timezone-node/releases) frequently.

---

Thank you for checking out **Location Timezone Node**! We hope you find this library useful for your projects. If you have any questions or feedback, feel free to reach out. Happy coding!