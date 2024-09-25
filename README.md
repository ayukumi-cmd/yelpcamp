# **YelpCamp**

YelpCamp is a full-stack web application for campground reviews. Users can browse, create, and review campgrounds. This project was built as part of the Colt Steele Full Stack Web Developer Bootcamp, and focuses on essential web development skills using Node.js, Express, MongoDB, and Passport.js.

---

## **Features**

- 🔍 **Campground Listings**: View all campgrounds with descriptions, images, and locations.
- ✍️ **Campground Reviews**: Users can leave reviews and ratings for campgrounds.
- 🔐 **User Authentication**: Secure authentication using Passport.js for registration, login, and logout.
- 🛡️ **User Authorization**: Users can only edit or delete campgrounds and reviews they’ve created.
- 🗺️ **Map Integration**: Campground locations are visualized with a map powered by Mapbox.
- 📱 **Responsive Design**: Fully responsive for mobile, tablet, and desktop users.


---

## **Technologies Used**

### **Backend**:
- Node.js
- Express.js
- MongoDB & Mongoose (Database)
- Passport.js (Authentication)

### **Frontend**:
- EJS (Embedded JavaScript Templates)
- Bootstrap 5 (Styling)
- Mapbox (Interactive Maps)

---

## **Installation**

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash  
   git clone https://github.com/ayukumi-cmd/yelpcamp.git
   cd yelp-camp
2. Install dependencies:
    npm install
3. Configure environment variables:
Create a .env file in the root directory and add the following variables:
```bash 
DATABASE_URL=<your MongoDB URL>
CLOUDINARY_CLOUD_NAME=<your Cloudinary cloud name>
CLOUDINARY_KEY=<your Cloudinary API key>
CLOUDINARY_SECRET=<your Cloudinary API secret>
MAPBOX_TOKEN=<your Mapbox token>
```

4.Run the application locally:
```bash
    npm start
```



Usage
Register/Login: Sign up for an account or log in.
---
Create a Campground: Users can create campgrounds with name, price, location, image, and description.
---
Add Reviews: Leave a review with a rating for campgrounds.
---
Edit/Delete Campgrounds: Users can only edit or delete campgrounds they created.
---
Mapbox Integration: View campground locations on an interactive map.
---
---
Future Enhancements:
Add pagination for campgrounds.
---
Implement user profiles with activity history.
---
Improve campground filtering by location and price.


