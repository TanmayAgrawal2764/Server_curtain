```markdown
# MERN Stack Backend with Node.js and Express.js of Air Curtain Application live at : https://pss24j-5173.csb.app

This is the backend part of a MERN (MongoDB, Express, React, Node.js) stack application, built using Node.js and Express for a robust RESTful API, utilizing AWS SDK for database interactions.

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Environment Variables](#environment-variables)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

Ensure you have the following installed:

- Node.js (version 14.x or above)
- npm or yarn
- AWS account and appropriate AWS SDK configurations

### Clone the Repository

```bash
git clone https://github.com/yourusername/mern-vite-react-backend.git
cd mern-vite-react-backend
```

### Install Dependencies

Using npm:

```bash
npm install
```

Using yarn:

```bash
yarn install
```

## Running the Application

### Setup Environment Variables

Create a `.env` file in the root of the project and add the following:

```
PORT=5000
AWS_ACCESS_KEY_ID=your_aws_access_key_id
AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
AWS_REGION=your_aws_region
JWT_SECRET=your_jwt_secret
```

### Start the Development Server

Using npm:

```bash
npm run dev
```

Using yarn:

```bash
yarn dev
```

The server will start on `http://localhost:5000`.

## Project Structure

```plaintext
mern-vite-react-backend
├── config
│   └── awsConfig.js
├── controllers
│   └── userController.js
├── middleware
│   └── authMiddleware.js
├── models
│   └── userModel.js
├── routes
│   └── userRoutes.js
├── utils
│   └── errorHandler.js
├── .gitignore
├── package.json
├── README.md
├── server.js
└── .env
```

- **config/**: Contains AWS configuration file.
- **controllers/**: Contains functions to handle requests and responses.
- **middleware/**: Contains middleware functions for authentication and other purposes.
- **models/**: Contains data models (if applicable).
- **routes/**: Contains route definitions.
- **utils/**: Contains utility functions.
- **server.js**: The entry point for the server.

## Available Scripts

In the project directory, you can run:

### `npm run dev` or `yarn dev`

Runs the app in the development mode.
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

### `npm run start` or `yarn start`

Runs the app in production mode.

## Environment Variables

The application requires the following environment variables to be set:

- `PORT`: The port on which the server runs.
- `AWS_ACCESS_KEY_ID`: Your AWS access key ID.
- `AWS_SECRET_ACCESS_KEY`: Your AWS secret access key.
- `AWS_REGION`: The AWS region.
- `JWT_SECRET`: The secret key for JWT.

## Dependencies

- **express**: "^4.x"
- **aws-sdk**: "^2.x"
- **jsonwebtoken**: "^8.x"
- **dotenv**: "^10.x"

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.
```
