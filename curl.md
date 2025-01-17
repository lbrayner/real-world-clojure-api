```bash
curl http://localhost:3001/greet
curl http://localhost:3001/info
curl -H "Content-Type: application/json" http://localhost:3001/todo -d '{"id": "08904b02-c99b-4af1-890b-86a2978357ed", "name": "Sapo", "items": [{"id": "08563927-afb3-4ca5-9fd1-0aff68feff4a", "name": "Boi", "status": "Done"}]}'
curl http://localhost:3001/todo/08904b02-c99b-4af1-890b-86a2978357ed
```
