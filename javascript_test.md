# JavaScript test

- Repository: `javascript-test` (should be private!)
- Type of Challenge: `Consolidation`
- Duration: `4 hours`
- Deployment strategy : `Netlify`
- Team challenge : `solo`

You decide to host a cocktail party during holidays.
There's only one minor problem: you don't have the slightest idea on how to create them.
Time to solve your problem with your freshly acquired JavaScript skills!

## Deliverables

Your readme in your repository should contain a link to the live result.

> 💡 Start way before the deadline to put things online to avoid last-minute stress.

## What do we look for?

This test is designed to assess your current JavaScript level, evolution and insight in coding.

### Don't ❌
- Don't stress about having a perfect solution at once (we're not looking for missing comma's, we want an overview of your progress!).
- Throw your solution away just before the deadline if it doesn't work. Bits and pieces are always better than nothing (and more interesting to analyse as coach).
- Rush to finish. Make the most of the time you have: if you finish early, are there any parts you can improve?
- No need to spend a lot of time on styling. The focus is JavaScript.
- Be stuck forever on one step. Skip one if you need to, and try the next one.
- Communicate with the rest of the group. This is a test, after all!

### Do ✅
- Ask questions instead of making assumptions.
- Work step by step, every reached milestone is one.
- Think about your git usage.
- Consider what techniques you can use, and which one you prefer for a specific purpose.
- Take a short break when you need it. (this is an official test, so please remain seated)
- Look back at everything you've learned so far!
- Use Stackoverflow, previous exercises, ...

## Time to get started

> Note: This is a brief project and a simple structure is sufficient.
> There's no need to use specific tools or compilers.

### Step 1

Generate buttons (using JS, not in html), each one with a different color. They all represent a drink:
- Hugo €5
- Martini €7
- Margarita €7
- Manhattan €9
- Earl Grey tea €2
- Herbal tea €2
- Ginger ale €3
- Lemonade €3

### Step 2

Every button should be clickable by the user.
Depending on the drink that was picked, you show `not a cocktail` or `a cocktail` in the console.

### Step 3

When the user clicks a drink, there's a couple of options.
Prepare a `div` that will get different content depending on the result

#### The drink is a soft drink

Show the text `Just pour the drink, and you're ready to go!`.

#### The drink is a tea

Show the steps to make tea:
- Put the kettle on
- Get a teaspoon of tea in your cup
- Pour the water and wait for a couple of minutes
- Enjoy the perfect tea!

#### The drink is a cocktail

Show a picture and instructions to make it.
Use the following API to get this information: `https://www.thecocktaildb.com/api/json/v1/1/search.php?s=yourSearchTerm`

### Step 4

Keep track of every drink that was clicked in a list in the HTML.
Bonus: show the total price of the full list.

### Bonus: step 5

Make the info of the drinks easy to update: it should all be in JS in a way that's easy to edit.
Tip: one separate file only containing the info seems like a good choice.