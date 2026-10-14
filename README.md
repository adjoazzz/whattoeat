# What's Eat

A meal planner. You sign up, tell it when you eat and what you eat, and it builds your week. Shuffle the plan, swap any meal, add new ones, and generate a market list.

## Run it

It's a single static page. Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Status

- Sign-up and Google sign-in are placeholders. Nothing is verified on a server yet.
- Progress is saved in the browser with localStorage.
- Surprise me picks a random Ghanaian dish, drops it into a random open slot this week, and links to a real recipe.
- Themes: Plain (original grid), Meadow, Dusk, Sunrise, Lagoon. The map themes have animals that wander past.

## Next

- Add Supabase for email and Google authentication.
- Store meal times, meals and plans in Supabase tables so they follow the account.
