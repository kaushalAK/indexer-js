# coinshift

This project aims at downloading and indexing transactions on Ethereum network.

Introduction: It's a basic ETL program where we are requesting data from a blockchain node and then store it in a database. Making it more accessible to use.

This is an event based system The event module enables us to listen to specific events. We have an Ethereum publisher, to which we can subscribe to a topic. All sorts of events get broadcasted to the network by the publisher. As a subscriber, we can choose which topic to subscribe to.

Steps to run the code:

To get access to a test Sepolia Network, an ethereum node is required, as we cannot mock actual data at scale, hence this adaptor was used. You will need a project id to access this node.
Once the node is setup. Use the node url to start your subscription to listen to events.
MySQL is being used, please setup a local mysql and provide the same in the subsequest service classes.
Run the application and use the endpoints to start indexing transactions and blocks.
