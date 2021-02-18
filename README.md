# computer-science-quiz-app
A quiz app built using Vue.Js for the fronted and Opentdb Api for fetching the questions for the quiz.

# To run the application
Using npm
```
$ npm install
$ npm run build
$ npm start
```

Using docker
```
docker build -t comp-quiz-app .
docker run -p 8080:80 --rm --name quiz-app comp-quiz-app
``` 
You can access the server on [`localhost:8080`](http://localhost:8080/) in your browser.


#### Open Trivia Api: https://opentdb.com/api_config.php
