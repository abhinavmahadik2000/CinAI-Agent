# CineAI-Agent

CineAI-Agent is an AI-powered backend service designed to interact with movie databases and provide intelligent recommendations, search, and analysis features for cinematic content.

## Features

- Connects to MongoDB for data storage and retrieval
- Integrates with TMDB (The Movie Database) API for movie data
- Utilizes Gemini AI for advanced recommendations and analysis
- Secure environment variable management

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- MongoDB instance (local or remote)
- TMDB API Key
- Gemini API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/CineAI-Agent.git
   cd CineAI-Agent
   ```

2. **Install dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `backend` directory:
   ```
   MONGO_URL="mongodb://localhost:27017"
   DB_NAME="your_database_name"
   TMDB_API_KEY="your_tmdb_api_key"
   GEMINI_API_KEY="your_gemini_api_key"
   ```

### Running the Backend

```bash
npm start
```

The backend will start on the configured port (default: 3000).

## Project Structure

```
CineAI-Agent/
├── backend/
│   ├── .env
│   ├── src/
│   ├── package.json
│   └── ...
├── .gitignore
└── README.md
```

## Security

- **Never share your `.env` file or API keys publicly.**
- `.env` is included in `.gitignore` to prevent accidental commits.

## License

[MIT](LICENSE)

---

*For more information, see the source code or contact the maintainer.*
