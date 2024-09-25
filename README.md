YelpCamp is a full-stack web application for campground reviews. It allows users to browse, create, and review campgrounds. Built as part of the Colt Steele Full Stack Web Developer Bootcamp, this project emphasizes fundamental skills in Node.js, Express, MongoDB, and authentication using Passport.js.

Features
Campground Listings: View all campgrounds with descriptions, images, and locations.
Campground Reviews: Users can leave reviews and ratings for campgrounds.
User Authentication: Secure authentication using Passport.js for registration, login, and logout.
User Authorization: Users can only edit or delete campgrounds and reviews they’ve created.
Map Integration: Campground locations are visualized with a map powered by Mapbox.
Responsive Design: Built to be fully responsive for mobile, tablet, and desktop users.
Technologies Used
Backend:

Node.js
Express.js
MongoDB & Mongoose (Database)
Passport.js (Authentication)
Frontend:

EJS (Embedded JavaScript Templates)
Bootstrap 5 (Styling)
Mapbox (Interactive Maps)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/yelp-camp.git
cd yelp-camp
Install dependencies:

bash
Copy code
npm install
Configure environment variables: Create a .env file in the root directory and add the following variables:

bash
Copy code
DATABASE_URL=<your MongoDB URL>
CLOUDINARY_CLOUD_NAME=<your Cloudinary cloud name>
CLOUDINARY_KEY=<your Cloudinary API key>
CLOUDINARY_SECRET=<your Cloudinary API secret>
MAPBOX_TOKEN=<your Mapbox token>
Run the application locally:

bash
Copy code
npm start
Access the app: Open http://localhost:3000 in your browser.

Usage
Register/Login: Sign up for an account or log in.
Create a Campground: Users can create campgrounds with name, price, location, image, and description.
Add Reviews: Leave a review with a rating for campgrounds.
Edit/Delete Campgrounds: Users can only edit or delete campgrounds they created.
Mapbox Integration: View campground locations on an interactive map.

bash
Copy co
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a pull request
Future Enhancements
Add pagination for campgrounds.
Implement user profiles with activity history.
Improve campground filtering by location and price.
