# AI Custom Model MarketHub

MarketHub is a model-license marketplace. Demo credit is **HUB**. Node (Express) serves the API and the built React app from `client/dist`. `npm start` only runs the Node server.

## Demo accounts

Password: `demo1234`

| Email | Role |
| --- | --- |
| `maya@markethub.local` | Builder with listed lots |
| `kai@markethub.local` | Licensee / buyer |
| `nova@markethub.local` | Secondary trader |

## Run

```bash
npm install
cd client
npm install
cd ..
npm run build
npm start
```

Open `http://127.0.0.1:9030/`. `npm start` does not run webpack. Rebuild the client only when source files change: `npm run build`.
