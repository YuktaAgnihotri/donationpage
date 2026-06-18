live link - https://yuktaagnihotri.github.io/donationpage/ 

# Donation Website Frontend

A responsive, frontend-only donation portal built with HTML, CSS, and Vanilla JavaScript. This project is designed to be easily integrated with client-side payment gateways like Stripe Checkout or embedded donation widgets.

## Features
- **Responsive Layout:** Optimized for mobile and desktop viewing.
- **Dynamic Amount Selection:** Users can choose predefined amounts (e.g., $10, $50, $100) or enter a custom value.
- **Campaign Selector:** Dropdown to allocate funds to specific charitable causes.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   ```

2. **Configure Payment Settings:**
   - Open `js/main.js` and replace the placeholder API keys with your actual **Stripe Publishable Key** or **PayPal Client ID**.
   - For simple use, you can replace the form action with a standard [PayPal Donate Button](https://paypal.com) or embed code from platforms like [DonorDock](https://www.donordock.com/articles/create-custom-donation-pages-with-donordock).

3. **Run Locally:**
   - Double-click `index.html` to open and test the page in any web browser.

## Technologies Used
- **HTML5**
- **CSS3** (Flexbox/Grid)
- **Vanilla JavaScript** (ES6)
