# Test streaming twiiter data and storing them in Kafka using the topic 'hello'

Steps:
1. Get twitter creds (either get file from me or get your own)
2. Install binary of Kafka version 2.12-2.1.0
3. runs these commands (pip install kafka-python, pip install python-twitter, pip install tweepy)
4. Runs these commands in seperater terminals in order
	- bin/zookeeper-server-start.sh cfig/zookeeper.properties
	- bin/kafka-server-start.sh config/server.properties
	- python TwitterStreaming.py