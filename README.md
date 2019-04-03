# RMQ-Post
Library to Post RMQ message

This library is used by any generic microservice to post an RMQ message which is turn forwared to the next subsystem.  All the below inputs are obtained from DB queries.

Inputs: RoutingKey, RMQ ExchangeName, RMQ UserName, RMQ Password, Port, VhostName, Service FQDN

Output: RMQ Post Success / Failure message
