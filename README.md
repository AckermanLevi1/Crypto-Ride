# Crypto-Ride

Crypto-Ride is a blockchain-powered ride-sharing platform aimed at providing decentralized, secure, and transparent services. Users can seamlessly book rides, track routes, and pay for services using cryptocurrencies. This application integrates blockchain technology with real-world ride-hailing services, leveraging smart contracts for trustless transactions.

![Alt text](ss1.gif)

## Tech Stack

- **Frontend**: Next.js
- **Backend**: Node.js, Express.js
- **Cryptocurrency Payment Gateway**: Metamask, Web3.js
- **Database**: Firebase 

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/just-ctrlC-ctrlV/Crypto-Ride.git
   cd Crypto-Ride
2. Install the necessary dependencies:
    ```bash
    npm install
3. Set up environment variables. Create a .env file and add the following variables:
    ```bash
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN
    NEXT_PUBLIC_MAP_STYLE
    NEXT_PUBLIC_FIREBASE_API_KEY
    NEXT_PUBLIC_UBER_ADDRESS
    NEXT_PUBLIC_MAPBOX_DIRECTION_URL
    NEXT_PUBLIC_MAPBOX_GEOCODER_URL
    NEXT_PUBLIC_MAPBOX_TOKEN
4. Run the server:
    ```bash
    npm run dev
5. Access the application on http://localhost:3000.
## Acknowledgements

- Mapbox for location services and Map
- Metamask for blockchain technology
- Firebase for database services