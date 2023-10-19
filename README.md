# 🐶Indiana_Bones🐶
# Funny Dog Names Web App

The Funny Dog Names Web App is a simple web application built with Express.js, designed to display funny dog names and collect user-submitted names. This README will provide an overview of the project and instructions on how to set it up and run it on your local machine.

## Project Structure

The project consists of the following components:

- `server.js`: This is the main server script that configures the Express.js server, sets up routes, and listens for incoming requests.

- `routes/home.js` and `routes/funny-name.js`: These files define the routes for the home page and the "funny name" page, respectively. The app displays funny dog names on the home page and allows users to submit new names on the "funny name" page.

- `util/path.js`: This file defines a utility function to determine the root directory of the project.

## Getting Started

Follow these steps to set up and run the Funny Dog Names Web App on your local machine:

### Prerequisites

- Node.js: Ensure that you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/funny-dog-names.git
```

2. Navigate to the project directory:

```bash
cd funny-dog-names
```

3. Install project dependencies:

```bash
npm install
```

### Running the App

1. Start the server:

```bash
npm start
```

2. Open your web browser and visit [http://localhost:3000](http://localhost:3000).

3. You will see the home page displaying funny dog names. Click on "Funny Name" to visit the page where you can submit new funny dog names.

## Dependencies

The project uses the following Node.js packages, which are specified in the `package.json` file:

- [express](https://www.npmjs.com/package/express): A web framework for Node.js that simplifies the development of web applications.

- [body-parser](https://www.npmjs.com/package/body-parser): A middleware for parsing request data, which is essential for handling form submissions.

## License

This project is available under the [ISC License](LICENSE).

## Author

- Alexander