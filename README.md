# JS Interview: Search Suggestions Component

## Project Overview
The client wants to create a powerful search component. He provided us examples from LinkedIn.

This component will allow users to search users of organizations.

## Requirements
1. **Dropdown with Popular Suggestions**:
    - When the user clicks on the search input, a dropdown list should display popular suggestions (assume these come from the API).

2. **Live Suggestions Based on User Input**:
    - As the user types in the search input, fetch and display suggestions that match the input.

3. **No Results Handling**:
    - If there are no results for a given search query, display a "See all results" option that navigates to an extended search page.

4. **Clear Search Input**:
    - The input should have a clear button to allow users to quickly reset the field.

5. **Navigation**:
    - When the user clicks on a suggestion, they should be navigated to the relevant page for that suggestion.

6. **Dropdown Dismissal**:
    - The suggestions dropdown should close automatically if the user clicks outside of it.

## Instructions
### 1. **Create a technical design of your solution.**
   First, you'll need to outline a **technical design** for how you would implement the search suggestions component. We need to present this vision to client.

### 2. **Create a POC for search component.**
   You will now need to implement the search suggestions feature using **Vanilla JS**. You are given an HTML structure with an input field, clear button, and an empty `<ul id="suggestions">` element to populate with search results.

1. **Fetch Default Suggestions from API**:
    You can use this endpoint to fetch default users list https://jsonplaceholder.typicode.com/users?_limit=10 or just mock api calls =).

2. **Update Suggestions List**:
    - Display the fetched suggestions as `<li>` elements within the `<ul id="suggestions">` list.
    - Clear previous suggestions from the list each time new results are fetched.
    - If no suggestions are found, add a "No results found" message or similar.

3. **Clear Functionality**:
    - Implement the clear button to reset the search input and hide the suggestions list when clicked.


## NOTES: 
1. Use Vanilla JS/TS.
2. You can use any IDE.
3. You can "google", if you need some documentation.
4. Ask questions if needed.
5. Do not rush to finish all the tasks. Focus on quality =)






