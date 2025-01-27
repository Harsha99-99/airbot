# AirBot App

This project is a web application built using Streamlit that allows users to get flight information along with weather details. The app integrates APIs to fetch flight schedules and real-time weather data, providing a seamless experience for users interested in travel and meteorological updates.

## Features

- **Flight Search**: Enter source and destination cities to find flight schedules.
- **Weather Updates**: Retrieve real-time weather data for the departure and arrival cities.
- **API Integration**: Uses flight and weather APIs for accurate and up-to-date information.
- **User-Friendly Interface**: Interactive Streamlit UI for a smooth user experience.

## Tech Stack

- **Frontend**: Streamlit (Python-based framework for building web apps)
- **APIs**:
  - Flight information API
  - Weather API
- **Backend**: Python for API integration and data processing

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flight-weather-app.git
   cd flight-weather-app
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your API keys:
   - Replace placeholders in the code with your actual API keys for the flight and weather APIs.

5. Run the app:
   ```bash
   streamlit run app.py
   ```

6. Open the app in your browser. It typically runs at `http://localhost:8501/`.

## Usage

1. Open the app and enter the following details:
   - **Source City**: The city you are departing from.
   - **Destination City**: The city you are traveling to.
2. Click on the "Search" button to fetch flight details and weather information.
3. View the results displayed on the app.

## File Structure

```
flight-weather-app/
├── app.py                 # Main application file
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── .gitignore             # Git ignore file
```

## Requirements

- Python 3.7+
- Streamlit
- Requests
- API keys for flight and weather data (ensure valid subscriptions to the respective services)

## Future Enhancements

- Add support for more APIs (e.g., hotel or car rental services).
- Include a map visualization for flight routes.
- Cache data for faster repeated queries.
- Expand to support multiple languages.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Streamlit Documentation](https://docs.streamlit.io/)
- [Flight API Provider](https://docs.flightapi.io/)
- [Weather API Provider](https://www.weatherapi.com/docs/)

