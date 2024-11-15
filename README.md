https://github.com/sniegockajulia/Netflix-2.0

## Practice Description
In the second part of this activity, a new functionality will be added that allows the application to connect with The Movie Database (TMDb) API to search for movies and work with external data. This section will help students understand how to interact with REST APIs, how to send and receive HTTP requests, and how to integrate data from external sources into their web applications. Additionally, students will learn to manage API key security and implement advanced features that enhance the user experience. 

This second part of the exercise will allow students to work with HTTP requests, process responses in JSON format, and learn how to effectively integrate external data. It will also provide an opportunity to handle errors and exceptions in API requests and learn how to design a more robust and complete user experience. Upon completing this part of the exercise, students will have an application with significantly expanded functionality, capable of connecting to external services to enrich the available information and improve user interaction.

## Tasks

Implement the Search View: Create a new searchView() that includes a text field and a search button. Ensure the interface is clear and user-friendly, and that the view handles cases where no valid search terms are entered.
Add the Search Functionality: Implement the searchContr(query) controller to connect with the TMDb API and retrieve results. Handle network and API errors appropriately, and provide clear messages to the user if no results are found or technical issues arise.
Display Search Results: Create the resultsView(results) to display the movies found in the API. The view should be attractive and allow easy navigation of the results, with relevant information and clear buttons to add the movies to the local database.
Add Movies to the Local Database: Implement the addFromAPIContr(movie) controller to allow users to add a movie from the results to the local database. Ensure data is validated before adding, avoid duplicates, and confirm the operation's success to the user.
Update the Router: Add the necessary new actions to the router to handle the new buttons and events, ensuring that the search and movie addition functionalities are well-integrated into the overall application flow.

