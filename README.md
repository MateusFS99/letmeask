This is the main repository for the Letme.Ask application, which includes both the backend (`letmeask-api`) and the frontend (`letmeask-ui`) as submodules.

## About 🎯

The Letme.Ask application is designed to help users to ask something about a course, using AI we transcript the room audio end the questions are answered based on this transcription. This repository serves as the main entry point, containing submodules for both the backend and frontend components.

## Structure 📂

- `letmeask-api`: The backend of the Letme.Ask application, developed with Node.js and Fastify, using Google Genai to integrate Gemini AI, Drizzle for ORM and PostgresSQL as the database.
- `letmeask-ui`: The frontend of the Letme.Ask application, developed with React and TypeScript, using Vite for the build tool.

## Features 📝

The application must be able to:

- [✔] Create a new room;
- [✔] Record audio to use as the room content;
- [✔] Make questions to the AI agent;

## Technologies and Installation 🛠 💻

For more details, please refer to the individual repositories: [letmeask-api](https://github.com/MateusFS99/letmeask-api) and [letmeask-ui](https://github.com/MateusFS99/letmeask-ui).

## License ®️

This project is under the MIT license. Consult the [LICENSE](LICENSE) for details.