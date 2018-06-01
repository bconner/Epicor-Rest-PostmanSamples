# Using the Postman Samples

While the Help is useful we find one of the easiest ways to explore and test the services
to be [Postman](https://www.getpostman.com/). This project contains a Postman Collection
which is a set of runnable examples showing how to use all the basic features of the
services that you can point to your environment and modify. To set that up:

* Install [Postman](https://www.getpostman.com/)

* Import the [Sample Collection](https://github.com/bconner/Epicor-Rest-PostmanSamples/blob/master/Erp10RestSamples.json.postman_collection).
See [this](https://www.getpostman.com/docs/collections)
for details on importing a collection.

* [Add/Update an environment](https://www.getpostman.com/docs/environments) for your
local server. The collection includes a Host environment variable which you should
change to your test server's api root url.

At that point you can explore the collection and run any of the samples.
