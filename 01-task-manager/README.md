# Task-Manager
### Projeto criado para estudo e prática em Node.js

## Project setup
```
npm install
```

### Set you Database MongoDB
#### create file .env
```
EXEMPLE:
MONGO_URI=mongodb+srv://USER:PASSWORD@HOST/taskmanager?retryWrites=true&w=majority
```

### Run Node Serve
```
node index.js
```
### Routes
>app.get('/api/v1/tasks')           - get all the tasks
>app.post('/api/v1/tasks')          - create a new task  
>app.get('/api/v1/tasks/:id')       - get single task
>app.patch('/api/v1/tasks/:id')     - update task
>app.delete('/api/v1/tasks/:id')    - delete task

