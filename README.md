

# Book Library Organizer

This project is a simple web-based book library organizer that allows users to search for books using the Google Books API, filter books by category, and add books to their personal library.  The library data is persisted using local storage.

## Features

*   **Book Search:** Search for books using titles, authors, or keywords via the Google Books API.
*   **Autocomplete Suggestions:** Get suggestions as you type your search query.
*   **Category Filtering:** Filter books by categories like Fiction, Science, and History.
*   **My Library:** Add books to your personal library and view them later.  Library data is saved in your browser's local storage.
*   **Book Details:** Click on a book to see more details, including a description.
*   **Responsive Design:** The layout adapts to different screen sizes.

## Technologies Used

*   HTML
*   CSS
*   JavaScript
*   Google Books API


## What I Learned

This project was a great learning experience for me. Here are some of the key things I learned:

*   **Working with APIs:** I gained valuable experience working with the Google Books API, including making requests, handling responses, and parsing JSON data.  I also learned about API rate limiting and how to make requests more efficiently.
*   **DOM Manipulation:** I practiced manipulating the Document Object Model (DOM) using JavaScript to dynamically update the content of the page, including adding book items, displaying details, and handling user interactions.
*   **Local Storage:** I learned how to use local storage to persist data in the user's browser, which allowed me to create the "My Library" feature.
*   **Event Handling:** I worked with various JavaScript events, such as `onclick`, `oninput`, and others, to make the website interactive.
*   **Responsive Design:**  I practiced creating a responsive design that adapts to different screen sizes using media queries in CSS.
*   **Asynchronous JavaScript:** I became more comfortable working with asynchronous JavaScript, which is essential when making API calls.  I used `fetch` and promises to handle the asynchronous nature of these requests.
*   **Code Structure and Organization:** I focused on writing clean, well-structured, and maintainable code.

## New Things I Learned

While making this project, I encountered a few new challenges and learned some interesting things:

*   **Autocomplete Implementation:** Implementing the autocomplete feature was a new experience. I learned how to filter suggestions based on user input and display them in a dropdown-like manner.
*   **Handling API Rate Limiting:** I learned about the importance of handling API rate limits and implemented a strategy to avoid exceeding the limits by fetching data from the Google Books API one book at a time when displaying the user's library.
*   **Displaying Star Ratings:** Figuring out how to dynamically display star ratings based on the average rating provided by the API was a fun challenge.
*   **Error Handling for APIs:**  I added basic error handling to provide feedback to the user if there are issues fetching data from the API (e.g., if a book in the library is no longer found).

## Future Improvements

*   **Improved Styling:** The styling could be improved to make the website more visually appealing.
*   **More Advanced Search:**  Adding more search filters (e.g., by author, publisher, ISBN) would enhance the search functionality.
*   **User Authentication:** Implementing user authentication would allow users to save their libraries across different devices.
*   **Book Cover Previews:**  Potentially allow users to click on book covers to get a larger preview.
*   **Integration with other APIs:** Explore integration with other book-related APIs for additional features.

This project was a valuable learning experience, and I am excited to continue improving it and exploring new web development techniques.
