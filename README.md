# heroku-noDB

Node/Express w/o db

make sure you have Heroku CLI installed
log in to heroku.com
from your dashboard create a new app & name it as you see fit
note: you can create apps from Heroku CLI, but they will be named randomly for you so I prefer to do this
make sure your port settings are using process.env.PORT
make sure your dependencies have been npm installed with --save make sure your app has an npm start command
test your app
browse to your project's folder in terminal
make sure you are logged in to heroku with heroku login
after loggin in, you must connect the app to heroku with heroku git:remote -a HEROKUPROJECTNAME
push your work to the heroku project: git push heroku master
to see the logs from heroku's terminal run heroku logs
