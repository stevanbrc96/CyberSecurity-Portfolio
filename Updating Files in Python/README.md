# **Project: Automated File Updating in Python**

## **Objective**

The goal of this project was to develop a Python script to automate a common security administration task: removing specific IP addresses from an allow list file.

## **Process & Tools Used**

The script was developed in a **Jupyter Notebook** and followed a clear algorithm:

1. **Read File:** The script opens a text file named allow\_list.txt and reads its contents into a string variable.  
2. **Convert to List:** The string of IP addresses is converted into a Python list using the .split() method for easier manipulation.  
3. **Iterate and Remove:** The script iterates through the list of IP addresses. A conditional statement checks if an IP address is present in a predefined remove\_list. If a match is found, the .remove() method deletes that element from the list.  
4. **Rewrite File:** The cleaned list is converted back into a string using the .join() method. The original allow\_list.txt file is then opened in write mode ("w") and overwritten with the updated string.

## **Skills Demonstrated**

* **Python Scripting:** Writing clean, commented code to perform a specific task.  
* **Automation:** Creating a script to automate a manual security process, reducing the chance of human error.  
* **File I/O:** Reading data from and writing data to text files.  
* **Data Structures:** Manipulating data effectively by converting between strings and lists.  
* **Algorithmic Thinking:** Defining a step-by-step process to solve a problem.