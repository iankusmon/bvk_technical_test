# Buana Varia Komputama Technical Test
to list all IMDB top movies and profiling the users.

## Overview

The app manages movies for users.
Each user can have multiple movies. Each movie can have multiple ratings. The movie ratings obtained from IMDB API.

- movies are generated automatically via a cron job that is run every 7 days. (rake task: generate_movies)
- movie can have 3 statuses: NEW_RELEASE, OLD, & SPECIAL.
- movie can also store the value of ratings with scale 1-10.
- Relevant methods/controller actions on user:
  - edit
  - show
- Use the `seeds.rb` file to create some users.

# Development

Ruby version: 3.0.0

Rails version: 7.0.4

Node version: 15.14

## The UI

- There is some UI which helps manage all the data.

## Running locally

- Make sure you have correct versions of ruby, node and bundler installed.
- Run `make setup` to configure the project
- After that you can run `make start`
- You should be able to open `http://localhost:3000` and play around with the app

You can see `Makefile` and copy-paste commands from it manually too.

At this point consider initiating a new `git` repository and making an initial commit. Please, as you go about implementing the exercise, commit to git as you would normally do as if you were working on a PR.

## Documentation

TBA

