# Pinterest Clone

This project is a Pinterest clone built using React for the frontend and [Sanity](https://www.sanity.io/) as the headless CMS for managing content. It integrates Google OAuth for authentication and provides features similar to Pinterest, including pin creation, saving, and commenting.

# [Pinterest_Clone](https://pintrest-clone-app.vercel.app/) - Check out the website is LIVE HERE.

## Features

**Google OAuth Integration**: Allows users to log in using their Google account.
- **Pin Creation**: Users can create new pins with images and descriptions.
- **Pin Saving**: Ability to save pins to collections or boards.
- **Commenting**: Users can comment on pins.
- **Responsive Design**: The UI adapts to different screen sizes using responsive techniques.

## Project Structure

- **`/frontend`**: Contains the frontend React application files.
- **`/backend`**: Contains the backend Sanity Studio configuration and schema.

## Technologies Used

### Frontend

- [React](https://reactjs.org/): JavaScript library for building user interfaces.
- [React Router DOM](https://reactrouter.com/): Declarative routing for React.
- [React Icons](https://react-icons.github.io/react-icons/): Icon library for React applications.
- [React Loader Spinner](https://www.npmjs.com/package/react-loader-spinner): Loading spinner component for React.
- [React Masonry CSS](https://www.npmjs.com/package/react-masonry-css): CSS-driven masonry layout for React.

### Backend

- [Sanity](https://www.sanity.io/): Headless CMS used for content management.
- [Styled Components](https://styled-components.com/): CSS-in-JS library for styling React components.

### Authentication

- [@react-oauth/google](https://www.npmjs.com/package/@react-oauth/google): Google OAuth library for authentication.
- [jwt-decode](https://www.npmjs.com/package/jwt-decode): JWT token decoding library.

### Development Tools

- [ESLint](https://eslint.org/): JavaScript linter for code quality.
- [Prettier](https://prettier.io/): Opinionated code formatter.


### Build and Deployment

- [React Scripts](https://create-react-app.dev/docs/available-scripts/): Scripts and configurations for React applications.
- [Sanity](https://www.sanity.io/): Command-line tools for Sanity CMS.

### Other

- [UUID](https://www.npmjs.com/package/uuid): Unique identifier generator.


## Getting Started

### Install the dependencies:
`npm install`

### Start the frontend:
`npm start`
Open http://localhost:3000 to view the frontend app in your browser.

### Navigate to the backend directory:
`cd ../backend`

###Install Sanity CLI globally (if not already installed):
npm install -g @sanity/cli

### Install Sanity dependencies:
`npm install`

### Start Sanity Studio:
`sanity start`


### Prerequisites

- Node.js and npm installed on your machine.

### Frontend Setup

### 1. Clone the repository:

   ```bash
   git clone https://github.com/jatinjangra001/Pinterest_Clone.git
   cd Pinterest_Clone
```

### 2. Environment Variables

Create a `.env` file in the `frontend` directory and add the following environment variables:

```plaintext
REACT_APP_GOOGLE_API_TOKEN=<your_google_api_token>
REACT_APP_SANITY_TOKEN=<your_sanity_token>
REACT_APP_SANITY_PROJECT_ID=<your_sanity_project_id>
```
### Instructions:
#### 1. Google API Token:
Obtain your Google API token from the Google Developer Console.
Replace <your_google_api_token> with your actual token.

#### 2. Sanity Token and Project ID:
Obtain your Sanity API token and project ID from your Sanity project dashboard.
Replace <your_sanity_token> and <your_sanity_project_id> with your actual values.
Note: Never share actual API tokens or sensitive information in public repositories. Always keep your environment variables secure and private.

## Dependencies

#### Core Dependencies

```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-router-dom": "^6.21.0",
  "react-icons": "^4.12.0",
  "react-loader-spinner": "^6.1.4",
  "react-masonry-css": "^1.0.16",
  "web-vitals": "^2.1.4"
},

{

  "@react-oauth/google": "^0.12.1",
  "jwt-decode": "^4.0.0"
},


{
  "@sanity/client": "^6.10.0",
  "@sanity/image-url": "^1.0.2",
  "@sanity/vision": "^3.23.1",
  "styled-components": "^6.0.7"
},



{
  "@sanity/eslint-config-studio": "^3.0.1",
  "@types/react": "^18.0.25",
  "eslint": "^8.6.0",
  "prettier": "^3.0.2"
}



