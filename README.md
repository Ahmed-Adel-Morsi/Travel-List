# Travel List

A simple travel packing list app built with React. Add items you plan to take, mark them as packed, sort the list, and track how ready you are to travel.

## Features

- Add items with quantity and description
- Mark items as packed or unpacked
- Sort by input order, description, or packed status
- Clear the list and see packing progress stats

## Tech Stack

- React (Create React App)
- CSS

## Getting Started

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm start
```

Build for production:

```bash
npm run build
```

## Deployment (GitHub Pages)

This project is set up to deploy with `gh-pages`.

```bash
npm run deploy
```

## Project Structure

```
src/
	components/
		App.js
		Form.js
		Item.js
		Logo.js
		PackingList.js
		Stats.js
	index.css
	index.js
public/
```

## Scripts

- `npm start` - run dev server
- `npm run build` - production build
- `npm test` - run tests
- `npm run deploy` - deploy to GitHub Pages

## Credits

Created as part of Jonas Schmedtmann's React course while reviewing React fundamentals (components, props, state, events).
