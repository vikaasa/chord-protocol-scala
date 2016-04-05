README:

Source Files Location:
src/main/scala-2.11/Chord/*

Usage: 
sbt "run numNodes numRequests"

Description:
We have implemented the chord protocol, which is a distributed lookup protocol that addresses the problem of determining the location of a node that stores a desired data item efficiently. 
Given a key, Chord maps the key onto a node. Data location can be easily implemented on top of Chord by associating a key with each data item, and storing the key/data pair at the node to which the key maps.
Chord adapts efficiently as nodes join and leave the system, and can answer queries even if the system is continuously changing. 
