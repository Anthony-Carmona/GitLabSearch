# GitLab Search

This project is a React component designed to search for projects on GitLab using the GitLab GraphQL API. It allows users to input search parameters and view the search results, including project names, descriptions, creation dates, full paths, archival status, and project members.

## Setup Instructions

1. **Install Dependencies:**
   - Ensure you have Node.js and npm installed on your machine.
   - Run `npm install` to install all necessary dependencies.

2. **API Token:**
   - Replace the placeholder token (`glpat-PoBNDC2_T6fyGTyjj4Dp`) with your GitLab personal access token. This token is used for authentication to access the GitLab GraphQL API.

3. **Run the Application:**
   - Execute `npm start` to run the application.
   - The application will launch, allowing you to search for GitLab projects.

## Usage

- **Search Projects:**
  - Input search parameters into the search bar.
  - Click on the "Search" button to retrieve the projects matching the search criteria.

- **View Search Results:**
  - Results will be displayed in a table format.
  - Each row represents a GitLab project and includes details such as name, description, creation date, full path, archival status, and project members.

- **Pagination:**
  - If there are more than 20 results, a "See more" button will appear at the bottom of the page.
  - Clicking this button will load additional results.

## Note

- This project utilizes the Apollo Client for interacting with the GitLab GraphQL API.
- Ensure proper handling of sensitive information, especially when dealing with authentication tokens.
- Make sure to adhere to GitLab's API usage guidelines to avoid rate limiting or other restrictions.

Feel free to reach out for any questions or assistance!
