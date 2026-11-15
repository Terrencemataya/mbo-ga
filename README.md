# mbo-ga

A fresh farm produce marketplace built with React Native and Expo SDK 58.

## Run locally

1. Install Node.js 22.13 or newer.
2. Run `npm install`.
3. Run `npm start`, then scan the QR code with Expo Go or open an emulator.

The current build includes onboarding, produce search and category filters, favourites, a basket with quantity controls, delivery details, cash or mobile-money-on-delivery selection, checkout, order confirmation, and order history. Profile, basket, favourites, and orders are saved on the device (browser local storage on web and the app documents folder on iOS/Android).

## Demo limitations

Sign-in is a local profile form, not account authentication. Products, prices, delivery fees, and order statuses are demo data. Placing an order records it on the current device; it does not send the order to a farm or delivery service. Payment selections are instructions for payment on delivery; no payment is processed. A backend and payment provider are needed for live commerce.
