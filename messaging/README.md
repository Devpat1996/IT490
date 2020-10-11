# How to use RabbitMQ Management

## What do I need in docker-compose.yml?
...
messsaging: 
	image: 'rabbitmq: 3.8.8-mangament'
	ports:
		- 15672:15672
...

You would have to specify that you are using the management version and
you need to forward port 15672. 

## How do I get to the web-interface?
You can get to the web interface by going to htpp://localhost:15672

## What does it show ?

In the Queues tabe under "All queues" it will show you any queues that you have 
made. 

If you navigate to connections tab, you would be able to see everyone who is 
connected to this instance. 