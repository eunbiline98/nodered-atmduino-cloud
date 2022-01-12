# nodered-atmduino-cloud

This code will run HTTP server with MQTT-over-websocket capabilities. So, you need to replace `mqtt://` protocol with `ws://` one

Mqtt heroku Deploy

```
$ git add .
$ git commit -m "Intial Commit"
$ heroku login or heroku login -i
Enter your Heroku credentials.
...
$ heroku create
Creating mqtt-cloud-atmduino.herokuapp.com... done, stack is cedar
http://mqtt-cloud-atmduino.herokuapp.com// | git@heroku.com:mqtt-cloud-atmduino.herokuapp.com.git
Git remote heroku added
$ git push heroku main
...
-----> Node.js app detected
...
-----> Launching... done
       http://mqtt-cloud-atmduino.herokuapp.com deployed to Heroku
```

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?button-url=https://github.com/eunbiline98/nodered-atmduino-cloud/master&template=https://github.com/eunbiline98/nodered-atmduino-cloud/master)

  <a href="https://nodered-atmduino.herokuapp.com/ui/">
    <img src="https://img.shields.io/badge/nodered-%23E4405F.svg?&style=for-the-badge&logo=nodered&logoColor=white" height=35>
  </a> 

