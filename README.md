# Emulated-Hadoop-DFS-Storage
Emulated Hadoop DFS Storage: Implemented block-based storage, node-based data lookup, and efficient partitioning techniques to simulate Hadoop Distributed File System (HDFS) behavior. Achieved seamless data retrieval and visualization using Firebase, MongoDB, and Python Streamlit dashboard. 

<img src="https://github.com/blm3886/Emulated-Hadoop-DFS-Storage/blob/main/1.png" width=100% height=80%>

# ● Front-End Development:
The user interface is crafted using Streamlit, a Python web development framework, providing an intuitive dashboard experience. 
The dashboard mimics Hadoop DFS storage operations, enabling users to interact effortlessly with the backend databases.


# ● Implementation of the Back-end:
This project focuses on emulating a robust back-end system, replicating a file system-based storage structure. 
Data management is distributed across MongoDB and Firebase, creating a versatile storage architecture reminiscent of a File System. 
The architecture comprises essential nodes, namely the Data Node, Metadata Node, and the unique FileLocations Node on Firebase.

Components:

Data Node:
Responsible for storing the datasets' contents, ensuring efficient data storage and retrieval.

Metadata Node:
Manages metadata associated with directories and files, storing essential information such as ID, Type (DIRECTORY/FILE), and the parent directory/file reference (previousNode).

Index Node (Firebase Exclusive):
Crucial node on Firebase, facilitating the identification of data partition storage location (Firebase or MongoDB), ensuring seamless data retrieval.

<img src="https://github.com/blm3886/Emulated-Hadoop-DFS-Storage/blob/main/2.png" width=100% height=80%>
<img src="https://github.com/blm3886/Emulated-Hadoop-DFS-Storage/blob/main/3.png" width=100% height=80%>
<img src="https://github.com/blm3886/Emulated-Hadoop-DFS-Storage/blob/main/4.pngg" width=100% height=80%>
