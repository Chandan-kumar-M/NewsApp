# NewsApp

NewsApp is a MERN stack-based web application that aggregates news articles from various countries and categories, providing users with a comprehensive and personalized news browsing experience. The application features both light and dark modes to enhance readability in different environments.

## Features

- **Global News Coverage**: Fetches and displays news from multiple countries, keeping users informed about international events.
- **Category Filtering**: Allows users to browse news articles by sections such as Entertainment, Sports, and more, catering to diverse interests.
- **Theme Toggle**: Offers light and dark mode options, enabling users to switch themes based on their preference for optimal viewing.
- **Responsive Design**: Ensures a seamless experience across various devices, including desktops, tablets, and mobile phones.

## Technologies Used

- **Frontend**: React.js for building the user interface, with CSS3 for styling.
- **Backend**: Node.js and Express.js for server-side operations.
- **Database**: MongoDB for storing user preferences and other data.
- **External API**: Integration with a news API to fetch real-time news articles.

## Installation

To set up and run NewsApp locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Chandan-kumar-M/NewsApp.git
   cd NewsApp
   ```

2. **Install server dependencies**:

   ```bash
   cd server
   npm install
   ```

3. **Configure environment variables**:

   - Create a `.env` file in the `server` directory with the following content:

     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     NEWS_API_KEY=your_news_api_key
     ```

     Replace `your_mongodb_connection_string` and `your_news_api_key` with your actual MongoDB connection string and news API key, respectively.

4. **Start the backend server**:

   ```bash
   npm start
   ```

5. **Install client dependencies**:

   ```bash
   cd ../client
   npm install
   ```

6. **Start the frontend application**:

   ```bash
   npm start
   ```

   The application should now be running, and you can access it in your browser at `http://localhost:3000`.

## Folder Structure

- **client/**: Contains the React frontend code.
- **server/**: Houses the Express backend code.
- **client/src/components**: Includes reusable React components.
- **client/src/pages**: Contains page-level React components.
- **client/src/styles**: Holds CSS stylesheets.

