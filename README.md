# travel-booking-platform
# WanderNest

WanderNest is a full-stack vacation rental listing web app inspired by Airbnb. Users can browse stays, search by destination, create their own listings, upload property images, and leave reviews.

## Features

- User signup, login, and logout
- Create, edit, and delete property listings
- Upload listing images with Cloudinary
- Add and delete reviews with ratings
- Search listings by country or location
- Filter listings by category
- Authentication and authorization using Passport.js
- Flash messages for success and error handling
- Server-side validation using Joi

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS / EJS-Mate
- Passport.js
- Cloudinary
- Multer
- Joi
- Bootstrap / custom CSS

## Project Structure

```bash
WanderNest/
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── app.js
├── middleware.js
├── cloudConfig.js
└── schema.js

Installation

1. Clone the repository
git clone <your-repo-link>
cd WanderNest

2. Install dependencies
npm install

3. Create a .env file in the root directory and add:
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_map_token
SECRET=your_session_secret
ATLASDB_URL=your_mongodb_connection_string

4. Start MongoDB locally

5. Run the project
node app.js

6. Open in browser
http://localhost:8080/listings
