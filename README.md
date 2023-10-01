# Camply - A Campground Web Application

**Camply** is a web application inspired by yelp.com, designed to help users discover campgrounds and share their reviews. Users can also contribute by adding their own campgrounds to the platform, creating a community of outdoor enthusiasts. The application features a map for easy campground location discovery, and it implements fuzzy search capabilities using MongoDB Atlas search.

## Deployment

You can access the Camply web application by visiting [https://bikas-camply.herokuapp.com/](https://bikas-camply.herokuapp.com/).

## Key Features

### Authentication

- Users can register and log in to their accounts.
- Passport.js is used for user authentication.

### Authorization

- Users must be logged in to make any changes, such as adding, updating, or deleting campgrounds.
- Users can only modify their own posts and reviews.

### Functionalities

- Campgrounds are displayed on a map using the Mapbox API, providing a visual overview of campground locations.
- Fuzzy search functionality is implemented using MongoDB Atlas search, making it easy to find campgrounds.
- Both client-side and server-side validations are in place to ensure data integrity.
- Images of campgrounds are uploaded to Cloudinary, simplifying the management of visual content.
- Users can add and delete images after creating a campground entry.
- The application supports Create, Read, Update, and Delete (CRUD) operations for campgrounds.
- Flash messages provide user feedback and notifications.
- Sessions and cookies are employed for user sessions and data management.
- Each campground entry displays its location separately on a map.

## Tech Stack

**Front End**

- HTML, CSS, Bootstrap v5.0
- EJS (Embedded JavaScript) and EJS Mate for templating

**Back End**

- Node.js
- Express.js
- MongoDB for data storage
- Cloudinary for image management
- MapBox for mapping services
- Passport (local strategy) for authentication
- JOI for data validation
- Connect-flash for flash messages
- Morgan for request logging
- Helmet for HTTP header security
- mongoSanitize for sanitizing MongoDB input
- sanitizeHtml for HTML sanitization

## Deployment

The application is deployed using Heroku, with the database hosted on MongoDB Atlas.

## Contributing

If you're interested in contributing to Camply, you are welcome to get involved with the project.

Feel free to explore the world of campgrounds and share your experiences with fellow adventurers! 🏕️🌲🌞
