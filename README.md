# fCC Forum Leaderboard

This project fetches and displays the latest topics from the freeCodeCamp Forum using asynchronous JavaScript. The leaderboard provides an overview of the latest discussions, including the topic title, category, number of replies, views, and the time of the last activity.

## Features

- Fetches the latest topics from the freeCodeCamp Forum API.
- Displays a list of topics with category information, avatars of contributors, number of replies, view counts, and time since the last activity.
- Uses asynchronous JavaScript with the Fetch API to retrieve and display data dynamically.
- Error handling is implemented using `try...catch` for a smoother user experience.

## Technologies Used

- HTML
- CSS
- JavaScript (Asynchronous JS, Fetch API, Promises, `async/await`)

## How It Works

1. The application fetches the latest topics from the freeCodeCamp Forum API asynchronously.
2. The topics are displayed in a table format with relevant information including topic title, avatars of the users who posted, the number of replies, view count, and how long ago the last activity occurred.
3. Each topic title is a clickable link that leads directly to the discussion on the freeCodeCamp Forum.
4. Error handling ensures that in case of a failure to fetch data, it will be caught and logged in the console for debugging.