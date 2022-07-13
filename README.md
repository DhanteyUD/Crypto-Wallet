# React Custom Hooks

`Custom Hooks` are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated.

- [x] Hooks are reusable functions.

> When you have component logic that needs to be used by multiple components, we can extract that logic to a `custom Hook`.

- [x] Custom Hooks start with **"use".** Example: `useFetch.`

## Build a Hook

In the code below, we are fetching data in our `Home` component and displaying it.

We will use the <a href="https://jsonplaceholder.typicode.com/">JSONPlaceholder</a> service to fetch fake data. This service is great for testing applications when there is no existing data.

To learn more, check out the <a href="https://www.w3schools.com/js/js_api_fetch.asp">JavaScript Fetch API</a> section.

Use the JSONPlaceholder service to fetch fake "todo" items and display the titles on the page:
