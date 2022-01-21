# nrf_to_gcloud
Created from blog post: https://devzone.nordicsemi.com/guides/cellular-iot-guides/b/software-and-protocols/posts/how-to-connect-nrf91-to-google-cloud

```
This blog post covers how to connect to Google Cloud with an nRF9160 DK. The nRF9160 DK is using MQTT protocol to communicate with Google Cloud IoT Core, a service that connects to and manages IoT Devices. The project code is attached at the end of this post.

We used the Cloud IoT Core to get data from the nRF9160 DK into Pub/Sub, which is Google Cloud’s internal messaging service that allows us to send and receive messages from and to IoT devices. From here we used Cloud Functions as a functionality to react on, among other things, Pub/Sub events or HTTP triggers.
```
