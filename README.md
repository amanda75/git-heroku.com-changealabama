git-heroku.com-changealabama
============================
var app = express.createServer(express.logger());  
     
   app.get('/', function(request, response) {  
   -  response.send('Hello World!');  
   +  response.send('A startup is a business built to grow rapidly.');  
    }))     
  var port = process.env.PORT || 5000;  
    app.listen(port, function() {  
       console.log("Listening on " + port);  
    -});  
   +}); 
  
  
