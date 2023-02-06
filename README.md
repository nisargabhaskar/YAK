# Yet Another Kafka (YaK):
YaK or Yet Another Kafka is one of the projects that can be chosen as part of the Big Data Course at PES University. It involves setting up a mini-Kafka on a student's system, complete with a Producer, Subscriber and a Publish-Subscribe architecture.

## Team Members:
* PES1UG20CS261 - Natasha Cheri Satish 
* PES1UG20CS268 - Nisarga Bhaskar
* PES1UG20CS274 - Paladugula Lakshmi Snigdha 
* PES1UG20CS299 - Prarthana Prasanna Rajapurohit

Steps to implement code: 
```
python3 zookeeper.py
python3 broker1.py
python3 consumer.py
python3 producer.py
```
Run the above four commands in different terminals.

If broker1, which is currently the leader broker fails, run "python3 broker2.py". Broker2 becomes the leader broker followed by which if it fails run "python3 broker3.py" which makes broker3 the leader broker.

Log file of the producer, consumer outputs(steps) has been created, a sample of which is put in the repository.

"big_data" folder in the repository is the directory created for a topic name and is used to store messages in partitions that are created in the directory.

