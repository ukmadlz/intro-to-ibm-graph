#  Indexes

Make `POST`, `PUT`, `GET` & `DELETE` queries to manipulate the __indexes__

[https://ibm-graph-docs.ng.bluemix.net/api.html#index-apis](https://ibm-graph-docs.ng.bluemix.net/api.html#index-apis)

Example:

`curl $GRAPHURL/index?type=vertex -X POST -H "Content-Type: application/json" -d "{ \"type\": \"vertex\", \"propertyKeys'": [{\"name\": \"personName\", \"dataType\": \"String\", \"cardinality\": \"SINGLE\"}], \"indexOnly\": {\"name\": \"person\"}, \"composite\": true, \"name\": \"vByPerson\"}"`
