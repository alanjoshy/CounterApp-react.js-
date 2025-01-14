# Counter App

A simple counter application built using React and Vite. This app demonstrates the use of React hooks like `useState` and `useEffect`, along with `axios` for API calls to fetch user data dynamically based on the counter value.

## Features

- **Increment/Decrement Counter:**
  - Users can increment or decrement the counter value.
  - Counter values are restricted to a range (1 to 10).

- **Loading, Success, and Error States:**
  - Displays a loading indicator while fetching data.
  - Shows error messages if the API call fails.

## Tech Stack

- **React**: For building the user interface.
- **Vite**: For fast and modern development.
- **Axios**: For making HTTP requests.
- **CSS**: For styling the application.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alanjoshy/counter-app.git
   cd counter-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the app in your browser:
   ```
   http://localhost:5173
   ```

## Folder Structure

```
.
├── src
│   ├── App.jsx       # Main application component
│   ├── components    # Contains reusable components (if any)
│   ├── styles.css    # Application styling
│   └── main.jsx      # Entry point for the app
├── public            # Static assets
├── index.html        # HTML template
├── package.json      # Dependencies and scripts
└── vite.config.js    # Vite configuration
```

## How It Works

1. The counter value is displayed with increment and decrement buttons.
2. When the counter value changes, the app triggers a `useEffect` hook.
3. User information is displayed based on the fetched data.
4. Loading and error states are handled gracefully.



## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the app for production.
- `npm run preview`: Preview the production build.

## Future Improvements

- Add animations for loading and error states.
- Extend functionality to display additional user details.
- Implement local storage to persist the counter value.

## License

This project is licensed under the [MIT License](LICENSE).

---

### Author

- **Your Name** - [GitHub Profile](https://github.com/alanjoshy)

