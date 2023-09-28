# Problem

In this challenge, we want to assess your front-end development skills by building an app that allows users to explore Pokémon by type.

The initial screen should contain cards of all the Pokémon types (electric, ground, grass, etc.). If the user clicks on a card, it should navigate to the `pokemon-type/:type` route and show all Pokémon from that type with pagination, with 10 items per page.

## Essential information:

- The API documentation is on https://pokeapi.co/docs/v2.  You’ll find detailed information about how to fetch data on Pokémon, including endpoints, request parameters, and data structure. 
- To get all the Pokémon from the electric type, for example, we would make a request to https://pokeapi.co/api/v2/type/electric
- Hint: to get all the Pokémon types, you need to look under the Resource Lists/Pagination section

# Guidelines

- It should use Angular or React Native (according to the job description)
- It must contain instructions on how to run the code
- It should look good
- It should work
- The initial screen should display all the Pokémon types
- Clicking on a type should navigate to the `pokemon-type/:type` route
- The list of Pokémon of a given type should have pagination and show 10 items per page
- Automated tests are a bonus
- Any CSS framework can be used

__*If you're developing with Angular:*__
- It should use RxJs
- Using NgRx is a bonus

# Time reference

We expect this challenge to take you around 120 minutes. This is a time reference so you can infer the level of polish we expect from your solution. Of course, feel free to spend as much time on it as you wish.

# Delivery

You should open a public git repository for us to clone your project and review the code.

# Interview

We will review the solution live in the interview and you’ll have the opportunity to explain things in the project you find the most interesting. Be prepared to discuss your code and design decisions, difficulties, and how you tested your application.
