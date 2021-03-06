# Computer vision in the new era of Artificial Intelligence and Deep Learning
## Visión por computador en la nueva era de la Inteligencia Artificial y el Deep Learning

This repository contains a collection of Jupyter Notebooks as well as other resources (e.g. presentations, links, ...) that are going to be used during the "Second quarter university extension course" that the University of Oviedo is going to teach (online). For more information about this course, you can check the following [URL](https://www.uniovi.es/estudios/extension/cursos2c/-/asset_publisher/SEp0PJi4ISGo/content/vision-por-computador-en-la-nueva-era-de-la-inteligencia-artificial-y-el-deep-learning?redirect=%2Festudios%2Fextension%2Fcursos2c)

Work in progress :construction:

**Objectives**

   :heavy_check_mark: To know the current context of computer vision in the new era of artificial intelligence and Deep Learning
   
   :heavy_check_mark: To know the main tools and strategies for problem solving using different data sources
   
   :heavy_check_mark: Knowing how to handle computer tools and specific software for digital image processing
   
   :heavy_check_mark: Understanding how basic digital image processing and analysis methods and techniques work

**Content**

 :heavy_check_mark: Introduction to OpenCV and Python
 
 :heavy_check_mark: Basic image treatment
 
 :heavy_check_mark: Image processing
 
 :heavy_check_mark: Machine learning (Scikit-learn)
 
 :heavy_check_mark:Deep learning (Tensorflow, Keras, PyTorch)
 
The target audience is broad and includes
 * People who have experience in computer science (maybe to graduate level) but who do not know about OpenCV
 * People who are studying other subjects and want to play with computer vision 





## Introduction

[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Introduction.pdf)

## Notebooks

### Colab utilities and tricks for computer vision

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:| ------------:|
| Colaboratory introduction | 10 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/notebooks_and_colab_introduction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/notebooks_and_colab_introduction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Colab.pdf) |
| Collection of features, utilities and tricks on Colab and/or Python | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/collection_of_some_features_utilities_and_tricks.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/collection_of_some_features_utilities_and_tricks.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Colab_features_utilities_and_tricks.pdf) |
| Take image from webcam as numpy array in Colab | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/take_image_from_webcam_as_numpy_array.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/take_image_from_webcam_as_numpy_array.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Take_image_and_vide_in_colab.pdf) |
| Take video from webcam in Colab | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/take_video_from_webcam_in_colab.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/take_video_from_webcam_in_colab.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Take_image_and_vide_in_colab.pdf) |
| Explore, execute and see the output of external Python scripts | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/explore_and_execute_external_scripts_in_colab.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/explore_and_execute_external_scripts_in_colab.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Explore_execute_and_see_external_python_scripts.pdf) |
| Create and show multiple images in the same figure with matplotlib | 15 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/show_multiple_images_same_figure_plt.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/show_multiple_images_same_figure_plt.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Show_multiple_images_same_figure_plt.pdf) |
| Install Colab utilities (https://github.com/albertofernandezvillan/colaboratory-utils) | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/colaboratory_utils.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/colaboratory_utils.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Install_colab_utilities.pdf) |

### Introduction to Python and NumPy

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:| ------------:|
| Introduction to Python| 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/python_introduction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/python_introduction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Python.pdf) |
| Introduction to Numpy | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/numpy_introduction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/numpy_introduction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Numpy.pdf) |


### OpenCV notebooks for computer vision

#### OpenCV basics

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:| ------------:|
| Basic image treatment (color and grayscale images) in OpenCV | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/basic_image_treatment_with_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/basic_image_treatment_with_opencv.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_basics.pdf) |
| BGR color format in OpenCV | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/bgr_color_format_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/bgr_color_format_opencv.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/BGR_color_format_opencv.pdf) |
| Drawing basic figures (points, lines, poligonal curves,...) in OpenCV | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/basic_drawing_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/basic_drawing_opencv.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_drawing.pdf) |
| Drawing text and symbols in OpenCV | 10 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/drawing_text_and_symbols_in_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/drawing_text_and_symbols_in_opencv.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_drawing.pdf) |

