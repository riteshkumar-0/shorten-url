```markdown
# URL Shortener

## Overview
This project is a **URL Shortener** built using **Node.js**, **Express.js**, and **MongoDB**. It allows users to generate short URLs for long links, track usage, and manage shortened URLs.

## Features
- Generate **short URLs** for long links.
- Redirect users to the original URL when accessing the short link.
- Store shortened URLs in **MongoDB**.
- Track **click counts** and analytics.
- API endpoints for URL management.

## Technologies Used
- **Node.js**
- **Express.js**
- **MongoDB** with Mongoose ORM
- **Shortid** for unique URL generation
- **dotenv** for environment variables

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/url-shortener.git
   ```
2. Navigate to the project directory:
   ```sh
   cd url-shortener
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up **.env** file with MongoDB URI and other configs:
   ```sh
   MONGO_URI=your_mongodb_connection_string
   BASE_URL=http://localhost:5000
   ```

## Usage

### Start the Server
```sh
npm start
```

### API Endpoints
- **POST /shorten** - Shortens a given URL
- **GET /:shortId** - Redirects to the original URL
- **GET /analytics/:shortId** - Fetch analytics of a short URL

## License
This project is licensed under the **MIT License**.
```

