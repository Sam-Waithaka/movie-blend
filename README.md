# Movie-Blend

Movie-Blend is a responsive single-page application built with React and Appwrite. It allows users to browse movies fetched from an external API with pagination, search for specific titles, and view a trending list based on user search activity, simulating a Netflix-like experience.

## Features

- **Movie Browsing**: View a paginated list of movies fetched from an external API.
- **Search Functionality**: Find movies by entering keywords in the search bar.
- **Trending List**: Displays top trending movies based on user searches within the app.
- **Responsive Design**: Ensures optimal viewing experience across various devices.

## Technologies Used

- **Frontend**: React, JavaScript, HTML5, CSS3
- **Backend**: Appwrite
- **External API**: [Specify the movie API used]
- **Version Control**: Git

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- Appwrite instance

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Sam-Waithaka/movie-blend.git
   cd movie-blend
   ```

2. **Install dependencies:**

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

3. **Set up Appwrite:**

   - Ensure you have an Appwrite instance running.
   - Create a new project in Appwrite.
   - Set up necessary databases and collections for storing user searches and trending data.
   - Update the Appwrite endpoint and project ID in your React application.

4. **Configure environment variables:**

   Create a `.env` file in the root directory and add the following:

   ```env
   REACT_APP_API_KEY=your_movie_api_key
   REACT_APP_APPWRITE_ENDPOINT=your_appwrite_endpoint
   REACT_APP_APPWRITE_PROJECT_ID=your_appwrite_project_id
   ```

5. **Start the development server:**

   Using npm:

   ```bash
   npm start
   ```

   Or using yarn:

   ```bash
   yarn start
   ```

   The application will be accessible at [http://localhost:3000](http://localhost:3000).

## Usage

- **Browse Movies**: Navigate through the paginated list to explore different movies.
- **Search**: Use the search bar to find specific movies by title.
- **Trending**: Check the trending section to see the most searched movies by users.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m 'Add feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Appwrite for backend services.
- The Movie Database (TMDb) API for movie data.
- React for the frontend framework.

## Contact

For any questions or suggestions, please contact [developersam.w@gmail.com].
