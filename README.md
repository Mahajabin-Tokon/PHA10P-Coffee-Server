# Coffee Store Server

## Description

The Coffee Store Server is designed to manage the backend operations for a coffee store application. It connects to a MongoDB database to perform CRUD operations and expose endpoints for managing coffee inventory. Middleware like CORS and dotenv are used to ensure seamless and secure server functionality.

## Packages Used

- **[Express](https://www.npmjs.com/package/express)**: Web framework for building the server.
- **[MongoDB](https://www.npmjs.com/package/mongodb)**: Database driver for connecting to MongoDB.
- **[dotenv](https://www.npmjs.com/package/dotenv)**: For managing environment variables.
- **[cors](https://www.npmjs.com/package/cors)**: Middleware for enabling CORS.

## Key Features

1. **CRUD Operations**
   - Fetch all coffee items.
   - Fetch a specific coffee item by ID.
   - Add new coffee items.
   - Update existing coffee items.
   - Delete coffee items.

2. **Secure Database Connectivity**
   - Uses MongoDB for data storage, with connection details securely managed via environment variables.

3. **RESTful API Design**
   - Endpoints follow RESTful conventions, ensuring a clean and predictable interface for client-side integration.

4. **Middleware for Enhanced Functionality**
   - CORS for handling cross-origin requests.
   - Body parser for JSON payloads.

5. **Easy Deployment**
   - Configured for deployment using Vercel with routes defined for various HTTP methods.

6. **Scalable Architecture**
   - Modular and scalable setup using Express.js, enabling easy addition of new features and endpoints.

## Installation

To set up the server locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coffee-store-server.git
