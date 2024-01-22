# README for "My Dictionary"

## Project Overview
This project, titled "My Dictionary," is a web-based application designed for learning and managing English vocabulary. The application allows users to search for words, view detailed definitions and examples, and manage their vocabulary list.

### Key Features
- **Word Search Functionality**: Users can search for English words, and if the word is not in the database, it redirects to a detail page for new word entry.
- **Word Detail View**: Displays detailed information about words including definitions and usage examples, retrieved using an external API.
- **Vocabulary Management**: Users can save new words along with their definitions into the database and delete them as needed.
- **Example Sentences**: Functionality to add and view example sentences for each word to understand the context of usage.
- **Responsive Design**: The application is styled using Bootstrap and custom CSS for a responsive layout and an engaging user interface.

### Technology Stack
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Python, Flask
- **Database**: MongoDB
- **External API**: Owlbot Dictionary API for fetching word definitions and examples
- **Hosting**: The application uses an AWS MongoDB instance for database management.

### Setup and Installation
1. **Clone the Repository**: Get the project files from the source repository.
2. **Install Dependencies**: Install necessary Python packages including Flask, pymongo, and requests.
3. **Database Configuration**: Configure MongoDB with the provided AWS IP, username, and password.
4. **Running the Application**: Start the Flask server by executing `app.py`.
5. **Accessing the Application**: Open a web browser and navigate to the local server address (usually `localhost:5000`).

### Usage
- **Searching for Words**: Use the search function to find or add new words to the database.
- **Viewing Word Details**: Click on words to view their definitions, examples, and related details.
- **Managing Vocabulary**: Add new words and their meanings to your personal vocabulary list, and delete them as needed.
