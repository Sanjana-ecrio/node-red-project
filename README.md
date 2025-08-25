# node-red-project
# Node-RED Contact App

## How to Deploy

### 1. Install dependencies

```bash
npm install express mongoose body-parser cors node-red
npm install node-red-dashboard
```

### 2. Start MongoDB

```bash
mongod
```

### 3.Start Node-RED server

```bash
npm start
```

### 4. Open Node-RED editor

Go to:
http://localhost:1880/red

### 5. Import Node-RED flows

Import subflows.json first → Deploy

Import dashboard.json and contacts.json → Deploy

### 6. Open dashboard

Go to:
http://localhost:1880/ui
