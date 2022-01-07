# [Developing a Single Page App with FastAPI and Vue.js](https://testdriven.io/blog/developing-a-single-page-app-with-fastapi-and-vuejs/)

## Requirements

Docker: make sure your docker deamon is running
Node v16.6.1: `node -v` -> v16.8.0
npm v7.20.3: `npm install -g npm`, `npm -v` -> 8.3.0
Vue CLI v4.5.13: `npm install -g @vue/cli`, `vue --version` -> @vue/cli 4.5.15
Python v3.9: Docker / PyCharm > Add Interpreter > Virtualenv

## FastAPI Setup
Remark: make sure your docker deamon is running

## Routing
1) When setting JWT token as cookie, https was disabled with (secure=False), this would need to be improved in prod.
2) Testing suggestions listed + [other tutorial](https://testdriven.io/blog/fastapi-crud/)
