#  Edges

Make `POST`, `PUT`, `GET` & `DELETE` queries to manipulate the __edges__

[https://ibm-graph-docs.ng.bluemix.net/api.html#edge-apis](https://ibm-graph-docs.ng.bluemix.net/api.html#edge-apis)

Example:

`curl $GRAPHURL/edges -X POST -H "Content-Type: application/json" -d "{ \"outV'": 256, \"label\": \"knows\", \"inV\": 512 }"`
