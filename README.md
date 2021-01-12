# bhive
distribute bots, auto exec, on cloud with event-driven

Let's build a system like https://github.com/muesli/beehive but run on kubernetes. And use Pub/Sub Framework to get input stream event and output stream event, not build-in channel,https://github.com/silverswords/pulse but anything realize pub/sub interface or is a message queue.https://github.com/ThreeDotsLabs/watermill Use distribute K/V store and modern future DB to store data, OSS like MinIO. 
Then use workflow to automated our every work on Scaleable Cloud with Kubernetes. https://github.com/uber/cadence
