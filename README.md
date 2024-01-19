# URL Shortener 🚀

This is a simple URL shortener project built using Node.js, Express, and MongoDB. It allows users to shorten long URLs into concise, shareable links.

## Getting Started 🏁

To run the project locally, follow these steps:

1. Install dependencies:

    ```bash
    npm install
    ```

2. Start the server:

    ```bash
    node app.js
    ```

By default, the server runs on port 3000. You can access the application at [http://localhost:3000](http://localhost:3000).

## Features 🌟

- **Shorten URLs:** Enter a long URL, and the system generates a unique short link for easy sharing.
- **Statistics:** The homepage displays the total number of short links created.
- **Redirect:** Accessing a short link (`/r/:code`) redirects to the original URL.

## Dependencies 📦

- **Express:** Fast, unopinionated, minimalist web framework for Node.js.
- **Mongoose:** Elegant MongoDB object modeling for Node.js.
- **body-parser:** Node.js body parsing middleware.
- **ejs-locals:** EJS template engine for Express.
- **valid-url:** URL validation library.
- **random:** Library for generating random strings.

## Configuration ⚙️

Make sure to set up your MongoDB connection URI in a `keys.js` file.

```javascript
// keys.js
module.exports = {
  mongoURI: 'YOUR_MONGODB_CONNECTION_URI',
};
```

## Usage 🚀
- Access the homepage to view statistics.
- Shorten a URL by submitting it through the provided form.

## Contributing 🤝
- Contributions are welcome! Feel free to open issues or submit pull requests.
