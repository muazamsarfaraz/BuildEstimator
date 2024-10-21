# Construction Cost Calculator

## Description

This project is a web-based Construction Cost Calculator that helps users estimate the cost of building projects. It takes into account various factors such as the type of building, size, location, and additional costs like architect fees and engineering fees.

## Features

- Calculate base construction costs based on building type and size
- Adjust costs based on location
- Include additional costs such as:
  - Architect fees
  - Engineering fees
  - Planning permission fees
  - Building regulation fees
  - Site survey costs
- Responsive design for use on various devices
- Real-time cost updates as users input data

## Technologies Used

- HTML5
- Tailwind CSS for styling
- JavaScript for calculations and dynamic updates

## Setup and Installation

1. Download the Tailwind CSS standalone CLI for Windows from the official Tailwind CSS website:
   https://github.com/tailwindlabs/tailwindcss/releases/latest

2. Extract the `tailwindcss-windows-x64.exe` file and place it in your project root directory.

3. Create a `tailwind.config.js` file in your project root with the following content:
   ```js
   module.exports = {
     content: ["./**/*.{html,js}"],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

4. Create a CSS file named `input.css` in your project root with the following content:
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

5. Open a command prompt in your project directory and run:
   ```
   tailwindcss-windows-x64.exe -i input.css -o output.css --watch
   ```

6. Open `index.html` in your web browser to use the calculator.

## Development

To watch for changes and rebuild the CSS automatically, keep the command from step 5 running in your command prompt.

## Usage

1. Select the type of building from the dropdown menu.
2. Enter the size of the building in square meters.
3. Choose the location of the project.
4. Check any additional costs that apply to your project.
5. The estimated cost will update in real-time as you make selections.

## Contributing

Contributions to improve the calculator are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
