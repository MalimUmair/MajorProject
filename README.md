# FullStack Wanderlust website: Nodejs, Express, MongoDB, PassportAuth

![alt text](https://github.com/abhisheksharma8630/megaProject/blob/main/Full.png)

This is repository of FullStack website Wanderlust with Nodejs, Expressjs, MongoDB


### Cloning the Repository

```shell
git clone https://github.com/abhisheksharma8630/Wanderlust_MegaProject.git
```

Features:

- Full responsiveness
- Credential authentication
- Google authentication
- Image upload using Cloudinary CDN
- Client form validation 
- Server error handling 
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
    - For example we will filter out properties that have a reservation in your desired date range to travel
- POST and DELETE routes in route handlers

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
SECRET=
CLOUD_NAME=
CLOUD_API_KEY=
LOCATION_API_KEY=
```

### Start the app

```shell
nodemon app.js
```
