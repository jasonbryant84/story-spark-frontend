# Frontend
Frontend Reaect & NextJS to handle server side rendering where possible for client. Will run on port `3000` at url `http://127.0.0.1:3000`

## Setup
From root directory...

### Install
Install dependencies

`npm install`

Start frontend server

`npm run dev`

### Sanity Check

Healthcheck can be executed [here](http://127.0.0.1:3001/healthcheck) to ensure the backend is up and running. CORS not implemented for this endpoint.

### Env Vars

.env.local
```bash
NEXT_PUBLIC_BACKEND_HOST=http://127.0.0.1
NEXT_PUBLIC_BACKEND_PORT=3001
```