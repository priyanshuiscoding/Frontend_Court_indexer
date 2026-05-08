# Court File Indexer Frontend

React and Vite frontend for the Court File Indexer.

## Manual Ubuntu Run

Run the backend first, then start the frontend:

```bash
cd ~/Court-file-indexer/Frontend_Court_indexer
cp .env.example .env
npm install
npm run dev -- --host 0.0.0.0
```

Default `.env`:

```bash
VITE_API_BASE_URL=http://localhost:8000/api/v1
VITE_BACKEND_BASE_URL=http://localhost:8000
```

Open:

```text
http://localhost:5173
```

Build for production:

```bash
npm run build
npm run preview -- --host 0.0.0.0
```
