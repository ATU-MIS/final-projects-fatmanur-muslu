# Expiry Tracker

Expiry Tracker is a web application that helps you keep track of the expiration dates of your items. It allows you to scan barcodes to automatically retrieve item information and set expiration dates.

## Features

* Barcode scanning using the device's camera
* Manual item addition with custom name, comments, and expiry date
* Firebase authentication for user login/logout
* MongoDB for storing user data
* Integration with Open Food Facts API to retrieve item information
* Responsive design for mobile and desktop

## Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/ATU-MIS/final-projects-fatmanur-muslu.git](https://github.com/ATU-MIS/final-projects-fatmanur-muslu.git)
    ```

2.  Navigate to the project directory:
    ```bash
    cd final-projects-fatmanur-muslu
    ```

3.  Install dependencies:
    ```bash
    npm install
    ```

4.  Create a Firebase project and enable Firebase Authentication and Firestore.

5.  Configure Firebase credentials in the project (see instructions below).

6.  Start the development server:
    ```bash
    npm start
    ```

7.  Open the application in your browser at `http://localhost:3000`

## Firebase Configuration

To configure Firebase credentials, create a `.env` file in the root directory of the project and add the following variables from your firebase project settings page:

```env
APIKEY='XXX'
AUTHDOMAIN='XXX'
PROJECTID='XXX'
STORAGEBUCKET='XXX'
MESSAGINGSENDERID='XXX'
APPID='XXX'
MEASUREMENTID='XXX'
