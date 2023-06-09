# Object-Detection-System
An object detection system using the TensorFlow Object Detection API.
You need to have TensorFlow and OpenCV installed. Additionally, you should have a pre-trained object detection model saved in a directory, and you need to specify the path to that directory in the tf.saved_model.load() function.

The perform_object_detection() function takes an image path as input, performs object detection on the image using the pre-trained model, and returns the detections. You can then process and display the detections based on your specific requirements.

Remember to replace 'path_to_model_directory' with the actual path to your model directory and 'path_to_image.jpg' with the path to your input image.