#### Image processing with OpenCV

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:| ------------:|
| Geometric image transformations in OpenCV | 15 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/geometric_image_transformations_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/geometric_image_transformations_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| OpenCV sliders for image processing | 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/opencv_sliders_introduction_image_processing.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/opencv_sliders_introduction_image_processing.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| Visual interfaces (with buttons and sliders) for image processing with OpenCV | 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/visual_interface_image_processing_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/visual_interface_image_processing_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| Computational photography module in OpenCV | 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/computational_photography_module_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/computational_photography_module_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| Inpainting with OpenCV| 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/inpaint_algorithm_in_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/inpaint_algorithm_in_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| K-means clustering for color quantization with OpenCV | 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/k_means_clustering_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/k_means_clustering_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| References for main image processing techniques and algorithms in OpenCV | 50 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/references_for_main_image_processing_techniques_in_opencv.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/references_for_main_image_processing_techniques_in_opencv.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |
| Some packages for face processing in Python| 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/face_processing.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/face_processing.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Image_processing_with_opencv.pdf) |


#### Configure OpenCV with GPU on Colab and benchmarking inference speed
| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Configure OpenCV with GPU con Colab |  20 min |[Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/configure_opencv_with_gpu_on_colab.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/configure_opencv_with_gpu_on_colab.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_gpu_colab_inference.pdf) |
| Benchmarking GPUS vs CPU with OpenCV in Colab (human pose estimation)|  20 min |[Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/benchmarking_inference_speed_gpu_vs_cpu_opencv_on_colab.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/benchmarking_inference_speed_gpu_vs_cpu_opencv_on_colab.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_gpu_colab_inference.pdf) |
| Benchmarking GPUS vs CPU with OpenCV in Colab (YOLO V4) |  20 min |[Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/yolo_v4_opencv_dnn.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/yolo_v4_opencv_dnn.ipynb) |[Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/OpenCV_gpu_colab_inference.pdf) |

### Machine learning for computer vision

#### Introduction to scikit-learn for classification, regression and clustering

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Scikit-learn introduction for classification | 40 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/scikit_learn_introduction_classification.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/scikit_learn_introduction_classification.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Scikit_learn.pdf) |
| Scikit-learn introduction for regression | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/scikit_learn_introduction_regression.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/scikit_learn_introduction_regression.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Scikit_learn.pdf) |
| Scikit-learn introduction for clustering (color quantization) | 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/k_means_clustering_sklearn.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/k_means_clustering_sklearn.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Scikit_learn.pdf) |
| Closed eyes detection | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/closed_eyes_detection.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/closed_eyes_detection.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Scikit_learn.pdf) |

#### Introduction to pandas

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Pandas introduction | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pandas_introduction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pandas_introduction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Pandas_introduction.pdf) |
| Minimal example using both scikit-learn and pandas for classification | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pandas_and_scikit_learn_introduction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pandas_and_scikit_learn_introduction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Pandas_introduction.pdf) |



#### Introduction to metrics in scikit-learn

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Metrics for classification  | 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/metrics_for_classification_with_scikit_learn.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/metrics_for_classification_with_scikit_learn.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Scikit_learn_metrics.pdf) |



### TensorFlow and Keras

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|-------------:|
| Simple MNIST convnet | 15 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/simple_mnist_convnet_keras.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/simple_mnist_convnet_keras.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/IntroductionDeepLearning.pdf) |
| Simple MNIST convnet (2) | 15 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/simple_mnist_convnet_keras_2.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/simple_mnist_convnet_keras_2.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/IntroductionDeepLearning.pdf) |
| Using a pre-trained model for inference using Keras Applications| 15 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_prediction.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_prediction.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |
| Set up Kaggle API in Colab| 5 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/set_up_kaggle_api_in_colab.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/set_up_kaggle_api_in_colab.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |
| Using Keras Applications for feature extraction in a classification problem with scikit-learn| 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_feature_extraction_for_classification.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_feature_extraction_for_classification.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |
|Using Keras Applications for feature extraction in a clustering problem with scikit-learn| 25 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_feature_extraction_for_clustering.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_feature_extraction_for_clustering.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |
|Image and dataset augmentation| 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_imagedatagenerator_and_dataset_augmentation.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_imagedatagenerator_and_dataset_augmentation.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |
|Transfer learning using Keras Applications| 35 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_transfer_learning_dogs.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/keras_applications_transfer_learning_dogs.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/TensorFlow_and_Keras.pdf) |

