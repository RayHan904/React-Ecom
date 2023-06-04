# E-Commerce Project Readme

This project is an e-commerce website developed using React.js, Redux, Redux Saga, Stripe Integration and Firebase. It aims to provide a seamless shopping experience for users and includes features like product listing, cart management, user authentication, and order processing.

## Project Structure

The project follows a typical React.js project structure, with additional directories for Redux-related files and Firebase configuration. Here's a brief overview of the key directories and files:

- **src**: Contains the main source code for the project.
  - **components**: Holds the reusable components used throughout the application.
  - **pages**: Includes the main page components for different routes.
  - **redux**: Contains Redux-related files, such as actions, reducers, and sagas.
  - **firebase**: Includes Firebase configuration and utility files for authentication and database management.
  - **styles**: Holds the CSS and styling files for the project.
  - **App.js**: The entry point of the application where the routes and main components are defined.
  - **index.js**: The main entry point of the application where React is rendered.

## Prerequisites

To run the project locally, you need to have the following software installed:

- Node.js: [Download and Install Node.js](https://nodejs.org/en/download/)
- Firebase: Create a Firebase project and obtain the necessary configuration values.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone this repository: `git clone https://github.com/your-username/ecommerce-project.git`
2. Navigate to the project directory: `cd ecommerce-project`
3. Install the dependencies: `npm install`
4. Create a Firebase project and obtain the configuration values.
5. Replace the placeholder values in the `firebase/firebase.utils.js` file with your Firebase configuration.
6. Run the development server: `npm start`
7. Open your web browser and visit `http://localhost:3000` to see the application.

## Features

- User authentication: Allows users to sign up, sign in, and sign out.
- Product listing: Displays a list of products with details like name, price, and image.
- Cart management: Users can add items to the cart, update quantities, and remove items.
- Order processing: Users can place orders and view their order history.
- Firebase integration: Uses Firebase authentication for user management and Firestore for data storage.

## Technologies Used

The project utilizes the following technologies and libraries:

- [React.js](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Redux](https://redux.js.org/): A predictable state container for managing application state.
- [Redux Saga](https://redux-saga.js.org/): A library for managing side effects in Redux applications.
- [Firebase](https://firebase.google.com/): A platform for building web and mobile applications.
- Stripe: A technology company that provides tools for online payment processing.

## Screen Shots

### Home Page
![Home Page](https://github.com/RayHan904/React-Ecom/assets/54216177/3a2b1939-1009-479c-b4ac-cc9f2fa778b5)

### Catelog (by Category)

![Catelog by Category](https://github.com/RayHan904/React-Ecom/assets/54216177/2ff3209a-aba4-4926-a3ed-183f67b53437)


### Login/Sign up Page

![Login or Signup page](https://github.com/RayHan904/React-Ecom/assets/54216177/85e05954-d5cc-42d1-a7d5-80394da7842c)


### Cart 

![Cart](https://github.com/RayHan904/React-Ecom/assets/54216177/20d56a21-4d94-49a2-a290-d2d3a1319a20)



## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your needs.

## Acknowledgements

This project was inspired by various e-commerce platforms and built as a learning exercise. Many thanks to the open-source community and the authors of the libraries used in this project.

## Contact

For any further questions or inquiries, please contact the project maintainer:

- Name: Mohammed Rehan Ali
- Email: dev.rayhan98@gmail.com
