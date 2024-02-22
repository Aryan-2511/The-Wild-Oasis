# The Wild Oasis - Hotel Management Application

Welcome to The Wild Oasis, an Hotel Management System that empowers administrators and authenticated users to efficiently manage and track all the bookings within the hotel. This application enables you to seamlessly add, update, delete, and create new cabins, as well as modify hotel settings. Additionally, it provides features to sort cabins and bookings conveniently. The system also facilitates updating and deleting bookings, performing check-ins and check-outs, and offers an insightful dashboard complete with charts to visualize data.

## Technologies and Packages Used

- **React**: A popular JavaScript library for building user interfaces.

- **Supabase**: An open-source alternative to Firebase that provides real-time and secure database services.

- **React-Query**: A Powerful asynchronous state management for TS/JS, React, Solid, Vue and Svelte

- **Styled-Components**: A CSS-in-JS library for styling React components.

- **React-Hot-Toast**: A toast notification library for React applications.

- **React-Error-Boundary**: A package for implementing error boundaries in React components.

- **Recharts**: A charting library for React that allows you to create beautiful and responsive charts.

## Features

1. **User Authentication and Signup:**

   1. Hotel employees can log in to the application to perform tasks.
   2. New users can only be signed up within the application to ensure that only actual hotel employees can create accounts.

2. **User Profile Management:**

   1. Users can upload an avatar to personalize their profile.
   2. Users can change their name and password.

3. **Cabin Management:**

   1. The app provides a table view with all cabins.
   2. The table view displays cabin information, including cabin photo, name, capacity, price, and current discount.
   3. Users can update or delete existing cabins.
   4. Users can create new cabins, including the ability to upload a photo.

4. **Booking Management:**

   1. The app provides a table view with all bookings.
   2. The table view displays booking information, including arrival and departure dates, booking status, paid amount, cabin details, and guest data.
   3. Booking status can be "unconfirmed," "checked in," or "checked out."
   4. The table view is filterable by booking status.
   5. Additional booking data includes the number of guests, number of nights, guest observations, and whether breakfast was booked and its price.

5. **Booking Operations:**

   1. Users can delete, check in, or check out a booking as the guest arrives.
   2. On check-in, users can accept payment outside the app and then confirm the payment within the app.
   3. Guests can add breakfast for the entire stay during check-in if they haven't already.

6. **Guest Data Management:**

   1. Guest data contains full name, email, national ID, nationality, and a country flag for easy identification.

7. **Dashboard:**

   1. The initial app screen serves as a dashboard displaying important information for the last 7, 30, or 90 days.
   2. It shows a list of guests checking in and out on the current day, and users can perform tasks related to these activities from the dashboard.
   3. The dashboard provides statistics on recent bookings, sales, check-ins, and occupancy rates.
   4. It includes a chart showing all daily hotel sales, distinguishing between "total" sales and "extras" sales (only breakfast at present).
   5. There's also a chart displaying statistics on stay durations, an important metric for the hotel.

## Screenshots

![App Screenshot](https://raw.githubusercontent.com/yaredow/the-wild-oasis/main/public/screenshots/login.PNG)

![App Screenshot](https://raw.githubusercontent.com/yaredow/the-wild-oasis/main/public/screenshots/dasboard-dark.PNG)

![App Screenshot](https://raw.githubusercontent.com/yaredow/the-wild-oasis/main/public/screenshots/booking.PNG)

## Installation

Make sure you have node installed on you system.

Install the-wild-oasis with npm

1-)To install the node modules once you are in the root directory of the project use:

```bash
  npm install
```

2-)To install vite run:

```bash
 npm install vite
```

3-)To run the project:

```bash
  npm run dev
```

## Login

Use the following credentials to Login

Email: demo@example.com

Password: qwertyuiop
