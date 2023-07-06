# Home Service Application

## About
With the Home Service application, users can easily find and book various services for their home needs. The application provides a platform where sellers can register their services, customers can browse and book services, and admins can manage the service listings and reviews.

## Registration and Authorization
- Users can register as customers or sellers.
- User registration should include name, gender, age, email, password, and role (seller or customer).
- Users can log in with their email and password.
- Email confirmation is required for user accounts.
- After 5 incorrect login attempts, the user's account should be disabled for 5 minutes.
- The admin role will be added by default.

## Customer Dashboard
Customers will have access to the following features:
- View all available services.
- Sort available services based on date.
- Search services by category.
- View detailed information about a specific service.
- Book a service.
- Rate and review a service.
- Make payments using Stripe.
- View ongoing services.
- View completed services.

## Admin Dashboard
Admins will have access to the following features:
- Manage categories for services.
- Add new service categories.
- Delete service categories.
- View newly added services.
- Approve or reject newly added services.
- Provide a reason for rejecting a service.
- View a list of approved services.
- View a list of rejected services.
- Review and approve rejected services.

## Seller Dashboard
Sellers will have access to the following features:
- View all of their own services.
- Each service will display its status (pending, approved, or rejected).
- In case of rejection, sellers can resolve admin comments and request re-approval.
- Register new services.
- View reviews submitted for their services.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
