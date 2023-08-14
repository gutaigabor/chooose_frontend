# Install and run

## Mock server

### Install

```
cd ./mock_api_server

npm install -g json-server
```

### Run

```
json-server --watch data.json --port 3001
```

## Frontend

### Install
```
cd ./chooose_react

npm install
```

### Run

```
npm run dev
```

# Test data JSON file

- location: './mock-api-server/data.json'
- after change in file, mock api server restart required

# Unit Tests

There is an example unit test: './chooose_react/tests/App.test.tsx'

```
cd ./chooose_react

npm run test
```

# Environment

./chooose_react/.env: .env file is uploaded into git repo only because of the test task nature 