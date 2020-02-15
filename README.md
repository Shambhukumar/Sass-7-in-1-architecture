# SASS-7-IN-1-ARCHITECTURE 

This is simple project using the sass 7 in 1 architecture and sticking to Sass Guidelines writing conventions

    In the Development Environment running live-server and the watch the file parallely 
   
    npm start 
    "start": "npm-run-all --parallel devserver watch:sass"
    
    For converting sass to normal css file with prefixes and also compressed in size
    npm build:css 
    "build:css": "npm-run-all compile:sass prefix:css compress:css"
