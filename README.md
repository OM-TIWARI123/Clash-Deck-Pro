# ClashDeckPro - Clash Royale Deck Builder

ClashDeckPro is an AI-powered Clash Royale deck builder.  Enter your player tag to receive personalized deck recommendations based on your playstyle and statistics.

## Features

* **AI-Driven Deck Generation:**  Generates three different deck types (Aggressive, Control, Speed Cycle) tailored to your playing style.
* **Player Profile Analysis:** Analyzes your Clash Royale stats to understand your strengths and weaknesses, informing deck recommendations.
* **Deck Sharing and Saving:** Easily share your generated decks with friends or save them for later use.
* **Intuitive Interface:** User-friendly design for easy navigation and deck viewing.
* **Offline Functionality (PWA):**  Access key features even without an internet connection.

## Technology Stack

* **Next.js:** React framework for building the user interface.
* **TypeScript:**  For static typing and improved code maintainability.
* **OpenAI API:**  For generating deck recommendations using AI.
* **Clash Royale API:** For fetching player stats and card data (API keys required).
* **Tailwind CSS:**  Utility-first CSS framework for styling.
* **Lucide:**  Icon library.
* **Radix UI:**  Primitive UI components.
* **Service Workers (Next.js PWA):** Enables offline capabilities.

## Prerequisites

* Node.js and npm (or yarn) installed on your system.
* API Keys for both the Clash Royale API and OpenAI API.  These should be configured as environment variables (`NEXT_PUBLIC_API_KEY_1`, `NEXT_PUBLIC_API_KEY_2`, `NEXT_PUBLIC_API_KEY_3`, `NEXT_PUBLIC_API_KEY_4`, `NEXT_PUBLIC_API_BASE_URL`, `NEXT_PUBLIC_API_KEY_OPEN_AI_1`, etc.  See `src/components/deck-builder.tsx` for details).

## Installation

1. Clone the repository:  `git clone https://github.com/ShiwangPande/clash-royal-deck-builder.git`
2. Navigate to the project directory: `cd clash-royal-deck-builder`
3. Install dependencies: `npm install` or `yarn install`
4. Set environment variables (see Prerequisites).  You can use a `.env.local` file in your project root.

## Usage

1. Run the development server: `npm run dev` or `yarn dev`
2. Open your browser and navigate to `http://localhost:3000`.
3. Enter your Clash Royale player tag in the input field.
4. Click the "Generate Decks" button.
5. View your personalized deck recommendations.


## API Documentation

This application uses the Clash Royale API and OpenAI API.  Refer to their respective documentation for details:

* **Clash Royale API:** [Insert Clash Royale API Documentation Link Here if available]
* **OpenAI API:** [https://platform.openai.com/docs/api-reference](https://platform.openai.com/docs/api-reference)

The application's interaction with these APIs is handled within `src/components/deck-builder.tsx`.  The application uses multiple API keys for both services to handle rate limits and potential failures.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

[Specify License Here]


## Contact/Support

For any questions or issues, please contact [Your Contact Information Here].
