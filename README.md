# Show Finder

A short React + TypeScript exercise. You have about 15 minutes.

## The task

Build a component that lets a user search TV shows by name, using the public TVMaze API:

```
https://api.tvmaze.com/search/shows?q=<search>
```

- For each result, show the **image**, **name** and **status**.
- The user should always know what's happening: **loading**, **errors** and **no results**.
- Type everything. No `any`.
- Styling is optional. Focus on behavior.

## Assumptions you can make

- **Search as the user types.** There's no need for a submit button.
- **Empty input:** show a short prompt instead of calling the API.
- **Results:** show what the API returns for the search (at most 10 shows). No pagination.
- **Image:** use the medium-size one.
- **Status:** show it as the API returns it.
- **Scope:** a plain list in a single page is enough. No routing, global state or tests needed.
- **Libraries:** React and `fetch` are all you need. If you'd rather use a library, go ahead and tell us what it does for you.
- **API:** no key needed, and it can be called straight from the browser. Open it in a tab to see the response, for example [`?q=office`](https://api.tvmaze.com/search/shows?q=office).

## How we'll work

- Get something working first, then improve it. If time runs out, tell us what you'd do next.
- Please think out loud: we care more about your reasoning than about perfect syntax.
- **No AI assistants.** That includes ChatGPT, Claude, Copilot, Cursor and the bolt.new assistant in the StackBlitz sidebar. We want to hear *your* reasoning, not an AI's.
- Docs and Google are fine.
- If something still isn't clear, just ask.

## Where to code

1. Write your code in [`src/ShowFinder.tsx`](src/ShowFinder.tsx). It's already rendered by `src/App.tsx`, and the preview updates when you save. You can add more files if you like.
2. Press **Ctrl+S** (**Cmd+S** on Mac) as soon as you start. StackBlitz saves your own copy and the address bar changes to a new URL. Paste that URL in the call chat so your work isn't lost, then keep saving as you go. You don't need an account; you can ignore the "Sign in to save your changes" banner.

## Running it locally (optional)

The exercise runs in the browser, so you don't need to install anything. If you'd rather use your own editor:

```bash
npm install
npm run dev
```

`npm run typecheck` runs the TypeScript compiler.
