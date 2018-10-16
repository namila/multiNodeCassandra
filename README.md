# multiNodeCassandra
A multinode cassandra cluster using docker compose

Use docker-compose to start the cluster

<code>docker-compose up</code>

Connect to the first node of the cluster using cqlsh

<code>docker run -it --link cassandra1:cassandra --network=mulinodecassandra_cassandra-network --rm cassandra cqlsh cassandra</code>
