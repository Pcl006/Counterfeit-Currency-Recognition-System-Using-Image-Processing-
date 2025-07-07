Counterfeiting cash represents the illicit replication of unique currency; thus fake currency is a illegal currency that has not been approved by the government. Reserve bank of India (RBI) is the main body which has sole obligation to print currency notes in India. But RBI faces the issue of fake currency notes once sifted and coursed in the market consistently. Prior fake currency detection was finished by utilizing chemical properties of the currency paper. With the approach of computerized reasoning and image processing, advanced image processing is as often as possible utilized for fake currency detection by separating properties from images that speak to the highlights of currency. Feature extraction is testing function as it includes the extraction of legitimately or in a roundabout way unmistakable highlights of Indian currency. Security highlights of a currency are basic for deciding genuine and fake monetary forms. Basic security highlights incorporate watermarks, idle images, security thread, intaglio, optically factor ink, smaller scale lettering and fluorescence . In the proposed work, a methodology for fake currency detection is introduced that removes the general qualities, for example, shape, including the security thread, RBI logo and recognizable proof imprint from the image of the paper currency. Advanced Image Processing is a field that includes concentrating just as processing of images by removing properties from images and incorporates the acknowledgment of individual articles. Extricating properties for images of currency notes can get very unpredictable as it includes the extraction of some obvious and imperceptible highlights of Indian currency.

In this work, fake currency detection system for Indian Notes is proposed. Initially a database of various bonafide Indian notes of various denomination are prepared and test conducted for comparison between input image and database images. Firstly, the input currency images are preprocessed for conversion from RGB to gray for easy of further process, input image noisy images are median filtered for noise reduction. To keep the maximum features, DTCWT (Dual Tree Complex Wavelet Transform) are applied on the preprocessed images. This wavelet transform retains the maximum features of images without more losses. This wavelet transform comprises of a couple of DWT(Discrete Wavelet Transform) trees. In DTCWT, a genuine flag is connected to the two trees for decay and the yields of the both remade tress are found the middle value of toward the finish of the recreation stage. The DTWCT was created to defeat the absence of move in variance property of customary DWT. Next to the wavelet transform application, k-means segmentation algorithm for clustering the input images such as 200, 500 or 200 etc. is implementated and compare the features of the image and classified it as original or fake note. 

The proposed system is based on image processing and makes the process robust and automatic.
We used INR and USD as an example to illustrate the technique. This system is based on our knowledge about computer science technologies like Digital Image Processing, python and also a small step to implement in a system that is most important for industrial development. We had considered INDIAN Rupee and US Dollar for this project. Project can expand for more currencies inclusion according to use.

Algorithms Used
Edges are significant local changes of intensity in a digital image. An edge can be defined as a set of connected pixels that forms a boundary between two disjoint regions. There are three types of edges: 
•	Horizontal edges
•	Vertical edges
•	Diagonal edges
Edge Detection is a method of segmenting an image into regions of discontinuity. It is a widely used technique in digital image processing like 
 
•	pattern recognition
•	image morphology
•	feature extraction

Edge detection allows users to observe the features of an image for a significant change in the gray level. This texture indicating the end of one region in the image and the beginning of another. It reduces the amount of data in an image and preserves the structural properties of an image. 

CNN Algorithm
1)	Feature Extraction: CNN compose of multiple layers and first layer define for feature extraction and this features will be extracted from given input image dataset or any other multidimensional dataset.
2)	Feature Selection: Using this layer features will be selected by applying a layer called pooling or max polling.
3)	Activation module: using this module RELU will be applied on input features to remove out unimportant features and hold only relevant important features
4)	Flatten: This layer will be define to convert multidimensional input features into single dimensional input array
5)	Dense: This layer can be used to connect one layer to other layer to receive input features from previous layer to new layer to further filter input features in next layer to get most important features from dataset to have best prediction result.


