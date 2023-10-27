## BDI Hadoop/Spark – Lab 2
### Understanding HDFS File System 

#### Lab: Using HDFS Commands
This lab explores how files are added to, removed from, and viewed in HDFS.

**Table 1. About this lab**

- **Objective:** Become familiar with how files are added to and removed from HDFS and how to view files in HDFS.
- **Sample File locations:** [https://raw.githubusercontent.com/zilonguiuc/badm558/main/sales_tab.txt](https://raw.githubusercontent.com/zilonguiuc/badm558/main/sales_tab.txt)
- **Successful outcome:** You will have added and deleted several files and folders in HDFS.
- **Before you begin:** Ensure your Hadoop cluster is up and running within your GCP.
- **Related lesson:** The Hadoop Distributed File System (HDFS)

Your Hadoop cluster has all the features of a Master Node (NameNode & other management features) and 2 Compute Nodes (DataNode, etc). 

> **Note:** HDFS is installed on top of the Linux File systems. In this lab, we will work with both the Local Linux File System and the Hadoop File System. Generally, Hadoop commands start with `hadoop` or `hdfs`.

#### Perform the following steps:
##### Step 1: View the hdfs dfs Command
1. Open a three-node Hadoop cluster using your GCP dataproc account.
2. Use the code below to check your current path in the Linux system (default working folder):
'''
pwd

'''
3. Create a data folder and navigate into the data folder:
