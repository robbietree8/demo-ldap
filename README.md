## step to reproduce

1. run ./build-and-package.sh
2. run ./start.sh
3. curl -X POST -H "Content-Type: application/json" http://127.0.0.1:8888/login -d '{"username": "user", "password": "123"}'

