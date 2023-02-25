# viewMoviesNext
*Abstract* <br>
Fetch movie data from API and show it.<br><br>
*Description*<br>
This web application fetches movie data from the themoviedb.org API using an HTTP request. The response data is then parsed and rendered dynamically on the page. Each movie is displayed as a separate component, and the user can click on any movie component to reveal additional details about the selected movie, such as the synopsis and cast information.  <br>
To achieve this, the application utilizes Next.js, a popular framework for building server-side rendered React applications. The application makes use of server-side rendering to pre-render the movie data and display it as soon as the user visits the page. This results in a faster and more responsive user experience.  <br>
The movie data is fetched using asynchronous JavaScript to prevent the page from blocking while waiting for the response from the API. The data is then processed and transformed into React components, which are then displayed using dynamic client-side rendering.  <br>
To style the application, it utilizes Tailwind CSS, a popular utility-first CSS framework that allows for rapid prototyping and development of responsive web applications.
