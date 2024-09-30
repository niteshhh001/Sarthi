Here's a sample `README.md` file for your "Sarthi" project that you can use in your GitHub repository:

---

# Sarthi

**Sarthi** is an interactive AI-powered assistant designed to help users with various tasks such as suggesting places for road trips, summarizing concepts, brainstorming team activities, and what not. It uses a dynamic search interface and is built with **React** and **Vite**.

## Features

- **Interactive Search:** Users can click on predefined cards to prompt search queries or type their own prompts.
- **Real-time Results:** Results are displayed based on the prompt entered, with a loading state while data is fetched.
- **Development Features:**
  - **Image Search**: Coming soon.
  - **Voice Input**: Coming soon.
- **Responsive UI**: The interface is optimized for a seamless experience across devices.

## Project Structure

```plaintext
├── public
│   ├── assets
│   └── index.html
├── src
│   ├── assets
│   ├── components
│   │   └── Main.jsx
│   ├── context
│   │   └── context.js
│   ├── styles
│   │   └── Main.css
│   └── App.jsx
├── .env
├── .gitignore
├── README.md
└── package.json
```

## Getting Started

### Prerequisites

- Node.js
- Vite
- React

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sarthi.git
   ```
2. Install dependencies:
   ```bash
   cd sarthi
   npm install
   ```

3. Set up your environment variables:
   Create a `.env` file in the root of the project and add the following line:
   ```bash
   REACT_APP_SARTHI_API_KEY=your_api_key_here
   ```

### Running the Project

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Previews the production build.

## Usage

Once the app is running, you can:
- Enter your queries in the search box.
- Click on the preset cards to prompt a query.
- Receive results in real-time.

## Future Enhancements

- **Gallery Search**: Add a feature to search for images.
- **Voice Input**: Allow users to input prompts using voice.
- **Expanded Card Functionality**: More default queries for users to click on.

## Contributing

Contributions are welcome! Please submit a pull request with a clear description of the changes made.

## License

This project is licensed under the MIT License.

---

Feel free to modify this as needed for your project!
