dog-detector-kafka-consumer
==============================

Generated using the template [opendatahub-io/odh-s2i-project-simple](https://github.com/opendatahub-io/odh-s2i-project-simple)

Buildable Python [source to image](https://github.com/openshift/source-to-image) project that creates a simple Kafka consumer service that reads images from a queue and pushes predictions on a new queue.  Takes a pretrained object detection model from [openimages_v4/ssd/mobilenet_v2](https://tfhub.dev/google/openimages_v4/ssd/mobilenet_v2/1).  Jupyter Notebooks for working with the model included.