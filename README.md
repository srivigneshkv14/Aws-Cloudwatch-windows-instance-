Monitoring

Monitoring means tracking the performance and health of your EC2 instance (e.g., CPU usage, disk activity, network usage, etc.)

• See if the resources are being used or idle.

• Set alerts when usage goes high or low.

• Take actions automatically Ex:like stopping the instance if idle too long.

CloudWatch is the AWS service that collects these metrics.

It's not possible to use mutiple resources under single alarm, each alarm is associated to track  each resource.
