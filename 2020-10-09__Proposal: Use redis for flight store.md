### Decision 
* Decide to use redis for flight store
### 
### Positive Consequences
* More efficient memory storage compared to memcached
* Access to better data structures to represent queues
### 
### Negative Consequences
* Redis is single threaded
* Need to run in cluster mode for better effectiveness, so might cost more money
