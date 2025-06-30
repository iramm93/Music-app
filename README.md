Music Library Micro Frontend

This is a modular music application developed using a micro frontend architecture. It features a primary application that loads an independent music library component and incorporates role-based authentication to manage access.
Music Library Micro Frontend


Features
Micro frontend structure utilizing Vite Module Federation
Two user roles:
Admin: able to add and delete songs
User: restricted to viewing, searching, and sorting songs
Song list equipped with filtering, sorting, and reset functionalities
Basic in-memory login system (no backend)

Tech Stack:
React
- Vite
- JavaScript / TypeScript
- Tailwind CSS for styling
- Module Federation plugin (@originjs/vite-plugin-federation)
- Deployed with Netlify or Vercel

To run the app:
cd main-app
npm install
npm run dev

For the music library
cd ../music-library
npm install
npm run dev


Features
Micro frontend structure utilizing Vite Module Federation
Two user roles:
Admin: able to add and delete songs
User: restricted to viewing, searching, and sorting songs
Song list equipped with filtering, sorting, and reset functionalities
Basic in-memory login system (no backend)

Tech Stack:
React
- Vite
- JavaScript / TypeScript
- Tailwind CSS for styling
- Module Federation plugin (@originjs/vite-plugin-federation)
- Deployed with Netlify or Vercel

To run the app:
cd main-app
npm install
npm run dev

For the music library
cd ../music-library
npm install
npm run dev

