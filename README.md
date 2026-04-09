# Apache Kafka

## Focus:

### 1. Leader and Follower Mechanics

- How one broker becomes the leader
- How followers replicate data from the leader
- What happens when a leader fails and a new leader is elected

### 2. The Controller Role

- The controller is elected through ZooKeeper
- It manages partition assignments
- It handles broker failures
- A new controller is elected if the current one fails

### 3. Message Persistence

- The log segment structure
- How messages are appended sequentially
- How indices map offsets to file positions

### 4. Client-Broker Protocol

- The binary protocol format
- Request/response patterns
- How clients discover and connect to the right brokers
