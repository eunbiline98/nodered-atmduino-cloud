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
Creating arcane-lowlands-8408... done, stack is cedar
http://arcane-lowlands-8408.herokuapp.com/ | git@heroku.com:arcane-lowlands-8408.git
Git remote heroku added
$ git push heroku main
...
-----> Node.js app detected
...
-----> Launching... done
       http://arcane-lowlands-8408.herokuapp.com deployed to Heroku
```

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?button-url=https://github.com/eunbiline98/nodered-atmduino-cloud/tree/master&template=https://github.com/eunbiline98/nodered-atmduino-cloud/tree/master)
