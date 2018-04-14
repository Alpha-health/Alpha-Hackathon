# Alpha Hackathon

## From automatic behavior sensing to improving your life

### Smartphone as a sensor for our behaviours
 
Smartphones have evolved from merely communication devices to personal devices that can help us in our daily life. They come equipped with various sensors capable of capturing mobility patterns (GPS and/or Wi-Fi for indoor positioning), social activity (Bluetooth), physical activity & sedentary time (accelerometer), and so on. Using the combination of these sensors researchers showed that it is possible to detect different activities, such as sleep patterns (using light, noise and screen-on/off events), moreover by analysing longitudinal behavioural patterns it was demonstrated that the phones are also capable of understanding personal traits or mood change patterns.

### Dataset

Dartmouth College has collected a rich data set that contains longitudinally captured mobile sensor data combined with a multitude of questionnaires and surveys focused on mental health of students. They opened it for public research.
You may find the link to the data set here:
http://studentlife.cs.dartmouth.edu/dataset.html

and more information about this study here:
http://studentlife.cs.dartmouth.edu/

NOTE THAT FOR THE COMPETITION YOU'LL BE USING A SUBSET OF THAT DATASET, which you can find here:

https://drive.google.com/open?id=1_60smE2A3p7JWSm5TowrUarER_J4kAPK

### Task

The hackathon can be divided into three tasks:
1. The Data Science task: (i) create a model to predict mood from phone sensor data (ii) find a way to summarize the important features (some sort of dimensionality reduction) that can be use for the user's understanding.
2. The entrepeneurial task: think of a potential application of both the mood inference and the findings with respect to the findings on what drives mood. **Here in Alpha Health, we are developing a platform for helping people optimize their wellbeing through behavior change. Therefore, the application should be tailored towards that goal: helping the user have a better life by changing toxic behaviors.**
3. The design task: create a design that could serve as a base for the development of the aforementioned application.

In order to get started, please follow these steps:
- Create a github repo.
- Download the data with the link above.
- Develop a model that infers the mood of a person (target variable) from the given data.
- Analyze the important features and extract meaning from them.
- Design a representation of the output of the model for the specific application you've thought of.
- Please send us the link to the github repository that contains the code used by the end of the hackathon.
- Prepare a (simple) presentation to explain your solution to the data science problem, the application you came up with and the design you've elaborated.

### Evaluation

As you can see, the three tasks require three different skillsets. The first task is more oriented towards data scientists. The second task requires teamwork and entrepeneurship. The third task has a design component. 

When evaluating the first component of the task we will take into consideration: (i) how comprehensive and creative the features extracted are, (ii) how well they've been summarized for potential interpretations, (iii) the quality of the model, not merely in terms of performance (important but not critical), but also on the way it's been thought, designed and evaluated.

The second task requires a smart idea that both can be useful for users and rigorous from the data science perspective. That entails a tension between the designers and data scientists. An optimal solution should neither be too utopic nor too simple (not every element of the idea needs to have been developed, you can also present future steps).

With respect to the third task, we will be looking at the potential usability of the idea and the attractiveness of the design from the user's perspective.

There is no fixed quantification of the importance of these components. Teams can focus on what they are specialized in. That is, if a team consists only of designers, we will evaluate the result based on the design. That said, the jury will value a balanced solution :)

Note that this  data set is meant to be used for inspiration - we will not use any data from the StudentLife data set for the commercial purposes.
