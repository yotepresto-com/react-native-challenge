# React Native Challenge

Thanks for applying to the **Yotepresto Software Engineering team** as a React Native developer. If you solve this challenge successfully, it means that you are a rockstar and we want you to be part of our team!


### The challenge

Your challenge is to build a **movies watchlist**. It's simple:

* The app will have only 1 view, and no need to store any data (all in memory).
* It will have 1 text input and 2 lists of items: the list of movies **to watch** and the list of **watched** movies.
* Each item has the **name** of the movie, a **checkbox** to mark as watched and the movie **poster** (image).
* The app must start empty. No watched movies or to watch.
* When the user adds a new movie title it's added to the "To watch" section.
* If the checkbox if activated, the item moves to the "Watched" section.
* If the checkbox if deactivated, the item moves back to the "To watch" section.
* The movie poster must the requested from the RottenTomatoes API, with the following request: `https://www.rottentomatoes.com/api/private/v1.0/movies.json?q={movie-title}&page_limit=1&page=1` (use the first result given the movie title).
* If no movie matches with the user input, then no image is displayed.


### Deliverables

* A public Github repo with a React Native app working for iOS and Android (DO NOT fork this repo).
* You may use [Expo](https://docs.expo.io/).
* The project must have at least 3 automated tests with [Jest](https://jestjs.io/).


### Rules

* You have exactly two weeks to complete this test and send it back to your recruiter.
* The design of the app must be as similar as possible to the screenshot above.
* You may use any public library.


### Extra points

It is not required but any extra work will speak great of you. For example:

* Adding animations.
* Adding install instructions in the README.
* Any extra function: deleting items, suggesting movie names, caching images, using github actions...

Best of luck!
