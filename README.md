

### README.md

```markdown
# Dynamic Form React Application

## Overview

This project is a dynamic event registration form built with React. The form allows users to input their details and choose whether they are attending the event with a guest. Depending on their selection, the form dynamically adjusts to include additional input fields.

## Features

- **Dynamic Form:** The form adjusts based on user input (e.g., adding fields for guest information if attending with a guest).
- **Validation:** The form includes basic validation for required fields and proper email format.
- **Styling:** The form is styled to be visually appealing and user-friendly.

## Folder Structure


dynamic-form/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   └── EventRegistrationForm.js
│   │   └── EventRegistrationForm.css
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/dynamic-form.git
   cd dynamic-form
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Usage

To use the form, simply enter your details in the provided fields. If you select "Yes" for attending with a guest, additional fields for the guest's information will appear. Submit the form to see a success message with the entered details.

## Components

### EventRegistrationForm

This component handles the form rendering, state management, and validation.

#### Props

- None

#### State

- `formData`: An object containing the form data.
- `errors`: An object containing the form validation errors.

### CSS Styling

The form is styled using CSS to ensure it is user-friendly and visually appealing. The styles are located in `EventRegistrationForm.css`.

## Deployment

1. Build the project for production:

   ```bash
   npm run build
   ```

2. Deploy the `build` folder to your preferred hosting service (e.g., Netlify, Vercel).

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

This `README.md` file includes all necessary details about your project, from installation and usage to contributing guidelines and contact information. Make sure to replace `https://github.com/amankumar94728/dynamic-form.git` with the actual URL of your GitHub repositor
