# Object-Detection-Using-ML


The scope of the project is to make it easier and convenient for the user to know the details 
about the objects around them and this approach can also be used to meet many other requirements
in AI in classifying real-world objects and make machines capable of having similar vision like humans,
it can also be used for security purposes when the dataset is changed. In this system, we will be having
various daily used objects as database and classify even the very similar looking objects.

2. General Description
Product Perspective:
The Object detection using machine learning project is a mobile application-based system. The application integrates two vast domains, namely, 
the Android operating system and Machine learning to identify objects. The application is built and tested on Android Studio and programmed in
java therefore it can only run on an android based device and the camera is used to detect the objects.

Product Functions:
The product (application) allows the user to detect and identify their surrounding common appliances and objects using their camera.
The product is designed in such a way that it would even distinguish the differences between similar objects in the database. 
The database comprises of machine learning models made by using a large number of images of the object in different conditions such as lighting,
background, etc which allows the product to be more precise and accurate while displaying the results. 
The product is also capable of showing the result on real-time while using camera instead of taking pictures to process through the algorithm,
thereby enhancing effectiveness.

User characteristics:
	The main categories of users of the product are end-users or the customers and the product developers or testers. 
  The user has only the access of the end application which can be run on an android smartphone. The product contains a simple UI which
  allows the user to find objects by allowing the camera permission and point at objects to gather the information regarding the object.
  On the other hand, the developer or tester used the application firstly in android studio in system to debug and improvise the code 
  and later to test it using very similar objects like a lemon and a tennis ball, on a mobile application to know the customer perspective of the application. 
  
General Constraint:
	The application is user friendly and requires no additional training to use and provide free usage after the installation. 
  It doesn’t involve in any financial transactions or require additional permissions other than the camera access so the safety 
  of the customer is not compromised. The application will be compatible with most android smartphones. The application runs on a 
  finite database so the product is not intended to detect every object which it is pointed to, but it is expected to detect the objects 
  in database at high accuracy, i.e distinguishing between very similar objects which was our main motive since the beginning of this project.
  
Assumptions and dependencies:
	It is assumed that the end device (android smartphone of user) is in correct working condition for example, 
  the user camera doesn’t have and issues and the product is installed on the device with android version higher than KitKat (4.0).
  Also, it is assumed that the installation was carried out without missing any minor chunk of code. 
  The product is partially dependent on the TensorFlow lite software which is used to implement machine learning algorithms on the android smartphone.
 
3. Functional Requirements
Basic Requirements of the application are as follows:
•	Detect an object using camera
•	Work in real-time without the need for the user to take images or to store them.
•	Show accuracy right below the image in real-time, i.e., the percentage of similarity between the object kept in front and the object it was matched to in our database.
•	Provide a simple easy to use interface.
4. Non-Functional Requirements

Security:
•	No user info is collected or stored to ensure maximum safety
•	Only camera permission is required for the functioning of the application
•	The photos captured by the camera during use would not be stored and discarded immediately for privacy purposes.
•	The database can only be accessed by developer so there is no mis-information regarding the results obtained.

Performance:
•	Real-time results are shown along with accuracy of the results
•	No slow down or lag is expected on the device

Reliability:
•	The application shows the accuracy in percentage of the result letting the user to know how much they should depend on the application
Maintainability:
•	Database is updated frequently in real time.
•	Errors are detected and corrected from iteration to iteration.
5. System Architecture and Model
The project follows the Iterative System Model as it allows the work to be done in parallel and also do iterations of product to keep improving it every iteration.
The product contains a simple system of four main categories mainly the Requirements Gathering (all documentation and user requirements come under this category),
Front-end (this part contains all the User Interface components of the application like design, layout, etc), 
ML Model (This part contains the dataset which is used to train using machine learning to create a model for the database) and finally the software or code part
(this part include the programming in java and integrating the ML with android and using TFlite software and testing it).


