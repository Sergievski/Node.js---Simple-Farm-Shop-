Node.js Farm Market Project
This is a simple Node.js project for a farm market website. It uses http module to create a server and read data from a JSON file to render dynamic pages.

Features
Homepage to display all the available products.
Each product has a dedicated product page.
API endpoint to get the JSON data.
Error page for invalid URLs.
Dependencies
fs module
http module
path module
url module
How to run
Clone the repository.
Install dependencies using npm install.
Run the project using node index.js.
Access the website by visiting http://localhost:8000 in a web browser.
Project Structure
data.json - Contains the data about all the products.
index.js - The main file which sets up the server and handles requests.
modules - Contains helper modules for rendering HTML templates.
