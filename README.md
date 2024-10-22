```markdown
# YelpCamp: Create and Review Campgrounds

**YelpCamp** is a website where users can create and review campgrounds. To review or create a campground, you must have an account. This project was part of Colt Steele's Web Development Course on Udemy.

![Image 1](https://github.com/MohammedJawwad/YelpCamp-project/blob/main/screenshots/image1.png)  
![Image 2](https://github.com/MohammedJawwad/YelpCamp-project/blob/main/screenshots/image2.png)

## Features
- **Create, edit, and remove campgrounds**: Users can manage their own campground listings.
- **Review campgrounds**: Users can leave one review per campground, with options to edit or remove their review.
- **User profiles**: Displays detailed user information (full name, email, phone, join date) and their listed campgrounds. Users can also edit their profile or delete their account.
- **Search functionality**: Search campgrounds by name or location.
- **Sorting options**: Sort campgrounds by highest rating, most reviews, lowest price, or highest price.

## Technologies Used
- **Backend**: Node.js, Express
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: MongoDB
- **Authentication**: Passport.js
- **Cloud Storage**: Cloudinary (for image uploads)
- **Maps Integration**: Google Maps / Mapbox

## Installation

### 1. Clone the repository
```bash
git clone git@github.com:MohammedJawwad/YelpCamp-project.git
cd yelpcamp
npm install
```

### 2. Environment Variables
Create a `.env` file in the root directory and add the following:

```bash
DATABASEURL='<your-database-url>'
API_KEY='<your-cloudinary-api-key>'
API_SECRET='<your-cloudinary-api-secret>'
```

### 3. Run the project locally
- Install [MongoDB](https://www.mongodb.com/try/download/community).
- Create a [Cloudinary](https://cloudinary.com/) account to get an API key and secret.
- In one terminal, run MongoDB:
  ```bash
  mongod
  ```
- In another terminal, start the application:
  ```bash
  node app.js
  ```

- Visit `localhost:3000` in your browser.

### 4. Maps Integration
To get Google Maps working, follow the [Google Maps API setup guide](https://developers.google.com/maps/documentation/javascript/get-api-key).

```
