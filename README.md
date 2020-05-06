# InfluencerHouseAssessment

New Clear REACTive App

## Assignment

#### Task
In this programming assessment, you will implement a front-end interface using React that consumes an API. Please read through the entire document before you start.

#### Requirements
Create a single-page React app that lets users interact with the data from one of the following APIs.
  - TMDB (https://www.themoviedb.org/documentation/api)
  - Spotify (https://developer.spotify.com/web-api/)
  - Pokemon (https://pokeapi.co/)
  - Marvel (https://developer.marvel.com/)
  - NASA (https://api.nasa.gov/index.html)

Note that you may need to create an account and/or acquire an API key for some of the APIs.
Additionally, the API you are working with may become temporarily unavailable.
If/when this happens, it doesn't mean you are blocked from working on the assessment.
You can mock the data, i.e. create a local hard coded response and use that instead of making the request.
This is also a good opportunity to think about how your app should handle errors.

Your app should have the following features:
  - **A list view**:  where users can input a search query and the app returns a list of results that match the query (i.e. searching movies or albums). There should also be a way to sort the search results based on different properties of the results (such as the name or rank) and of specifying an ordering (ascending and descending). Also, the search bar should filter as you type. You can sort and filter in the client side.
  - **A gallery view**: that displays some kind of image media from the chosen API (gallery of movie posters). The gallery view should also have some kind filtering attribute where users can select one or many attributes and filter the gallery by them (i.e. genres of films or music).
  -  **A detail view**: When an item in the search view or the gallery view is clicked, the app should display the different attributes of the selected item. Also, this view should have previous and next buttons (can be implemented with arrows) that lets the user cycle through the list of objects.

You will also be required to use following tools:
  - Use React Router for routing.
  - Use Axios for API calls.
  - Use PropTypes. https://facebook.github.io/react/docs/typechecking-with-proptypes.html
  

## Environment Setup Guide
1. Use `Create React App` (CRA) (see below) to generate your starter code in a directory of your choice.
2. CD into that directory and follow the instructions to make a new repository on either GitHub or GitLab. [Guide for GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) or [Guide for GitLab](https://docs.gitlab.com/ee/gitlab-basics/create-project.html#push-to-create-a-new-project).
3. After running `npm start` open a browser and go to `http://localhost:3000/` to view your page.
4. Open up `src/app.js` to start building your first component. Visit https://reactjs.org/docs/getting-started.html for many official, high quality resources to help get you started.

### Create React App
`create-react-app` is a tool that allows you to generate a react starter project that requires no immediate configuration. Visit the [getting started guide](https://facebook.github.io/create-react-app/docs/getting-started) to read more.

You may be wondering how the command `npx create-react-app my-app` works and why there is no installation step. Click [here](https://www.bram.us/2017/07/15/introducing-npx-an-npm-package-runner/) for an explanation of `npx`.
