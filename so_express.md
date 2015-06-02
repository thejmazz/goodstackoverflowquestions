# good stackoverflow questions
## express

[How to put middleware in it's own file in Node.js / Express.js]
(http://stackoverflow.com/questions/14958296/how-to-put-middleware-in-its-own-file-in-node-js-express-js)

This how you define your routes:

*routes.js*
~~~js
module.exports = function(app) {
    app.get('/', function(req, res) {
        // root directory
    })

    app.get('/home', function(req, res) {
        // home directory
    })
}
~~~

This is you define your middlewares:

*middleware.js*
~~~js
module.exports = {
    
}

Express: How to pass app-instance to routes from a different file?
http://stackoverflow.com/questions/10090414/express-how-to-pass-app-instance-to-routes-from-a-different-file
