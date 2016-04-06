#  Gremlin

Make `POST` queries to manipulate your entire Graph

[https://ibm-graph-docs.ng.bluemix.net/api.html#gremlin-apis](https://ibm-graph-docs.ng.bluemix.net/api.html#gremlin-apis)

Example:

`curl $GRAPHURL/gremlin -X POST -H "Content-Type: application/json" -d "{\"gremlin\": \"def g = graph.traversal(); g.V(256).out().out()\"}"`
