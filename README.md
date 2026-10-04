# Show Finder

A short React + TypeScript exercise. You have about 15 minutes.

## The task

Build a small component that lets a user search TV shows by name, using the public TVMaze API:

```
https://api.tvmaze.com/search/shows?q=<search>
```

- For each result, show the **image**, **name** and **status**.
- The user should always know what's happening: **loading**, **errors** and **no results**.
- Type everything. No `any`.
- Styling is optional. Focus on behavior.

No API key is needed. Feel free to open the API in a browser tab to look at the response, for example [`?q=office`](https://api.tvmaze.com/search/shows?q=office).

## Where to code

Write your code in [`src/ShowFinder.tsx`](src/ShowFinder.tsx). It's already rendered by `src/App.tsx`, and the preview reloads when you save. You can add more files if you like.

Docs and Google are fine. Please think out loud as you go: we care more about your reasoning than about perfect syntax.

## Running it locally (optional)

The exercise runs in the browser, so you don't need to install anything. If you'd rather use your own editor:

```bash
npm install
npm run dev
```

`npm run typecheck` runs the TypeScript compiler.
