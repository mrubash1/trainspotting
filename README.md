# Trainspotting Blog Post Series
If you have ever ridden the train, you know that the delay estimates Caltrain provides can be a bit…off. Sometimes a train will remain “two minutes delayed” for ten minutes after the train was already supposed to have departed, or delays will be reported when the train is on time. The idea for Trainspotting came from our desire to integrate new data sources for delay prediction beyond scraping Caltrain’s API . Since we had previously set up a Raspberry Pi to analyze train whistles, we thought it would be fun to validate the data coming from the Caltrain API by capturing real-time video and audio of trains passing by our office near the Mountain View station.

We describe this process in a series of posts:
    [Introduction to Trainspotting](https://svds.com/introduction-to-trainspotting/)
    [Image Processing in Python](http://www.svds.com/image-processing-python/)
    [Streaming Video Analysis with Python](http://www.svds.com/streaming-video-analysis-python/)
    [TensorFlow Image Recognition on a Raspberry Pi](http://svds.com/tensorflow-image-recognition-raspberry-pi/)
    [Deploying a Cloud-Enabled IoT Device]()

### Using this repository
We have included several demo jupyter notebooks that include code featured in the above blog posts. These notebooks import several custom modules we have written for image and video processing (found in the [src folder](/src)).

###  [TensorFlow Image Recognition on a Raspberry Pi](http://svds.com/tensorflow-image-recognition-raspberry-pi/)
[![Alt text for your video](https://img.youtube.com/vi/n0lCPXzaxTg/0.jpg?raw=true "TensorFlow Image Classification on a Raspberry Pi")](https://www.youtube.com/watch?v=n0lCPXzaxTg)

### [Streaming Video Analysis with Python](http://www.svds.com/streaming-video-analysis-python/)
[![Alt text for your video](https://img.youtube.com/vi/oLg50i2-No8/0.jpg?raw=true "Streaming Video Analysis with Python")](https://www.youtube.com/watch?v=oLg50i2-No8)
