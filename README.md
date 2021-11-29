# REAL TIME VIOLENCE DETECTION USING VIDEO SURVEILLANCE
## Introduction
“Surveillance is safety and security.”

Despite the increased surveillance using many CCTV cameras, people etc the crime rates are rising rapidly. Many countries now employ public video surveillance as a primary tool to monitor population movements and to prevent crime and terrorism, both in the private and public sectors.
The idea is to develope a full software solution for safety and surveillance that turns traditional CCTVs from only recording / evidence collecting into a crime prevention and detection tool, providing safety and security. This tech will work in real-time and show the statistics of all the CCTV surveillance.   
Our proposed method will ensure public safety and security without requiring any human intervention, while also providing an immediate alarm to the appropriate authorities. Our method attempts to instil a sense of security in men and women through crowd monitoring and behavioural analysis.
Through our proposed approach, the constant rise of criminal actions, their unexpectedness, and the breadth of harm that can be caused can be exponentially curtailed.

<br>


## DATASET-

https://github.com/airtlab/A-Dataset-for-Automatic-Violence-Detection-in-Videos

We have chosen a dataset from github consisting of 400+ videos scraped off internet which are classified as “violent” and “non-violent”.

	"cam1" and "cam2" are two subdirectories of the repository in github
            
	"non-violent/cam1" has 60 clips that depict non-violent behaviour"non-violent/cam2" has 60 movies that feature the same non-violent behaviours as "non-violent/cam1,"              but shot with a different camera and from a different perspective.
            
	There are 115 clips in "violence/cam1" that depict violent behaviour.
            
	"violence/cam2" has 115 clips that feature the same aggressive behaviours as "violent/cam1," but from a different camera and point of view.


## NEURAL NETWORK ARCHITECTURE (CUSTOMIZED CNN) 
A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance to various aspects/objects in the image/video and be able to differentiate one from the other. The pre-processing required in a CNN is much lower as compared to other classification algorithms. While in primitive methods filters are hand-coded, with enough training, CNN have the ability to learn these filters/characteristics.

Some parameters that we are using are

        Optimizer: Adam

        Loss: BinaryCrossEntropy

        Epochs: 30

        steps_per_epoch: 50


## TECH STACK –
NodeJS- Backend of our website
OpenCV- Video processing,
Tensorflow- neural Network Architecture


## 💼 &nbsp; Testing

Execute the following sequence of code to start contributing and testing:
- Open the directory labelled Website using the command
    ```sh
    cd Website
    ```

- Install all the dependencies using
    ```sh
    pip3 install -r requirements.txt
    ```

- Run the migrations using the following commands
    ```sh
    python3 manage.py makemigrations
    ```
    ```sh
    python3 manage.py migrate
    ```

- Run the Django server by
    ```sh
    python3 manage.py runserver
    ```

<br>


