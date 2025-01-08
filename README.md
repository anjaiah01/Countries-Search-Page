# Countries Search Page  

This project is a simple web application where users can search for countries and view relevant details like their flag, name, and population. The application fetches data from a public API and dynamically displays the results based on the user's input.  

## Features  
- Fetches country data from the [Countries API](https://apis.ccbp.in/countries-data).  
- Displays a loader while fetching data.  
- Dynamically renders country details (flag, name, population).  
- Filters country data based on user input.  

## Concepts Learned  
During this challenge, the following concepts were explored and implemented:  

1. **Fetching Data from an API**:  
   - Learned how to use the `fetch()` method to make HTTP GET requests to retrieve data from an API.  
   - Parsed JSON responses using the `.json()` method.  

2. **Dynamic HTML Elements Creation**:  
   - Used JavaScript to create and append HTML elements dynamically.  
   - Learned how to structure content programmatically.  

3. **Handling User Input**:  
   - Captured user input from an HTML input element.  
   - Filtered the fetched data based on the input value.  

4. **Bootstrap Integration**:  
   - Used the Bootstrap spinner component to show a loader while data is being fetched.  

5. **Efficient DOM Manipulation**:  
   - Updated the DOM efficiently by clearing old elements before appending new ones.  

## How It Works  
1. When the page loads:  
   - A loader spinner is displayed.  
   - A `fetch` request is made to the API: `https://apis.ccbp.in/countries-data`.  
   - On a successful response, country data is dynamically rendered on the page.  

2. When the user types in the search bar:  
   - The input value is used to filter the country data.  
   - Filtered results are dynamically displayed.  

## Technologies Used  
- **HTML**: For structuring the webpage.  
- **CSS**: For styling the elements (with the help of Bootstrap).  
- **JavaScript**: For making API requests, handling user input, and DOM manipulation.  
- **Bootstrap**: For the spinner component and styling.  
