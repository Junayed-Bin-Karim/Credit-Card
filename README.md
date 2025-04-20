# Interactive Credit Card Form

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is a dynamic and visually appealing credit card form built using Vue.js. It provides a real-time preview of the credit card as the user enters information, enhancing the user experience.

## Features

- **Real-time Card Preview:** As you type in the form fields, the credit card displayed above updates in real-time, showing the card number, holder name, expiry date, and CVV (when flipped).
- **Card Type Detection:** Automatically detects the credit card type (Visa, Mastercard, Amex, Discover, Troy) based on the entered card number and displays the corresponding logo.
- **Input Masking:** Uses `vue-the-mask` to format the card number input according to the detected card type (including the specific format for American Express).
- **Smooth Transitions:** Employs Vue.js transitions for a polished and engaging user interface when updating card details and flipping the card to view the CVV.
- **Focus Styling:** Highlights the currently focused input field on the virtual card for better visual feedback.
- **Responsive Design:** The form and card preview are designed to adapt to different screen sizes.
- **Customizable Appearance:** The background of the card can be easily changed (currently randomized on page load).

## Technologies Used

- **Vue.js (v2):** A progressive JavaScript framework for building user interfaces.
- **vue-the-mask:** A Vue.js plugin for input masking.
- **CSS3:** For styling the form and card elements.
- **HTML5:** For the basic structure of the form.

## Setup

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <https://github.com/Junayed-Bin-Karim/Credit-Card.git>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <your-project-directory>
    ```
3.  **Open `index.html` in your web browser.**

   *(This project is a front-end application and doesn't require a backend setup.)*

## Usage

Simply open the `index.html` file in your browser and start filling out the credit card form. Observe how the card preview updates in real-time as you enter the details.

-   **Card Number:** Enter your credit card number. The input will be automatically formatted, and the card type will be detected.
-   **Card Holders:** Enter the name of the cardholder.
-   **Expiration Date:** Select the month and year of expiry.
-   **CVV:** Enter the card verification value. The card will flip to show the back, where the CVV is displayed as asterisks.

## Customization

-   **Card Background:** The `currentCardBackground` in the `data()` section of `main.js` controls the card's background image. You can modify the range or provide a specific number to use a particular image from the `src/assets/images/` directory.
-   **Styling:** The `style.css` file contains all the CSS rules for the form and card. Feel free to modify it to match your desired look and feel.
-   **Card Images:** You can add more card background images to the `src/assets/images/` directory and update the logic in `main.js` to include them.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Author

Md. Junayed Bin Karim

 Student, Daffodil International University

 Email: karim22205101667@diu.edu.bd
