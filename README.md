# Sample FedHub Server Profile Layer

This server profile layer contains simple (non complete) configuration to support a FedHub use-case in PingFederate.

It contains a sample Identifier First adapter, Policy contract and policy tree.  It does not contain any external IdP connections, this will need to be done as the next development exercise.

Tested to work with **PingFederate 10.1.0** (pingidentity/pingfederate:10.1.0-edge - https://hub.docker.com/r/pingidentity/pingfederate) using the following base layer:
https://github.com/pingidentity/pingidentity-server-profiles/tree/ea477e708d24102675d3c7bf9e677ff5463e10f7/getting-started/pingfederate

And the following intermediate layer(s):
https://github.com/pingidentity/pingidentity-server-profiles/tree/80209bff8c9d23cb8c38c98f17df298bcff25954/pf-dns-ping-clustering

Refer to the README.md files of the related layers for additional information
