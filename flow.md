```bash
npx create-react-app . --template typescript
npm install --save-dev json-server@v0.17.4

cd src
mkdir server
cd server

touch routes.json # { "/api/*": "/$1" }

mkdir db
cd db
touch data.json
touch index.js

# ...

npm run serve
```

