# React Coding Interview - Book Search


## Objective

Build a React application that allows users to search for books using the Google Books API and displays the search results in a user-friendly way.

<br />

## API documentation

For this exercise, you'll interact with Google Books API. In particular, we'll use the endpoint to get a list of books.

Documentation:
- https://developers.google.com/books/docs/v1/reference/volumes/list


Example request:
```
GET https://www.googleapis.com/books/v1/volumes?q=harry%20potter
```

<br />

## Requirements

Core functionality - Functionality to search books & display a list of books:

- Your app should include a search form that allows users to search books by title.
- When the user submits the form, fetch data from the Google Books API (based on the entered title), and display a list of books from the API response (for each book, display the title, author, and cover image).
- Handle loading and error states.

<br />

Enhancements (Bonus Points)
- Allow clicking on a book to view more details (e.g., description, published date).
- For the list of books, implement pagination or infinite scrolling.
- Add a "Favorite" feature that allows users to save books locally (e.g., using localStorage).
- Use a UI library like Material-UI or TailwindCSS for styling.

<br />

## Technical Constraints

- Use React (functional components & hooks).
- For data fetching, you can use Axios, Fetch or Tanstack Query.
- Follow good coding practices (clean code, modular components).

<br />

## How to submit

- Fork and clone this repo
- Once you have completed the assignment, push your code to your forked repository and share the link with us

<br />

## Evaluation Criteria

- Completeness of functionality, according to the given requirements.
- Code clarity and structure.
- Use of React best practices.
- API integration and error handling.
- User experience and UI presentation.