### PyTorch

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Tensors| 30 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_1_tensors.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_1_tensors.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/PyTorch.pdf) |
| Learning| 60 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_2_learning.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_2_learning.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Learning.pdf) |
| Neural networks| 40 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_3_network.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_3_network.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Networks.pdf) |
| Transfer learning| 40 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_4_transfer.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pytorch_4_transfer.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Transfer.pdf) |

# Other topics

##  Introduction to flask (for computer vision)

| Lesson        | Estimated time needed | Source Code  | Colab |
| ------------- |:---------------------:| :-----------:| -----:|
| Minimal example showing how to create and deploy a Flask app for computer vision| 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/flask_app_on_colab_for_computer_vision_minimal_example.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/flask_app_on_colab_for_computer_vision_minimal_example.ipynb) |

## Introduction to Roboflow

| Lesson        | Estimated time needed | Datasets  | Models | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Datasets and models | 50 min | [Open](https://public.roboflow.com/) | [Open](https://models.roboflow.com/) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/Models.pdf) |

# Other resources
## Additional packages and libraries for computer vision and image processing in Python

### Introduction to Pillow: Python Imaging Library (PIL Fork)

| Lesson        | Estimated time needed | Source Code  | Colab | Presentation |
| ------------- |:---------------------:| :-----------:| -----:|------------:|
| Pillow: Python Imaging Library (PIL Fork)| 20 min | [Open](https://github.com/albertofernandezvillan/dl-ml-notebooks/blob/main/pil_introduction_python.ipynb) | [Open](https://colab.research.google.com/github/albertofernandezvillan/dl-ml-notebooks/blob/main/pil_introduction_python.ipynb) | [Presentation](https://github.com/albertofernandezvillan/computer-vision-and-deep-learning-course/blob/main/presentations/PIL.pdf) |

### [Scikit-image](https://scikit-image.org/) (Image processing in Python)


| Repository    | description |
| ------------- |:-----------:| 
|<img src="assets/github.png" width="20" height="20"> [scikit-image](https://github.com/scikit-image/scikit-image) | scikit-image: Image processing in Python|
|<img src="assets/github.png" width="20" height="20"> [skimage-tutorials](https://github.com/scikit-image/skimage-tutorials) | scikit-image tutorials|

> Stéfan van der Walt, Johannes L. Schönberger, Juan Nunez-Iglesias,
> François Boulogne, Joshua D. Warner, Neil Yager, Emmanuelle
> Gouillart, Tony Yu, and the scikit-image contributors.
> *scikit-image: Image processing in Python*. PeerJ 2:e453 (2014)
> https://doi.org/10.7717/peerj.453


### [Mahotas: computer vision in Python](http://luispedro.org/software/mahotas/) (Image processing and computer vision in Python)


| Repository    | description |
| ------------- |:-----------:| 
|<img src="assets/github.png" width="20" height="20"> [mahotas](https://github.com/luispedro/mahotas) | mahotas: Python Computer Vision Library|
|<img src="assets/github.png" width="20" height="20"> [mahotas-demos](https://github.com/luispedro/mahotas/tree/master/mahotas/demos) | mahotas tutorials and demos|

> Luis Pedro Coelho Mahotas: Open source software for scriptable
> computer vision in Journal of Open Research Software, vol 1, 2013.
> [[DOI](http://dx.doi.org/10.5334/jors.ac)]


## Additional packages and libraries for machine learning in Python

### [Dlib](http://dlib.net/) (C++ toolkit (with python API) containing machine learning algorithms and tools)

| Repository    | description |
| ------------- |:-----------:| 
|<img src="assets/github.png" width="20" height="20"> [dlib](https://github.com/davisking/dlib) | dlib library|
|<img src="assets/github.png" width="20" height="20"> [Examples: Python](https://github.com/davisking/dlib/tree/master/python_examples) | mini-tutorials for using dlib from Python (face detection, tracking, recognition or alignment)|

> KING, Davis E. Dlib-ml: A machine learning toolkit. The Journal of Machine Learning Research, 2009, vol. 10, p. 1755-1758.


Work in progress :construction:




## Course poster
![Course poster](https://raw.githubusercontent.com/albertofernandezvillan/dl-ml-notebooks/main/assets/course_poster_final.png)
