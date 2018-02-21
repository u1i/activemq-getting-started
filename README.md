# Running ActiveMQ

## Run dockerized ActiveMQ

docker run -p 61616:61616 -p 8161:8161 u1ih/activemq

## Manage in the browser

http://localhost:8161/

## Get commandline client

https://github.com/fmtn/a/

## Read messages from a testqueue

java -jar a-1.4.2-jar-with-dependencies.jar -c 10 testqueue



