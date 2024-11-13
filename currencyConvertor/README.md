# Currency Converter

A currency converter application built with React and Vite. This app allows users to input a currency and displays the converted value in another currency. It is designed with reusable components and custom hooks for modularity and maintainability.

## Features

- **Real-Time Currency Conversion**: Convert between different currencies using up-to-date exchange rates.
- **Reusable Components**: Designed with reusable components to maintain consistency and reduce duplication.
- **Custom Hooks**: Simplifies logic for API requests and state management.
- **Responsive UI**: Optimized to work on both desktop and mobile screens.

## Technologies Used

- **React** with **Vite** for a fast development environment
- **Custom Hooks** for shared logic
- **API Integration** for live currency rates
- **CSS Modules** or **Styled Components** (if applicable)

## Installation and Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/vishaldangwal/CurrencyConvertor.git
    cd currencyConvertor
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Start the development server**:
    ```bash
    npm run dev
    ```

4. **Visit** the app in your browser at `http://localhost:3000`.

## Project Structure

```plaintext
currencyConvertor/
├── public/                # Static assets
├── src/
│   ├── components/        # Reusable components
│   ├── hooks/             # Custom hooks for logic separation
│   ├── pages/             # Main pages and route handling
│   ├── App.jsx            # Root component
│   └── main.jsx           # Entry point
└── README.md


Usage
Select a base currency and enter the amount you wish to convert.
Choose a target currency to view the converted amount.
Custom Hooks
useCurrencyConverter: Handles API requests and manages exchange rate data.
useInputHandler: Manages the state for input fields.
API Integration
The app fetches real-time currency exchange rates from an external API, ensuring accuracy in conversions.

Contributing
Contributions are welcome! If you want to improve or add features, please fork the repository, make your changes, and submit a pull request.
