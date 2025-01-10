# KoinX Backend Internship Assignment

This project is a backend service developed for the **KoinX Backend Internship Assignment** using **Node.js** and **MongoDB**. It fetches real-time cryptocurrency data (Bitcoin, Matic, Ethereum) from the **CoinGecko API** and stores it in the MongoDB database. The service also provides APIs to fetch the latest cryptocurrency data and calculate the price deviation over historical records.

## Key Features
- **Background Job**: Fetches data (current price, market cap, and 24-hour change percentage) for Bitcoin, Matic, and Ethereum every 2 hours and stores it in a MongoDB database.
- **API `/stats`**: Provides the latest data (price, market cap, and 24-hour change) for the requested cryptocurrency.
- **API `/deviation`**: Calculates and returns the standard deviation of the price for the requested cryptocurrency based on the last 100 records stored in the database.

## Technologies Used
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **API Integration**: CoinGecko API

