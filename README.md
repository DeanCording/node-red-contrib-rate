# node-red-contrib-rate
A Node Red node for calculating the rate of change of a message property.

Rates of change are calculated based on the message topic, so multiple topics can be passed
through the node to calculate the individual rates of change for each topic.

*Rate Period* specifies the number of timestamp units the rate of change is calculated for.  For example, if the timestamp is in millseconds, *Rate Period* of 1000 would calculate the rate of change per second.
