# Currency Converter App

A simple yet powerful currency converter application that provides real-time exchange rates using the [CurrencyAPI](https://currencyapi.com/).

## Features

- Real-time exchange rates from CurrencyAPI
- Convert between all major world currencies
- Clean, responsive interface
- Quick currency swap functionality
- Automatic rate updates
- Displays last updated timestamp
- Mobile-friendly design

## Live Demo

Try the live version here:  
[https://developersolutions.netlify.app/currency-convertor](https://developersolutions.netlify.app/currency-convertor)

## Installation

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/kdippan/Developer-Solutions.git
```

2. Navigate to the project directory:
```bash
cd Developer-Solutions/currency-convertor
```

3. Open `index.html` in your browser

## API Key Note

This project uses a free API key from CurrencyAPI. If you encounter rate limit issues:

1. Get your own free API key from [CurrencyAPI](https://currencyapi.com/)
2. Replace the API key in `script.js`:
```javascript
const apiKey = 'YOUR_NEW_API_KEY';
```

## Project Structure

```
currency-convertor/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- CurrencyAPI

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or feedback, please open an issue on GitHub.
