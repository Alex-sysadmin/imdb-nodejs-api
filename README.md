
**IMDB Node.js Module**
----------------------------
This module  is made for [IMDB.com](http://imdb.com) website that allows  you to get any details about any Movie/TvShow .

## Dependencies
This module requires  the following packages to  be installed :

 - Request
 - Body-parser (Use POST input parameters)
 - Express

## How to install
To install this module, run the command below :

    $ git clone https://github.com/blackhair/imdb-nodejs-api.git
    $ npm install
Now you can use the package's method by runing it  : 
    
    
    $ node index.js
    
then, you can use the below method on port :3000 . 
Movie/Serial information can be retrieved  using this URL pattern : 


    http://localhost:3000/t=[Movie Ttile] // For get specific movie
    http://localhost:3000/s=[Movie Ttile] // For search the similar name 
    http://localhost:3000/i=[IMDB ID] // For get movie info by IMDB ID
