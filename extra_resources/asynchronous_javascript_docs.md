# Fetch and Display API Data

**Objective:**  
Use the fetch API to retrieve data from a public API and log the response to the console.

**Steps:**
1. Choose a public API (like the JSONPlaceholder or OpenWeatherMap API).
2. Use `fetch` to send a GET request to the API.
3. Handle the response by converting it to JSON.
4. Log the JSON data to the console.

**Concepts Practiced:**
- Asynchronous programming with fetch
- Working with APIs
- JSON data handling

---

# Timer with Promises

**Objective:**  
Create a timer that counts down from a specified number of seconds using Promises to handle the asynchronous delay.

**Steps:**
1. Write a function that takes a number of seconds as an argument.
2. Use `setTimeout` inside a new Promise to resolve after the specified time.
3. Chain promises to create a countdown effect, decrementing the timer each second.
4. Log the countdown to the console.

**Concepts Practiced:**
- Using Promises
- `setTimeout`
- Asynchronous loops

---

# Dynamic Content Loader

**Objective:**  
Dynamically load content into a webpage without reloading the page, using the fetch API to retrieve content from a server and JavaScript to display it asynchronously.

**Steps:**
1. Create a simple HTML page with a button and a placeholder for content (e.g., a `<div>`).
2. Write a JavaScript function that uses `fetch` to retrieve data from a server or local file (JSON or plain text for simplicity).
3. After retrieving the data, use JavaScript to dynamically insert the content into the placeholder `<div>` when the button is clicked.
4. Ensure error handling is in place to manage any issues with the fetch operation.

**Concepts Practiced:**
- DOM manipulation
- Asynchronous programming with fetch
- Event handling
- Dynamic content update
