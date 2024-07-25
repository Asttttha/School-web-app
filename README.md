# School website

## Getting Started

To get started with the application, follow the instructions below to set up the project on your local machine.

### Prerequisites

**Install**
- **Node.js**: [Download and install Node.js](https://nodejs.org/).
- **npm**: Comes with Node.js installation.

### Clone the Repository

First, clone the repository to your local machine using Git:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the actual URL of the repository.

### Navigate to the Project Directory

Change your working directory to the project folder:

```bash
cd path-to-project
```

## Installation

### Install Project Dependencies

Run the following command to install all required packages:


```bash
npm install react-slick slick-carousel react-select react-router-dom react-icons aos
```

These packages are essential for implementing carousels, animations, icons, and routing functionality in the application.

## Running the Application

To run the application in development mode, use the following command:

```bash
npm start
```

This command will start the development server and open the application in your default web browser at `http://localhost:3000`.

## Features

The Web application offers the following features:

- **Responsive Design**: Built with Tailwind CSS for a mobile-friendly and responsive user interface.
- **Animated Transitions**: Smooth transitions and animations powered by AOS.
- **Interactive Components**: Carousels, dropdowns, and interactive buttons enhance user experience.
- **Modular Architecture**: Clear separation of components for easier maintenance and scalability.
- **Accessibility**: Throughout the development project, accessibility was tested using the browser's inspect tool.

## Packages Used

Here are the key packages used in this project:

| Package            | Description                                                    |
|--------------------|----------------------------------------------------------------|
| **react-slick**    | Carousel component for displaying slideshows.                  |
| **slick-carousel** | CSS and assets for react-slick carousels.                      |
| **react-select**   | Customizable select dropdowns for various options.             |
| **react-router-dom** | Navigation and routing capabilities for the React application. |
| **react-icons**    | Collection of popular icons for UI components.                 |
| **aos**            | Animations on scroll for enhancing user interaction.           |

## Setup Tailwind CSS

### Install Tailwind CSS

```bash
npm install -D tailwindcss postcss autoprefixer
```

### Generate Tailwind Configuration

```bash
npx tailwindcss init
```

This will create a `tailwind.config.js` file in the root of your project.

### Configure Tailwind CSS

Modify the `tailwind.config.js` file to include the paths to your template files:

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}", // Specify the paths to your source files
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### Import Tailwind CSS

Add the Tailwind CSS imports to your main CSS file (e.g., `src/index.css`):

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Start the Development Server

Run the application to see Tailwind CSS in action:

```bash
npm start
```

#### Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request. You can also open issues for any bugs or feature requests.

