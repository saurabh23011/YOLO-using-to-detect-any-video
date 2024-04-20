# YOLO-using-to-detect-any-video
![Untitled video - Made with Clipchamp](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/7e2166a1-39b8-41d2-bea8-a5859e583b53)
Single-shot object detection
Single-shot object detection uses a single pass of the input image to make predictions about the presence and location of objects in the image. It processes an entire image in a single pass, making them computationally efficient.

However, single-shot object detection is generally less accurate than other methods, and it’s less effective in detecting small objects. Such algorithms can be used to detect objects in real time in resource-constrained environments.

YOLO is a single-shot detector that uses a fully convolutional neural network (CNN) to process an image. We will dive deeper into the YOLO model in the next section.
Two-shot object detection
Two-shot object detection uses two passes of the input image to make predictions about the presence and location of objects. The first pass is used to generate a set of proposals or potential object locations, and the second pass is used to refine these proposals and make final predictions. This approach is more accurate than single-shot object detection but is also more computationally expensive.

Overall, the choice between single-shot and two-shot object detection depends on the specific requirements and constraints of the application.

Generally, single-shot object detection is better suited for real-time applications, while two-shot object detection is better for applications where accuracy is more important.

Object detection models performance evaluation metrics
To determine and compare the predictive performance of different object detection models, we need standard quantitative metrics.

The two most common evaluation metrics are Intersection over Union (IoU) and the Average Precision (AP) metrics.

Intersection over Union (IoU)
Intersection over Union is a popular metric to measure localization accuracy and calculate localization errors in object detection models.

To calculate the IoU between the predicted and the ground truth bounding boxes, we first take the intersecting area between the two corresponding bounding boxes for the same object. Following this, we calculate the total area covered by the two bounding boxes— also known as the “Union” and the area of overlap between them called the “Intersection.”

The intersection divided by the Union gives us the ratio of the overlap to the total area, providing a good estimate of how close the prediction bounding box is to the original bounding





![63c6c085946c7a8a435eb5c9_iou](https://github.com/saurabh23011/YOLO-using-to-detect-any-
video/assets/154420149/cfe36d20-7cb0-4727-80c3-2292a54738b4)
![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/b3579f43-0827-4669-a6ad-8a88b4544d6d)



![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/d8704857-19d3-4d2d-b63c-56b148c074ad)
![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/517be0cc-64f7-4836-962a-32fff77fdce2)


![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/4aad2d46-05c4-4e37-ae0f-48ad97a078c9)

![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/3670cdcb-39ca-4a15-8e1e-62084256581e)



![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/8dcd53a7-9b6f-4191-b7cd-1fedc3b28c5b)

![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/755fc5b4-569c-48a7-b7df-8f62c4629680)


![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/3f48e021-d27f-4cb3-9d60-32814dfe9ba6)


![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/ee3539de-d7e8-4315-9302-0a2432124302)



![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/026cffd5-e245-4e2d-af97-2a0f44905af8)



![image](https://github.com/saurabh23011/YOLO-using-to-detect-any-video/assets/154420149/dd77db18-641e-411f-8db9-9a9277e486d5)





box.

Intersection over union
