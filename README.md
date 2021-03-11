# forkify

An online recipe book

## User Stories

- As a user, I want to search for recipes, so that I can find new ideas for meals.

- As a user, I want to be able to update the number of servings, so that I can cook a meal for a different number of people

- As a user, I want to bookmark recipes, so that I can review them later

- As a user, I want to be able to create my own recipes, so that I have them all organized in the same app

- As a user, I want to be able to see my bookmarks and own recipes when I leave the app and come back later, so that I can close the app safely after cooking

## Features

- Search for recipes

  - Search functionality: input field to send request to API with searched keywords
  - Display results with pagination
  - Display recipe with cooking time, servings and ingredients

- Update the number of servings

  - Change servings functionality: update all ingredients according to current number of servings

- Bookmark recipes

  - Bookmarking functionality: display list of all bookmarked recipes

- Create my own recipes

  - User can upload own recipes
  - User recipes will automatically be bookmarked
  - User can only see their own recipes, not recipes from other users

- See my bookmarks and own recipes when I leave the app and come back later
  - Store bookmark data in the browser using local storage
  - On page load, read saved bookmarks from local storage and display.

## Information Architecture

![flowchart](forkify-flowchart-part-1.png)
