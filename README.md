# Eat-Da-Burger

## Node Express Handlebars Assignment

### Functionality
Using an home-grown ORM, the app has 4 basic CRUD functions...

- CREATE a new burger using the "Submit" form, which... * hits a /burger/create route in Express to insert a new burger into the MySQL database * re-routes the webpage back to the index, where the burger is now ready to be eaten column (via Handlebars)
- READ all entries from the MySQL database and display them to the DOM using Handlebars.
- UPDATE a selected burger by clicking "Devour It", which... * hits an /burgers/:id update route in Express to change its "devoured" status in the MySQL database * re-routes the webpage back to the index, where the burger is now in the devoured column (via Handlebars)
- DELETE a selected burger by clicking "Cancel Order, which... * hits an /burgers/:id delete route in Express to delete from MySQL database (via Handlebars)

## Tech used
- Node.js
- MySQL
- Express 
- Express Handlebars
- jQuery
- JavaScript
- CSS
- HTML

- node server to run server locally.
- Used local application on port 8080 URL: `http://localhost:8080/`

## Heroku
[Eat-Da-Burger link](https://powerful-journey-83255.herokuapp.com/)

## Author

* **Lori Berti** - [Lori Berti](https://github.com/lberti92)
