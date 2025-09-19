# Project: Automated File Updating in Python

## Objective
The goal of this project was to develop a Python script to automate a common security administration task: removing specific IP addresses from an allow list file. [cite_start]This demonstrates the ability to use programming to create efficient and repeatable security solutions[cite: 956, 957].

## Process & Tools Used
[cite_start]The script was developed in a **Jupyter Notebook** and followed a clear algorithm[cite: 958]:
1.  [cite_start]**Read File:** The script opens a text file named `allow_list.txt` and reads its contents into a string variable[cite: 971, 972].
2.  [cite_start]**Convert to List:** The string of IP addresses is converted into a Python list using the `.split()` method for easier manipulation[cite: 984, 985].
3.  **Iterate and Remove:** The script iterates through the list of IP addresses. [cite_start]A conditional statement checks if an IP address is present in a predefined `remove_list`[cite: 1015, 1016, 1017]. [cite_start]If a match is found, the `.remove()` method deletes that element from the list[cite: 1019].
4.  [cite_start]**Rewrite File:** The cleaned list is converted back into a string using the `.join()` method[cite: 1044, 1045]. [cite_start]The original `allow_list.txt` file is then opened in write mode (`"w"`) and overwritten with the updated string[cite: 1045].

## Skills Demonstrated
* **Python Scripting:** Writing clean, commented code to perform a specific task.
* **Automation:** Creating a script to automate a manual security process, reducing the chance of human error.
* **File I/O:** Reading data from and writing data to text files.
* **Data Structures:** Manipulating data effectively by converting between strings and lists.
* **Algorithmic Thinking:** Defining a step-by-step process to solve a problem.