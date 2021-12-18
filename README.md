# Forkify

Provide recipes.  
You can search recipes, and bookmark it.  
Whenever you access this site, you can check bookmarked recipes.

## MVC Architecture

### Model

- implemented functions that load recipes, search results, etc.
- used current state variable showed on current page

### View

- implemented views which users can interact with
- used View class as a parent class for rendering, and updating

### Controller

- implemented controller which connects between model and view
- handling events from user interface side by using functions implemented in model
