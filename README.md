# RabbitMQ-Docker-NodeJS
Simple Publish Subscribe model using RabbitMQ created using Docker Container and using Node.js

#Steps:

1. Install docker

2. Check if installed
-> docker -v

3. Create RabbitMQ container
-> docker run --name rabbitmq -p 5672:5672 rabbitmq

4. Create amqplib
-> npm install amqplib

5. create consumer.js and publisher.js

6. Write the code for simple queue to push and consume number

7. Add scipts in package.json

"scripts": {
    "publish": "node publisher.js",
    "consume": "node consumer.js"
  }

 8. Open two terminals

 9. On first terminal enter command
 -> npm run consume

 10. On second terminal enter command with sample numbers
 -> npm run publish 100
 -> npm run publish 200


