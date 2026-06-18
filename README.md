# Redditech — A Reddit Browsing App

> Epitech project — B-DEV-501 (B5, *Application Development*)
> Team project.

A **mobile browsing application for Reddit**, built with **React Native**. The project puts the developer in the role of a software architect: selecting and integrating existing libraries, consuming the Reddit API, and delivering a polished, well-tested UX.

## Features

- OAuth2 authentication against the Reddit API
- User profile (picture, username, description)
- Feed of posts from the subreddits the user follows
- Post filtering (best, hot, new, top, …)
- Subreddit search and detail view (subscribers, description, header image)
- Subscribe / unsubscribe to subreddits
- View and update user settings
- Pagination handling (Reddit *listings*)

## Tech stack

- **Framework:** React Native (Android)
- **Build:** Gradle (Gradle Wrapper)
- **API:** Reddit API (OAuth2)

## Build

```sh
cd android && ./gradlew assembleDebug
```

## What I learned

- Consuming a real-world REST API with OAuth2 authentication and pagination
- Building a polished mobile UI following platform guidelines
- Acting as a software architect: integrating libraries rather than reinventing them
- Defining a test strategy and technical documentation
