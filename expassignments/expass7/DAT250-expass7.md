
**Experiment assignment 7 report**

Link to repo: https://github.com/eivindszalay/RabbitMQTUT

**Experiment 1: Installation**

It was quite straightforward to complete the installation.

I installed RabbitMQ into python with command:
	
	python3 -m pip install pika --upgrade

*Technical issues*

I had trouble getting RabbitMQ to work in Java. Maven did not recognise the dependency or something. I swapped over to python, here thing were much smoother.

**Experiment 2**

The code for the first part is in the folder "Hello World".

*What I did*

I implemented the sender and receiver.

I executed them in different terminals and got them to send messages.

*Technical issues*

I had trouble getting RabbitMQ to work in Java. Maven did not recognise the dependency or something. I swapped over to python, here thing were much smoother.



**Experiment 3**

The code for this part is in the folder "Queue messaging".


*What I did*

I implemented new_task and worker.

This time i used three terminals, one for creating tasks and two for workers for handeling the queue. The round-robin algorithm was successful.

I included message acknowledgment and durability.

Lastly, I added fair dispatch.

**Experiment 4**

The code for this part is in the folder "Topics".

*What I did*

I implemented emit_log.py which publishes a message for all subscribing processes.

I implemented receive_log.py which subscribes to and consumes the messages that are published.

Again, running the programs in two different processes, I got them to send and receive a message.

