# Split Bill

Split Bill is a React application for tracking shared expenses with friends. Add friends, record how a bill was paid, and see who owes whom at a glance.

## Features

- Add friends with a name and profile image.
- Select a friend to split a bill with.
- Enter the total bill and your share; the other person's share is calculated automatically.
- Choose who paid and update the balance between you and your friend.
- View whether you owe a friend, they owe you, or the balance is settled.

Friend and balance data is stored in the app's state and is not persisted after the page is reloaded.

## Getting Started

### Prerequisites

- Node.js and npm

### Installation

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm start` runs the app in development mode.
- `npm test` starts the test runner.
- `npm run build` creates an optimized production build in the `build` directory.
- `npm run eject` exposes the Create React App configuration. This is a one-way operation.

## Technology

- React
- Create React App (`react-scripts`)
- CSS
