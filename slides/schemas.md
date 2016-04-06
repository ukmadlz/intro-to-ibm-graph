#  Schemas

Make `POST` & `GET` queries to manipulate the __schemas__

[https://ibm-graph-docs.ng.bluemix.net/api.html#schema-apis](https://ibm-graph-docs.ng.bluemix.net/api.html#schema-apis)

Example:

`curl $GRAPHURL/schema -X POST -H "Content-Type: application/json" -d "{ \"edgeindexes\": [], \"edgelabels\": [ {\"multiplicity\":\"simple\", \"name\":\"r\"} ], \"propertykeys\": [ {\"cardinality\":\"single\", \"datatype\":\"string\", \"name\":\"c\"} ], \"vertexindexes\": [ {\"composite\":false, \"name\":\"ci\", \"propertykeys\":[ \"c\" ], \"unique\":false} ], \"vertexlabels\": [ {\"name\": \"l\"} ] }"`
