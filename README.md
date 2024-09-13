# AI-Guessing-Game

## Overview
**AI-Guessing-Game** is a C++ application that interacts with an external API to retrieve and provide interesting facts or information about animals. Using the `cpr` library for HTTP requests and the `nlohmann_json` library for JSON parsing, the program retrieves animal-related data from the API, processes it, and outputs the results. The project is modular and can be easily extended for different APIs or response formats.

## Features
- **API Interaction**: Sends HTTP requests to a third-party API to retrieve animal-related data.
- **JSON Parsing**: Efficiently parses JSON responses from the API using the `nlohmann_json` library.
- **Error Handling**: Handles potential API request errors or malformed responses gracefully.
- **Extendable**: The project can be easily extended to interact with different APIs or handle more complex responses.
- **Lightweight**: The project is lightweight and only requires minimal dependencies, making it easy to deploy and run.

## Use Cases
- **Educational Tools**: Can be used to provide facts or information about animals in educational software.
- **Chatbots**: Integrate with a chatbot to allow users to query animal facts in real-time.
- **Automation**: Used in scripts or other applications to automatically retrieve and process animal-related data.

## API Details
The application communicates with a third-party API to fetch animal data:
- **API Endpoint**: (Specify the API endpoint used, e.g., `https://api.example.com/animal-facts`)
- **Request Type**: GET
- **Response Format**: JSON

Example of an API response:
```json
{
    "name": "Elephant",
    "size": "Large",
    "habitat": "Savanna",
    "lifespan": "60-70 years"
}
```
## Requirements
- **C++17** or higher.
- **CMake** 3.10 or higher.
- **cpr** library (for HTTP requests).
- **nlohmann_json** library (for JSON parsing).

## Dependencies
The project uses the following libraries:
- **cpr**: A C++ library for HTTP requests.
- **nlohmann_json**: A C++ library for JSON parsing.

Dependencies are managed using CMake's `FetchContent` module, which automatically downloads and configures the required libraries during the build process.

## Contact

For any questions or suggestions, feel free to reach out to me at [ashakirov@stetson.edu].
