# Philly Crime

For our project, we took an aim at applying quick sort and dijkstra's algorithm to a data set that contains information about crimes that occured within the Philadelphia area in a large range of years. This dataset was found on Kaggle and has information such as when and where the crime took place along with the type of crime that it was. Just for example, we can see that some common themes in these crimes were thefts, vandalism or assaults. Our program is setup so that you can see the safest path possible from one district (node) to another. The weights on them are the amount of crimes within that district over time. Quicksorting is used in a way that essentially organizes the data based on frequency and sorts the crimes with percentages to sort.

## How the project works

Our sorting algorithms will ensure that the program neatly organizes the data based on the user's input. So if a user wanted to view the crime type, they could type that into the prompt and the system will organize and arrange the dataset appropriately based on the prompt. In addition to this, there will be a graph that outputs a visualization of the organized data.

## A Snapshot of the KaggleData Since the file is much too large to upload onto Github

![Screenshot 2024-12-02 150924](https://github.com/user-attachments/assets/4ad6031a-8317-45ad-9d70-93dd930487a6)


## Significance of project
Our Philly Crime project is significant because it utilizes the important concepts that we learned in class. It helps us understand more about the topic of sorting larger files and manipulate the data so that we can help the user find what they want to see in terms of crime statistics within the Philadelphia areas.

# Usage Instructions
Access the colab notebook here: https://colab.research.google.com/drive/1-0R6A_UST8uw0xqOde3DM8y68_YgR7x8?usp=sharing

# Structure of the code
## CSV parsing and Data Preprocessing
The kagglehub module is used to easily load the kaggle dataset into the colab environment automatically. The dataset is in the form of a csv, with each row representing a reported crime with several additional columns of information.

## Counting
Simple algorithms are used to count the number of crimes that occur under certain specifications, such as by year, police zone, hour, or any combination of attributes, such as most common crime type by hour.

## Graphing and Djikstra's algorithm
Using an adjacency list of the nearest police zones in the Philadelphia region, and a list containing the counts of crime by each police zone, a graph is formed where each node is connected based on geographical adjacency, with the weights being the amount of crime reported in the adjacent zone. Djikstra's algorithm is then used to find the shortest path (path with least crime) to get from one zone in Philadelphia to another.

# Functionalities and Test Results 

![Untitled](https://github.com/user-attachments/assets/25aa8c3a-2572-46a2-a503-96f75f660c60)

![Untitled](https://github.com/user-attachments/assets/f543cb6d-7537-463f-8840-915f156d5ff8)

![Untitled](https://github.com/user-attachments/assets/b9f6c98f-4228-4810-9551-5ebc8f6423d1)

![image](https://github.com/user-attachments/assets/8f4d807c-4981-48fa-bc59-83331424e940)
