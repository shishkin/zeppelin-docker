# Apache Zeppelin Docker Image

## Build


    $ docker build -t zeppelin .

## Run


    $ docker run -d --name zeppelin -p 8080:8080 -p 8081:8081 zeppelin

Then open http://localhost:8080/ in the browser.

