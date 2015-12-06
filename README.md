vagrant-cassandra-spark
=======================

A work in progress.

Installs:
* Cassandra
* Spark

Prereqs:
* Vagrant
* Ansible (for provisionining)

To get going:
```
vagrant up
vagrant ssh
```

Then on the box:

```
spark-shell   // for spark shell

cqlsh   // for cassandra
```

The spark shell command has been aliased to include the connector on the classpath so you're ready to follow the examples on the connector [help page](https://github.com/datastax/spark-cassandra-connector/blob/master/doc/2_loading.md).

You can access the spark master [here](http://192.168.10.11:8080/).