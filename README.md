# Split Bill – React

A React application that helps users track shared expenses with friends and manage balances intuitively.

## Features
- Add and manage friends
- Split bills with dynamic balance updates
- Clear visual feedback for debts and credits
- Clean, component-driven architecture

## Tech Stack
- React (Create React App)
- JavaScript (ES6+)
- Functional components & hooks

## Architecture & Design Decisions
- State is lifted to the App level to ensure a single source of truth
- Business logic is separated from presentation components
- Controlled inputs are used for predictable form behavior
- Immutable state updates ensure reliable re-renders

## Tradeoffs
- Local state is used instead of global state for simplicity
- No persistence layer yet (intentionally scoped)

## Future Improvements
- Persist data with a backend API (Node/Nest)
- Introduce testing with React Testing Library
- Convert to TypeScript for stronger guarantees
- Replace static data with server-driven state

## Running Locally
```bash
npm install
npm start
