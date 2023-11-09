# Book Library Application

This application is a simple book library management system built using Node.js, Express, and MongoDB.

## Live Demo

You can access the live application at [https://local-library-production-107a.up.railway.app](https://local-library-production-107a.up.railway.app)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- Express
- MongoDB

### Installation

1. Clone the repository:

```bash
git clone https://github.com/hussein-saad/Local-Library.git
```

2. Navigate into the project directory:

```bash
cd Local-Library
```

3. Install the dependencies:
```bash
npm install
```

4. Create a .env file in the root of your project and add your MongoDB connection string:
```
MONGODB_URI=mongodb+srv://username:password@cluster0.mongodb.net/?retryWrites=true&w=majority
```

5. Start the application:
```bash
npm start
```

## Deployment

To deploy this application, you need to set the MONGODB_URI environment variable in your production environment. The method to do this depends on your hosting provider.


# Acknowledgments

This project was inspired by and built upon the [Local Library project](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website) from the [Mozilla Developer Network (MDN)](https://developer.mozilla.org/). We would like to express our gratitude to MDN for providing such a comprehensive and educational example.