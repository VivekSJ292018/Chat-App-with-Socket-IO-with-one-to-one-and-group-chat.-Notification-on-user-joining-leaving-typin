# Chat-App-with-Socket-IO-with-one-to-one-and-group-chat.-Notification-on-user-joining-leaving-typin [NOT DEPLOYED YET]


ReactJS Heroku and Socket.io Chat App 

1. First you’ll need to fork or download the respository.
2. Then in terminal you’ll install the node modules

npm install

    npm install express –save
    npm run build
    npm start

Then you can run it using


## npm run react to start React dev server. npm run server to start NodeJS Socket.io server.

For deploying on Heroku:-

    git init git initialize
    vim .gitignore edit .gitignore and add node_modules/* to exclude node_modules from being pushed
    git status git status
    git add . git add .
    git commit -m "new react socket chat heroku deployment" git commit -m “your update”
    npm run build npm run build
    heroku login herokuapp cli login
    heroku create create randomized directory name from heroku cli
    git push heroku master git push from heroku orig to heroku master
    open heroku: https://taskchatvivek.herokuapp.com/ 

