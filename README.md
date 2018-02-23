# Simple ThoughtSpot Webapp

A simple HTML/javascript page to call ThoughtSpot's APIs, using:

1. Basic auth
2. Use REST to fetch pre-defined answer as JSON
3. Use iFrame to embed a specific visualisation
4. Use iFrame to embed a specific pinboard

## Config

Clone this repo, and:

1. Create simple viz/pinboard in ThoughtSpot
2. Edit corresponding vars in `tsapi.html` for your ThoughtSpot environment with viz/pinboard ids
3. Enable CORS on ThoughtSpot
4. Install tomcat and copy `tsapi` dir to (for Mac Brew install): /usr/local/Cellar/tomcat/9.0.5/libexec/webapps
5. `catalina start`
6. Point your web browser at [http://localhost:8080/tsapi/tsapi.html] 

Then click through the buttons provided, ensuring you auth first. 


