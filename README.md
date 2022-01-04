# Health_Log-Database
In this project we are using a MongoBD database which is storing all the information from Health_Log app

Fisrt data from app is saved in txt files named patients.txt, hospitals.txt and doctors.txt. Now the data inside the txt file are streamed through Kafka using the concept of consumer and producer. We start zookeeper server and Kafka server and run each producer and consumer program one by one. While each pairs runs the data gets saved into mongo db in the database Health_Log. Inside Health_log database we create three collections names patients, doctors and hospital. So when we run cosumer producer program all the data gets subscribe to topic 'test_topic' and data gets save in database in the collections.
