# TM Recipes

A phone web app that makes any recipe with AI and turns it into a Thermomix recipe.

## What it does

- Type a dish idea, paste a recipe, or add a screenshot of a food video.
- AI writes a normal UK recipe (metric, UK ingredients, UK swaps where products differ).
- A second AI step converts it into Thermomix steps with time, temperature, speed, reverse and accessories.
- Steps the machine can't do (oven, crisping) are marked "Off the machine".
- Recipes are saved on your phone. Copy buttons give the title, ingredients and steps ready to paste into Cookidoo Created Recipes.
- "Change something" updates a recipe and converts it again.

## Set up on your phone

1. Open the app link in Safari.
2. Tap Share, then "Add to Home Screen".
3. Open it, tap Settings, paste your Anthropic API key, pick your Thermomix model.

## Privacy

- The API key is saved only in your phone's browser. It is never in this repo.
- Set a monthly spend limit on the key in the Anthropic Console.

## Files

- `index.html`: the whole app, including both AI prompts.
- `manifest.json`, `icon-*.png`: home screen icon and name.
