# Running ActiveMQ

## Run dockerized ActiveMQ

docker run -p 61616:61616 -p 8161:8161 u1ih/activemq

## Manage in the browser

http://localhost:8161/

## Get commandline client

https://github.com/fmtn/a/

http://nordlander.co/activemq-command-line-utility-a/

## Put a message onto a queue

a -p "Hello, world" testqueue

## List queues and topics

a -l

## Read 10 messages from a queue

a -c 10 testqueue

## Listen to incoming messages in a queue

a -g -c 1000 -w 0 testqueue

# Publish to a topic

a -p "hello" topic:gossip




