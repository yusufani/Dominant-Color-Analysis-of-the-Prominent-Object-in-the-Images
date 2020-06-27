# Dominant Color Analysis of the Prominent Object in the Images

In the research, it was aimed to determine the dominant color of the most important object in an image. It can be used in many places in daily life in the study. It can be used to determine the colors preferred by the employees of a company in their clothes, to determine the dominant color of the clothes in a fashion show or to determine the dominant car color preference in a region.

In the research, the intended result is obtained by applying a series of different processes to the image. First of all, the introduction image is converted into a suitable format and it is divided into sections with semantic integration method supported by deep learning. The linked component labeling method is used to detect the largest object in the segmented image. Then, only the pixel values of the largest object are sent to the color quantization function using k-mean. Finally, the pixels of the largest object whose colors are reduced are displayed to the user with the help of graphics.

The success of the transaction has been tested through a questionnaire. The output of our model for 20 images was shown to about 20 people and asked to score between 1 and 5. The success of the system is shown by taking the average of the points given by the users.


## Required Libraries

```bash
Tensorflow 1.14
PIL (Python Image Library)
matplotlib
numpy
sklearn
```

## Usage

1-) For the work of the project, you need Deeplabv3 Semantic Segmentation model. You can train model from Semantic Segmantation Model Training.ipynb or You can download trained model from [here](http://download.tensorflow.org/models/deeplabv3_pascal_trainval_2018_01_04.tar.gz).

2-) The results can be obtained by running the Dominant Color Analysis of the Prominent Object in the Images.ipynb file in an environment that supports Jupyter Notebook (it can be Google Colab or Jupyter) by running all the codes in order from top to bottom.
## Results

A: It is the input image.
B: Result image from semantic segmentation.
C: Labeling the largest object by applying CCL(Connected Component Labeling) on result B
D: Reducing the object in result C  to 4 colors by color quantization
E: Colors of the prominent object is the graph of the column.
F: Colors of the prominent object is the pie chart.
G: The color of the whole image is the graphic of the column.
H: Colors of the whole image is the pie chart.

![Alt text](Images/sample1.png?raw=true "Sample-1")
![Alt text](Images/sample2.png?raw=true "Sample-2")
![Alt text](Images/sample3.png?raw=true "Sample-3")
![Alt text](Images/sample4.png?raw=true "Sample-4")
![Alt text](Images/sample5.png?raw=true "Sample-5")
![Alt text](Images/sample6.png?raw=true "Sample-6")
![Alt text](Images/sample7.png?raw=true "Sample-7")
![Alt text](Images/sample8.png?raw=true "Sample-8")
![Alt text](Images/sample9.png?raw=true "Sample-9")
![Alt text](Images/sample10.png?raw=true "Sample-10")
![Alt text](Images/sample11.png?raw=true "Sample-11")
![Alt text](Images/sample12.png?raw=true "Sample-12")
![Alt text](Images/sample13.png?raw=true "Sample-13")
![Alt text](Images/sample14.png?raw=true "Sample-14")
![Alt text](Images/sample15.png?raw=true "Sample-15")

## Contact 
Yusuf Anı - yusufani8@gmail.com
Tarık Çarlı - pro.tarikcarli@gmail.com
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
