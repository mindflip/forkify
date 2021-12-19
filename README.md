# Forkify

Provide recipes.  
You can search recipes, check it, and bookmark it.  
Whenever you access this site, bookmarked recipes last.

### [DEMO APP](https://forkify-mindflip.netlify.app/)

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

## Functions

- search recipes
- show searched recipes applied pagination
- show clicked recipe
- show ingridients according to the number of servings
- save/load/delete bookmarks
- upload a recipe

---

**ref**  
[Udemy The Complete JavaScript Course](https://www.udemy.com/course/the-complete-javascript-course/)