UML stands for Unified Modeling Language. UML is a standardized general-purpose modeling language in the field of object-oriented software engineering. The standard is managed, and was created by, the Object Management Group. 
The goal is for UML to become a common language for creating models of object oriented computer software. In its current form UML is comprised of two major components: a Meta-model and a notation. In the future, some form of method or process may also be added to; or associated with, UML.
	The Unified Modeling Language is a standard language for specifying, Visualization, Constructing and documenting the artifacts of software system, as well as for business modeling and other non-software systems. 
The UML represents a collection of best engineering practices that have proven successful in the modeling of large and complex systems.
 The UML is a very important part of developing objects oriented software and the software development process. The UML uses mostly graphical notations to express the design of software projects.

USER  REQUIREMENTS:

Home:
Use case ID	Currency-Recognition-System-Using-Image-Processing
Use case Name	Home button
Description	Display home page of application
Primary actor 	User
Precondition	User must open application
Post condition	Display the Home Page of an application
Frequency of Use case	Many times
Alternative use case	N/A
Use case Diagrams	
Attachments	N/A

Upload Image:
Use case ID	Currency-Recognition-System-Using-Image-Processing
Use case Name	Upload Image button
Description	Show window For selection of image 
Primary actor 	User
Precondition	User must open application
Post condition	Display the window for selecting image
Frequency of Use case	Many times
Alternative use case	N/A
Use case Diagrams	
Attachments	N/A

Recognize:
Use case ID	Currency-Recognition-System-Using-Image-Processing
Use case Name	Recognize button
Description	This button is used for currency recognition. After pressing this button currency recognition will start and you will get output in few seconds on the application window
Primary actor 	User
Precondition	User must open application
Post condition	This button is used for currency recognition. After pressing this button currency recognition will start and you will get output in few seconds on the application window
Frequency of Use case	Many times
Alternative use case	N/A
Use case Diagrams	
Attachments	N/A


Reset:
Use case ID	Currency-Recognition-System-Using-Image-Processing
Use case Name	Resetbutton
Description	This button is used to clear the application window.
Primary actor 	User
Precondition	User must open application
Post condition	This button is used to clear the application window.
Frequency of Use case	Many times
Alternative use case	N/A
Use case Diagrams	
Attachments	N/A

Exit:
Use case ID	Currency-Recognition-System-Using-Image-Processing
Use case Name	Exit button
Description	This works as simple exit button.
Primary actor 	User
Precondition	User must open application
Post condition	This works as simple exit button.
Frequency of Use case	Many times
Alternative use case	N/A
Use case Diagrams	
Attachments	N/A

Currency Recognition System Using Image Processing
In this paper author is using image processing algorithm called Template Matching to recognized currencies of different countries as local peoples are familiar about their currency and they will be unaware of different currency so by using this application they can upload image and then system will match the pattern of different countries currency with uploaded image and then predict the one with highest matching.
In propose paper author is using currency exchange API to know the rate of that currency as per Indian rupee but this exchange API is not working as they are asking for payment. By paying 1000 dollars we can purchase that API so I am ignoring it and in below screen you can see that payment option
 
![image](https://github.com/user-attachments/assets/4b6295af-10c2-4b42-ae26-0d2902e97609)
If we use free account then its giving error like below screen
![image](https://github.com/user-attachments/assets/36d98fd8-9202-4d9a-a35e-958d0e6932c3)
In above screen you can see exchange rate is giving error when trying to access free account.
SCREEN SHOTS
To run project double click on ‘run.bat’ file to get below screen
![image](https://github.com/user-attachments/assets/ffc6d7eb-b5f6-4138-b5a3-202add362b6d)
In above screen click on ‘Upload Currency Image’ button to upload currency images like below screen
![image](https://github.com/user-attachments/assets/6d960622-3b38-4735-870f-03cfcd5fafdb)
In above screen selecting and uploading ‘1.jpg’ file and then click on ‘Open’ button to load image and then click on ‘Run Template Matching Currency Recognition’ button to get below output
![image](https://github.com/user-attachments/assets/edbaefc4-fe31-48ec-a4d3-9179a0711ef8)
In above screen first image is the training image template and second image is the original image so by applying template matching algorithm we can predict correct currency not and that currency not recognized as INR 100.


