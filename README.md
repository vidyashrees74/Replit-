# Recipe Remixer

Recipe Remixer is a web app that adapts recipes based on a user’s chosen constraint, such as vegan, kid-friendly, 30-minute, or halve it. It returns a rewritten recipe plus a short summary of what changed.

## Features

- Paste in any recipe.
- Choose a constraint like vegan, kid-friendly, 30-minute, Gluten free or type any of your choice. 
- Get back an adapted recipe.
- See a short “what changed” summary.
- Also you can toggle between metric and imperial units.

## Live Demo

[Open the live app] https://recipe-remix-engine--vidyashrees07.replit.app

## How It Works

1. Paste a recipe into the text box.
2. Enter a constraint or choose one from the options.
3. Click the remix button.
4. Read the adapted recipe and the changes summary.
5. Optionally toggle the metric/imperial units

## Tech Stack

- Replit
- HTML / CSS / JavaScript or your chosen framework
- LLM API for recipe rewriting

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/vidyashrees74/Replit-
cd Recipe Remixer
```

## Prompt Used

### First prompt
Build a Recipe Remixer web app that takes a input as a recipe and a user constraint, then returns an adapted recipe and a short summary of what changed.

### Final prompt
Help me build an app called "Recipe Remixer". It should have a textarea for my input that would be a original recipe, and a dropdown for constraints (like vegan, halve it, 30-minute, kid-friendly), a remix button, and an output area that shows the adapted recipe according to the constraint provided and a short ‘what changed’ summary at the end. Use a backend route that calls an LLM API. Include basic error handling and loading states.

make sure to handle the exceptions for example if a recipe cannot be adapted, give a suitable reason and suggest alternatives.

### additional prompts
-- can you add 2 more constraints in the drop down- Protein rich and second one gluten free.

-- "Custom Constraint" option that lets you type in your own dietary rule or cooking challenge. yes, do this. Also, Add a metric/imperial toggle to my Recipe Remixer app.The app should let the user switch the adapted recipe between metric and imperial units with a button or switch.(only when opted Please implement this in the existing UI, update the ingredient display when the toggle changes, and keep the recipe steps readable.
Use simple approximate conversions for common cooking units like grams, kilograms, milliliters, liters, ounces, pounds, tablespoons, teaspoons, and cups. If an ingredient cannot be converted safely, leave it unchanged and show it clearly. Please also add a small label that shows the current unit system and make sure the app still works if the recipe contains mixed units. Keep the code simple and add basic error handling.

## What I Would Improve Next

- Add more accurate ingredient conversion. (for example unit conversion in baking recipes)
- Support saving past recipe remixes.(also print recipes)
- Add better styling and mobile responsiveness.
- Polish UI better for smooth experience
- Add more tools which helps users experiment their favourite recipes and see if it is possible or   not

## Notes

This project was built and deployed on Replit and then published as a public GitHub repository.
