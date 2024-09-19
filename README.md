# ECE2112-PA4: Data Wrangling and Data Visualization
Name: CRUZ, Christian Enzo B.</br>
Section: 2ECE-D</br></br>

Instructions:</br>
Download the ECE Board Exam 2 dataset found on this link: bit.ly/ECEBoardExamDataset and write a
Python script/code in the Jupyter Notebook to do the given problems.</br></br>

#### ECE BOARD EXAM PROBLEM
First and foremost we have to import any related library by using the function below.</br>
![image](https://github.com/user-attachments/assets/b96255ef-ac5c-4e81-b661-8e8bce612241)</br>

#### 1. Now we import the data frame that will be used for number one. We first have to define the file then we use the function .read to be able to display and read it. This is shown on the figure below.</br>
![image](https://github.com/user-attachments/assets/7c4f1afc-c508-410d-a7c6-94e7bf71048a)</br>

###### a. Now that we have imported the file into our notebook, we are now tasked to find the Name, GEAS grade, and Electronics grade of the students from Luzon and has a college Track of Instrumentation.</br></br>

This can be done by using splicing we first have to set the parameters by using the following code functions.</br>
![image](https://github.com/user-attachments/assets/359c6a82-b837-44ae-b9b0-a5ddf27af07d)</br>
After doing so we have to input the specified columns we have to display adding the following to our function.</br>

![image](https://github.com/user-attachments/assets/56d1bd43-7568-4c43-b0e4-de3949c090e4)</br>
The function above would display the following.</br>
![image](https://github.com/user-attachments/assets/a85b9e42-0a7a-48f9-bb5a-a6115e0c2b68)</br></br>

###### b. As for letter b we are tasked to find the Name, Track, Electronics grade, and Average grade of a Female student residing in Mindanao. But since our data frame doesn't have a Avarage column yet we have to create one using the function below.</br>
![image](https://github.com/user-attachments/assets/5dbf8128-9d07-42c4-80cd-9fe672a7c6bd)</br>
Explaining the image above, I defined the column Average as the mean of each of the courses grade.</br></br>
After creating a new column 'Average', we can now use our previous function to find the specified students we just have to change the parameters alittle. This can be shown on the image below.</br>
![image](https://github.com/user-attachments/assets/50649bb8-f214-473e-99d1-1fd30c8157ef)</br></br>

#### 2. On number two we are tasked to create a visual so we could analyze whether different features contributes to average grade.
To do this I first imported the plot library shown on the function below.</br>
![image](https://github.com/user-attachments/assets/979c2e2f-185f-4325-9026-54da88ba88b6)</br>
After doing so we can now plot our graph by using the function below.</br>
![image](https://github.com/user-attachments/assets/fd770265-37d8-4014-bff2-d57f006da22c)</br>
Now we that we have completed the graph that displays the Average grade with respect to the college track chosen by the student, we can now just change the parameters of our graph to display the average grade with respect to gender and their hometown shown on the last two images below</br>
![image](https://github.com/user-attachments/assets/8c26ca9f-3a9e-43c2-90e1-7cf510855cb4) </br>
![image](https://github.com/user-attachments/assets/a1d9dbe2-a8ae-4cdd-9f47-42ecc74bce99)

