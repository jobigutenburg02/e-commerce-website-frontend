# My E-Commerce Website - Frontend

This is the **frontend** part of a full-stack e-commerce website, built using **React** and **Vite**. It provides a fast, responsive, and modern user interface for browsing products, adding them to cart, and placing orders.

## Before Getting Started

Visit [my backend repo](https://github.com/jobigutenburg02/e-commerce-website-backend/) and follow the steps mentioned in the repo. Then you can proceed with the following steps for running the frontend code.

## Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/jobigutenburg02/e-commerce-website-frontend.git
```

### 2. Navigate into the project directory

```bash
cd e-commerce-website-frontend
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```
### 5. Open your browser and go to [http://localhost:5173](http://localhost:5173)

## Payment Gateway Testing

### Flutterwave

Follow these steps to test payments using Flutterwave's sandbox environment:

- Log in to your Flutterwave account and go to [Flutterwave Dashboard](https://dashboard.flutterwave.com)
- Toggle to **Test Mode** (top-right corner)
- Navigate to **Settings > API** to get your secret key
- Configure the settings.py file at the main project directory ('shoppit') in backend

```bash
FLUTTERWAVE_SECRET_KEY=your_secret_key
```
- Replace 'your_secret_key' with your secret key

### PayPal

Follow these steps to test payments using PayPal's sandbox environment

- Log in to your PayPal account and go to [PayPal Developer Dashboard](https://developer.paypal.com/)
- Get both client ID and secret key from **Apps & Credentials** section
- Navigate to **Testing Tools > Sandbox Accounts**
- Create a personal account for testing
- Configure the settings.py file at the main project directory ('shoppit') in backend

```bash
PAYPAL_MODE=sandbox
PAYPAL_CLIENT_ID=your_sandbox_client_id
PAYPAL_SECRET=your_sandbox_secret
```
- Replace 'your_sandbox_client_id' with your client ID and 'your_sandbox_secret' with your secret key

## Support

For support and questions:
- Create an issue in the repository
- Contact: jbros2513@gmail.com
